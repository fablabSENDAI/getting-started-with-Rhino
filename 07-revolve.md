---
layout: default
title: 回転体
nav_order: 7
---

# 回転体(Revolve)

ろくろのように、ある軸を中心に線や面を回すことでできる回転体の作成方法

まず、Front画面に移り、
**Polyline**または**Curve**で、
Z軸線上から始まり、Z軸線上で終わる線を描く。

![](スクリーンショット 2016-05-12 11.41.49.png)
(線自身が交差またはループを作らないようにする。)

次に、<img src="./images/スクリーンショット 2016-05-12 11.33.37.png" alt="hi" class="inline"/> > <img src="./images/スクリーンショット 2016-05-12 11.42.19.png" alt="hi" class="inline"/>(**Revolve**)を選択。

<img src="./images/スクリーンショット 2016-05-12 11.42.33.png" alt="hi" class="inline"/>

"回転させるカーブを選択"
と、言われるので先ほど描いた線を選択しEnter

<img src="./images/スクリーンショット 2016-05-12 11.42.46.png" alt="hi" class="inline"/>

"回転軸の始点を選択"
と表示されたら...

<img src="./images/スクリーンショット 2016-05-12 11.43.00.png" alt="hi" class="inline"/>

選択したカーブの片端を選択し

<img src="./images/スクリーンショット 2016-05-12 11.43.06.png" alt="hi" class="inline"/>

”回転軸の終点を選択”
というメッセージに変わるはずなので、

<img src="./images/スクリーンショット 2016-05-12 11.43.24.png" alt="hi" class="inline"/>

選択した線のもう片方の端を選択

<img src="./images/スクリーンショット 2016-05-12 11.43.39.png" alt="hi" class="inline"/>

"回転の開始角度"

というメッセージが表示されたら"Full Circle(360度)"というボタンをクリック

<img src="./images/スクリーンショット 2016-05-12 11.43.49.png" alt="hi" class="inline"/>


すると、選択した線を回転軸を中心に360°クルッと回して回転体が作成される。

これと、ExtrudeSrfそしてBooleanコマンドを組み合わせることでより多彩なモデリングが可能になる
