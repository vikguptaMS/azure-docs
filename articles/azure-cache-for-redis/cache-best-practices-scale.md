---
title: Best practices for scaling
titleSuffix: Azure Cache for Redis
description: Learn how to scale your Azure Cache for Redis.
author: flang-msft
ms.service: cache
ms.topic: conceptual
ms.date: 08/25/2021
ms.author: franlanglois
---

# Scaling

## Scaling under load

While scaling a cache under load, configure your `maxmemory-reserved` setting to improve system responsiveness. For more information, see [Configure your maxmemory-reserved setting](cache-best-practices-memory-management.md#configure-your-maxmemory-reserved-setting).

## Scaling clusters

Try reducing data as much as you can in the cache before scaling your clustered cache in or out. Reducing data ensures smaller amounts of data have to be moved, which reduces the time required for the scale operation. For more information on when to scale, see [When to scale](cache-how-to-scale.md#when-to-scale).

## Scale before load is too high

Start scaling before the server load or memory usage gets too high. If it's too high, that means Redis server is busy. The busy Redis server doesn't have enough resources to scale and redistribute data.

## Cache sizes

If you're using TLS and you have a high number of connections, consider scaling out so that you can distribute the load over more cores. Some cache sizes are hosted on VMs with four or more cores. By distributing the workloads across multiple cores, you help bring down overall CPU usage on the cache VMs. For more information, see [details around VM sizes and cores](./cache-planning-faq.yml#azure-cache-for-redis-performance).

## Scaling and memory

You can scale your cache instances in the Azure portal or programatically using PowerShell cmdlets, Azure CLI, and by using the Microsoft Azure Management Libraries (MAML).

Either way, when you scale a cache up or down, both `maxmemory-reserved` and `maxfragmentationmemory-reserved` settings automatically scale in proportion to the cache size. For example, if
`maxmemory-reserved` is set to 3 GB on a 6-GB cache, and you scale to 12-GB cache, the settings automatically updated to 6 GB during scaling. When you scale down, the reverse happens.

For more information on scaling and memory, see [How to automate a scaling operation](cache-how-to-scale.md#how-to-automate-a-scaling-operation).

> [!NOTE]
> When you scale a cache up or down programmatically, any `maxmemory-reserved` or `maxfragmentationmemory-reserved` are ignored as part of the update request. Only your scaling change is honored. You can update these memory settings after the scaling operation has completed.


## Next steps

- [Configure your maxmemory-reserved setting](cache-best-practices-memory-management.md#configure-your-maxmemory-reserved-setting)
- [Scale an Azure Cache for Redis instance](cache-how-to-scale.md)
