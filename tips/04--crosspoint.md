---
layout: default
title: 交差点
parent: Tips
nav_order: 4
---

# 回路図の交差点

回路図の中で、線同士が交差している部分には、実は種類がある。<br>
これを読み間違えると、回路の間違った部分を **繋げてしまう / 離してしまう** 可能性があるので注意。<br>
複雑な回路ほどこれが出てくるので気を付けること。

## 接続する交差点

下図のように、交差点の部分に黒丸●がある場合、
<span style="color:#36b1bf">**1**</span>と<span style="color:#f2484b">**2**</span>の線は接続されているので、**電気的に繋げなければいけない！**

![crosspoint01](../images/tips/crosspoint/crosspoint_connect.jpg)


## スルーする交差点

下図のように、交差する部分に何もない場合は、<br>
<span style="color:#36b1bf">**1**</span>と<span style="color:#f2484b">**2**</span>の線は、互いに触れ合うことなく離れて交差しているだけなので、**接続してはならない！**

![crosspoint02](../images/tips/crosspoint/crosspoint_through.jpg)<br>

ちなみに、スルーする交差には次のような描き方もある↓

![crosspoint03](../images/tips/crosspoint/crosspoint_through2.jpg)<br>