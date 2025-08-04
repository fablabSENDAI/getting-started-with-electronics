---
layout: default
title: 抵抗
parent: パーツ
nav_order: 3
---

# 抵抗
電気の流れを抑えて、他のパーツにとってちょうど良い電流・電圧量に変えるための電子パーツ。<br>
これ単体で何か動作するってことはないけど、縁の下の力持ち的な存在で、ほぼ全ての電子回路に使われているであろう部品。<br>


|![回路記号](../images/component/resistor/resistor_icon.jpg)|![Tinkercad](../images/component/resistor/resistor_tinkercad.jpg)|![実物](../images/component/resistor/resistor_pinout.jpg)|
|:--|:--|:--|
|回路記号|Tinkercad|パーツ|

## 各足の解説（極性なし）
<span style="color:#36b1bf">**1**</span><br>
プラスマイナス特に指定なし

<span style="color:#f2484b">**2**</span><br>
プラスマイナス特に指定なし

※極性なし、なのでひっくり返して接続しても問題なし


## 補足説明

### カラーコード
抵抗には、カラーコードと呼ばれる４本の線がプリントされており、この線の色の組み合わせで抵抗値を調べることが出来る。

- [抵抗器のカラーコード・表示の読み方、覚え方](https://www.akaneohm.com/column/marking/)
- [resisto.rs](http://resisto.rs/)

### 足の長さ調整
抵抗は、足がまっすぐのままだと使いずらいので、下の写真のように90度にそれぞれ曲げて使う。<br>
![抵抗の足を曲げたとこ](../images/component/resistor/legtirm01.jpeg)

このままでも十分使えるが、ブレッドボードに挿すと結構飛び出た感じになる。<br>
なによりむき出しの足が他の線に接触すると思わぬところで回路がショートしてしまう。<br>
![背の高い抵抗の図](../images/component/resistor/legtrim02.jpeg)

そこで、ニッパーで足を短くする、大体1cmくらいの長さにできると良い。<br>
切りすぎるとブレッドボードに刺さりずらくなるので注意！<br>
![ニッパーで抵抗の足をトリミング](../images/component/resistor/legtrim03.jpeg)

足の長さを調整した抵抗はおさまりが良く、すっきりした回路になる。<br>
![ピタッと刺さった抵抗](../images/component/resistor/legtrim04.jpeg)

切り取った抵抗の足は捨てずにとっておこう。ユニバーサル基板へのはんだ付けの際に有用だ。