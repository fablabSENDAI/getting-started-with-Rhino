---
layout: default
title: デザインルール
parent: フラットパックデザイン
nav_order: 3
---

# CNC発注のためのデザインルール

* 使用できる材料

  * 18mm厚ラワン合板 1220mm x 810mm、１枚

  * 18mm厚ラワン合板 600mm x 600mm、１枚

* ビット径 1/4inch = 6.35mm

* 最低限残してほしいパーツの太さ
  * ラワン合板(18mm厚) 18mm
  * シナ合板(18mm厚) 18mm
  * 杉板(24mm厚) 24mm

  <img src="../images/minimum_thickness.png" alt="hi" class="inline"/>


* Make2Dしたら線がバラバラになるので、Joinしておく。

* 座面については、繊維方向がX軸方向に(接着痕が横縞になるように)材がセットされる。

* **ドッグボーン**は6.4mm径でつけておく

* パーツ -材端間距離：20mm

* パーツ -パーツ間距離：20mm

* **オフセット** : 片側0.4mm、両側0.8mm (基本的には穴の方にオフセットかける)

* in-cut (赤：R255 G0 B0)、out-cut (青：R0 G0 B255)、material (黒：R0 G0 B0)で**レイヤー分け**　→ **DXFでExport**

* 基本的に半角英数字で名前を付ける("学籍番号_氏名_素材.dxf"、例：12345678_pecker_plywood.dxf)
  * 合板の場合は、12345678_pecker_plywood.dxf
  * 杉板の場合は、12345678_pecker_cedar.dxf


* 提出フォルダにデータをアップする。

# DXFデータ提出締め切り：2025.06.17(火) 12:00