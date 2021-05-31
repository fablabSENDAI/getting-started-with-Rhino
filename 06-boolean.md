---
layout: default
title: 物体の足し算、引き算
nav_order: 6
---

# 物体の足し算•引き算

作成したオブジェクト同士の足しあわせたり•差し引いたりして、より複雑な形状を作り出せる。

オブジェクトをどこか一部分が重なるように、配置する。


<img src="./images/スクリーンショット 2016-05-12 11.51.38.png" alt="hi" class="inline"/>

便宜上、上のオブジェクトをA、下のオブジェクトをBとする。

### 足し算

まずは、A+Bをやってみる。

<img src="./images/スクリーンショット 2016-05-12 11.29.57.png" alt="hi" class="inline"/>><img src="./images/スクリーンショット 2016-05-12 11.29.57.png" alt="hi" class="inline"/>(**BooleanUnion**)を選択

A，B両者を選択してEnter.


<img src="./images/スクリーンショット 2016-05-12 11.40.18.png" alt="hi" class="inline"/>

A,Bがくっついて、１つのオブジェクトになる。

### 引き算

次に、A-B。

<img src="./images/スクリーンショット 2016-05-12 11.29.57.png" alt="hi" class="inline"/>><img src="./images/スクリーンショット 2016-05-12 11.30.12.png" alt="hi" class="inline"/>(**BooleanDifference**)を選択

まず、引かれる方を聞かれるので、Aを選択しEnter

そのあと、引く方を聞かれるので、Bを選択しEnter


<img src="./images/スクリーンショット 2016-05-12 11.40.45.png" alt="hi" class="inline"/>

このように、AからBが重なっていた部分が引かれた形が残る。

(ちなみに、コマンド中で”元のオブジェクトを削除する”をむこうにすれば、引く方のオブジェクトも残してくれる。)
