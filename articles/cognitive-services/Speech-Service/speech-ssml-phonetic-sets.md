---
title: Speech phonetic alphabets - Speech service
titleSuffix: Azure Cognitive Services
description: This article presents Speech service phonetic alphabet and International Phonetic Alphabet (IPA) examples.
services: cognitive-services
author: jiajzhan
manager: junwg
ms.service: cognitive-services
ms.subservice: speech-service
ms.topic: conceptual
ms.date: 02/17/2022
ms.author: jiajzhan
---

# SSML phonetic alphabets

Phonetic alphabets are used with the [Speech Synthesis Markup Language (SSML)](speech-synthesis-markup.md) to improve the pronunciation of text-to-speech voices. To learn when and how to use each alphabet, see [Use phonemes to improve pronunciation](speech-synthesis-markup.md#use-phonemes-to-improve-pronunciation).

Speech service supports the [International Phonetic Alphabet (IPA)](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet) stress and syllable symbols that are listed here. You set `ipa` as the `alphabet` in [SSML](speech-synthesis-markup.md#use-phonemes-to-improve-pronunciation). 

|`ipa` | Symbol         | 
|-------|-------------------|
| `ˈ`   | Primary stress     | 
| `ˌ`   | Secondary stress   | 
| `.`   | Syllable boundary  | 

For some locales, Speech service defines its own phonetic alphabets, which ordinarily map to the [International Phonetic Alphabet (IPA)](https://en.wikipedia.org/wiki/International_Phonetic_Alphabet). The seven locales that support the Microsoft Speech API (SAPI, or `sapi`) are en-US, fr-FR, de-DE, es-ES, ja-JP, zh-CN, and zh-TW. For those seven locales, you set `sapi` or `ipa` as the `alphabet` in [SSML](speech-synthesis-markup.md#use-phonemes-to-improve-pronunciation). 

See the sections in this article for the phonemes that are specific to each locale.

## ar-EG/ar-SA
[!INCLUDE [ar-EG](./includes/phonetic-sets/text-to-speech/ar-eg.md)]

## bg-BG
[!INCLUDE [bg-BG](./includes/phonetic-sets/text-to-speech/bg-bg.md)]

## ca-ES
[!INCLUDE [ca-ES](./includes/phonetic-sets/text-to-speech/ca-es.md)]

## cs-CZ
[!INCLUDE [cs-CZ](./includes/phonetic-sets/text-to-speech/cs-cz.md)]

## da-DK
[!INCLUDE [da-DK](./includes/phonetic-sets/text-to-speech/da-dk.md)]

## de-DE/de-CH/de-AT
[!INCLUDE [de-DE](./includes/phonetic-sets/text-to-speech/de-de.md)]

## el-GR
[!INCLUDE [el-GR](./includes/phonetic-sets/text-to-speech/el-gr.md)]

## en-GB/en-IE/en-AU
[!INCLUDE [en-GB](./includes/phonetic-sets/text-to-speech/en-gb.md)]

## en-US/en-CA
[!INCLUDE [en-US](./includes/phonetic-sets/text-to-speech/en-us.md)]

## es-ES
[!INCLUDE [es-ES](./includes/phonetic-sets/text-to-speech/es-es.md)]

## es-MX
[!INCLUDE [es-MX](./includes/phonetic-sets/text-to-speech/es-mx.md)]

## fi-FI
[!INCLUDE [fi-FI](./includes/phonetic-sets/text-to-speech/fi-Fi.md)]

## fr-FR/fr-CA/fr-CH
[!INCLUDE [fr-FR](./includes/phonetic-sets/text-to-speech/fr-fr.md)]

## he-IL
[!INCLUDE [he-IL](./includes/phonetic-sets/text-to-speech/he-il.md)]

## hr-HR
[!INCLUDE [hr-HR](./includes/phonetic-sets/text-to-speech/hr-hr.md)]

## hu-HU
[!INCLUDE [hu-HU](./includes/phonetic-sets/text-to-speech/hu-hu.md)]

## id-ID
[!INCLUDE [id-ID](./includes/phonetic-sets/text-to-speech/id-id.md)]

## it-IT
[!INCLUDE [it-IT](./includes/phonetic-sets/text-to-speech/it-it.md)]

## ja-JP
[!INCLUDE [ja-JP](./includes/phonetic-sets/text-to-speech/ja-jp.md)]

## ko-KR
[!INCLUDE [ko-KR](./includes/phonetic-sets/text-to-speech/ko-kr.md)]

## ms-MY
[!INCLUDE [ms-MY](./includes/phonetic-sets/text-to-speech/ms-my.md)]

## nb-NO
[!INCLUDE [nb-NO](./includes/phonetic-sets/text-to-speech/nb-no.md)]

## nl-NL/nl-BE
[!INCLUDE [nl-NL](./includes/phonetic-sets/text-to-speech/nl-nl.md)]

## pl-PL
[!INCLUDE [pl-PL](./includes/phonetic-sets/text-to-speech/pl-pl.md)]

## pt-BR
[!INCLUDE [pt-BR](./includes/phonetic-sets/text-to-speech/pt-br.md)]

## pt-PT
[!INCLUDE [pt-PT](./includes/phonetic-sets/text-to-speech/pt-pt.md)]

## ro-RO
[!INCLUDE [ro-RO](./includes/phonetic-sets/text-to-speech/ro-ro.md)]

## ru-RU
[!INCLUDE [ru-RU](./includes/phonetic-sets/text-to-speech/ru-ru.md)]

## sk-SK
[!INCLUDE [sk-SK](./includes/phonetic-sets/text-to-speech/sk-sk.md)]

## sl-SI
[!INCLUDE [sl-SI](./includes/phonetic-sets/text-to-speech/sl-si.md)]

## sv-SE
[!INCLUDE [sv-SE](./includes/phonetic-sets/text-to-speech/sv-se.md)]

## th-TH
[!INCLUDE [th-TH](./includes/phonetic-sets/text-to-speech/th-th.md)]

## tr-TR
[!INCLUDE [tr-TR](./includes/phonetic-sets/text-to-speech/tr-tr.md)]

## vi-VN
[!INCLUDE [vi-VN](./includes/phonetic-sets/text-to-speech/vi-vn.md)]

## zh-CN
[!INCLUDE [zh-CN](./includes/phonetic-sets/text-to-speech/zh-cn.md)]

## zh-HK
[!INCLUDE [zh-HK](./includes/phonetic-sets/text-to-speech/zh-hk.md)]

## zh-TW
[!INCLUDE [zh-TW](./includes/phonetic-sets/text-to-speech/zh-tw.md)]


***

