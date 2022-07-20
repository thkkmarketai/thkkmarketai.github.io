---
layout: default
title: thkk market AI
description: "マーケットデータ / Market Data"
---

## **マーケットデータ / Market Data**

- リポジトリ / Repository
 - [Market Data](https://thkkmarketai.github.io/marketdata)

　具体的な分析を始めるに当たり、まずはマーケットデータの提供元について把握しておきましょう。付き合いのある取引所や証券会社が必ずしも自分の目的に合うデータを提供しているとは限らず、その場合は広い世界を彷徨うしかありません。また、有料データや新規口座開設などの条件付きデータの場合、その敷居の高さがボトルネックとなることもあります。

　このプロジェクトでは、特段の断りがない限り無料で取得できるデータを使用します。分析の入口段階で余計な二の足を踏まなくて済むことや、有用な無料データを探したいという著者の意向も理由の一つです。事前に幾つか良い候補を決めておくと、後々躓くことも少なくなります。

　質という観点では「無料データ << 有料（or 条件付き）データ」である可能性を否定できませんが、その点はひとまず甘んじて受け入れようと思います。ただ、「ゴミを入れると、ゴミしか出てこない」という事態に陥らないよう、この工程では使用するデータの選択方法も合わせて検討していきます。

&emsp;

　You should find some market data sources before you start analyzing. You might already have a few trading accounts on your favorite exchanges or securities. But if they don't provide the data that you exactly want, you have to go around the world. You may find it difficult to reach out high-quality market data without any conditions.

　In this project, I will use the data for free unless otherwise noted. I want to avoid some troubles at my first step of market analysis and I also hope that there might be some excellent data for free in the world. If you choose some alternatives in advance, you will have fewer chances to fall.

　I agree and accept at this time that the data for free may have more problems than not for free. But I will consider how to select carefully the data for use in this project to avoid "Garbage in, garbage out".

&emsp;

　扱う商品カテゴリーは、データが揃いやすいstock、FX、cryptoの3種類を想定していますが、将来的にはratesも加えたいと考えています。上場・非上場に関わらず、プロバイダー毎に同一商品のデータ値が異なることは容易に想像できるため、比較を経た上で判断するプロセスは必須となります。

 <!-- 以下にcodeの簡単な説明と図やテーブルを表示する -->
 <!-- まず形を整えた上で、基本データ（平均、中央値、分散、偏差）を計算し、各業者毎に比較できるようにしたいと思います。リポジトリにはpd.DataFrameを使って分析できるcodeを掲載しています。 -->

　なお、この工程では各プロバイダーのAPIに関するcode例などは掲載していません。APIの仕様や詳細については、各プロバイダーのDocsをご参照ください。

&emsp;

　I think that stock, FX, and crypto data are easy to collect and handle. Rates would be the next one to add in the future. These data must be compared by some processes because each provider would give a different value regardless of listed or unlisted, even if it is the same product.

　Note that there is no code examples about API for each provider. Please read the docs if you need its specification or details.

&emsp;

## **resent posts**
1. []
2. []
3. []
4. []
5. []

&emsp;

　
