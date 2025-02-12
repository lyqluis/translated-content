---
title: AudioTrack.kind
slug: Web/API/AudioTrack/kind
page-type: web-api-instance-property
tags:
  - API
  - Audio
  - Audio Track
  - AudioTrack
  - HTML DOM
  - Media
  - Property
  - Read-only
  - Reference
  - id
  - track
browser-compat: api.AudioTrack.kind
translation_of: Web/API/AudioTrack/kind
---
{{APIRef("HTML DOM")}}

**`kind`** プロパティは、文字列で **{{domxref("AudioTrack")}}** に含まれる音声のカテゴリーを示します。

`kind` を使用すると、特定のトラックを有効または無効にするシナリオを決定できます。 音声トラックで利用可能な種類の一覧については、[音声トラックの種別文字列](#音声トラックの種別文字列)を参照してください。

## 値

文字列で、メディアが表すコンテンツの種類を指定します。この文字列は、以下の[音声トラックの種別文字列](#音声トラックの種別文字列)にあるもののうちの 1 つです。

## 音声トラックの種別文字列

音声トラックに使用できる種別は次のとおりです。

- `"alternative"`
  - : 別テイクの音声や、サウンドトラックのセリフなしバージョンなど、メイントラックの代わりとなる可能性があるものです。
- `"descriptions"`
  - : 動画トラックに描かれているアクションの音声による説明を提供する音声トラック。
- `"main"`
  - : 主音声トラック。
- `"main-desc"`
  - : 主音声トラックに音声の説明が混在していもの。
- `"translation"`
  - : 主音声トラックの翻訳版。
- `"commentary"`
  - : 解説を含む音声トラック。 これは、例えば、映画で監督の解説トラックを含めるために使用される場合があります。
- `""` （空の文字列）
  - : トラックに明確な種別がない、またはトラックのメタデータによって提供された種別が{{Glossary("user agent","ユーザーエージェント")}}に認識されていないもの。

## 仕様書

{{Specifications}}

## ブラウザーの互換性

{{Compat}}
