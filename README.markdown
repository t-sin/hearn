# Hearn - Literary notation markup language

Hearn is a markup language for literary notations.

>  "He! Was it anything like THIS that she showed you?" cried the soba-man, stroking his own face—which therewith became like unto an Egg... And, simultaneously, the light went out.
> --- "MUJINA" by Lafcadio Hearn from [KWAIDAN: Stories and Studies of Strange Things](http://www.gutenberg.org/files/1210/1210-h/1210-h.htm)


## Syntax

### Paragraph

```
理屈も仕組みもよくわかっているとはいえ、やはりいったん死んでしまった人とまたこうして普通に話をする、というのはまことに違和感のあるものだ。

京子が鱗状自在合板の盆の上につめたい崩梅茶と切った西瓜を載せて居間に入ってきた。
足もとにマユミが仔犬みたいにまとわりついている。
おばあちゃんが帰ってきて嬉しいのだけれど、マユミにとってはおばあちゃんと仲よしだった一年前の記憶はもう相当に薄れているだろうから、ここでこの人にどんなふうに接していったらいいのかまだよくわからないでいる、という状態なのだろう。

「すいかすいか。パパすいか好きだもん」

と、マユミがおばあちゃんにおしえてあげるからね、というような、思わせぶりな口調で言った。

「おむかいの常木原さんが自治会の役員をおやめになったのはあの方のてけ踊り教室にだいぶお弟子がついたからだって言ってました。
わたしもしばらくうちはだいぶ誘われましたけどもうてけ踊りは年寄りにはきついからってまるでことわってしまいましたけれどねえ」

おばあちゃんは好物のつめたい崩梅茶をすすりながら奇妙に早口でそんなことを言った。
てけ踊りというのがどんなものなのかよくわからなかったが、わかっているような顔をして頷いた。

--- 椎名誠, 『胃袋を買いに』, 文春文庫
```

### Part / Chapter / Section / Subsection

```
# はじめに

## 思考実験とは

### ダーウィンの土手の茂み

生態学は複雑な自然を研究対象としている．
この複雑さを象徴するもっとも有名なイメージは，チャールズ・ダーウィンの生物にあふれた土手の茂みの記述であろう．
（以下省略）

### 実体アプローチ

生態系は，教科書ではどのようにまとめられているのだろう？
ほとんどの場合，全体のなかの階層として取り上げられている．
（以下省略）

### プロセスアプローチ

階層的実体アプローチに対する対案は，プロセス（過程）を重視することである．
（以下省略）

--- デイビッド・ウィルキンソン, 『生物多様な星の作り方 生態学からみた地球システム』, 東海大学出版会
```

### Lists

#### Item list



#### Enumrate

```
奥さんはそんなわけにはいかないと言い、ふたりは激しく言いあった。ところが一日か二日すると、また別の手紙が、今度はイングランドから届いた。牧羊犬協会は長い名前を認めなかったらしい。次のように変えろと言って書類を送り返してきたのだ。

. ウィシーン・ウォー
. ウィシーン・ウォン
. ウィシーン・ウェイ
. ウィシーン・ウィッシュ
. ウィシーン・ウェル
. ウィシーン・ウィド
. ウィシーン・ウェン
. ウィシーン・ウィズ

「ざまあみろだ」ボスは言った。

--- マージョリー・クォートン, 『牧羊犬シェップと困ったボス』, 創元推理文庫
```
```


### Block quotation

```
> 引用行
>
> 複数段落
> 
> * 他の記法使える
> 
>> 入れ子
>> 
```

### Inline markups

#### Newlines

#### Newline

```
改行は行末に`<<`を書くことで挿入する。<<
複数回行うことで、いくらでも改行することができる<<
<<
<<
<<
こんなふうに。
```

#### Spaces; for changing theme

```

```

### Bold

### Italic

### Bold italic

### Ruby

### Emphasis

### Inline quotation

### Footnote

### Hyperlink

```
プロジェクトページは[こちら](http://github.com/t-sin/hearn)
```

#### Image



## Installation

## Author

* grey (shinichi.tanaka45@gmail.com)

## Copyright

Copyright (c) 2015 grey (shinichi.tanaka45@gmail.com)

## License

Licensed under the MIT License.
