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
# 第一部

## 第一章

### 第一節

#### 第一項

以下、本文がつづく。
```

### Lists

#### Item list

```
恵子は、母から渡されたメモを見た。そこにはこう書かれていた。

* キャベツ
* ニンジン
* 豚バラ肉（アメリカ産）
* 食器用洗剤
```

#### Enumrate

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
