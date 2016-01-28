# Hearn - Literary notation markup language

Hearn is a markup language; for literary notations.

>  "He! Was it anything like THIS that she showed you?" cried the soba-man, stroking his own face—which therewith became like unto an Egg... And, simultaneously, the light went out.
> --- "MUJINA" by Lafcadio Hearn from [KWAIDAN: Stories and Studies of Strange Things](http://www.gutenberg.org/files/1210/1210-h/1210-h.htm)


## Syntax

### Paragraph

```
第一段落。
段落は複数の文章から成る。
各段落は空行で区切って分けられる。
ひとつの段落の中では、明示的に指定しない限り改行は意味を持たない。すなわち、このように書ける。

第二段落。
段落の頭に字下げの全角スペースは必要ない。
役物（「！」「？」など）の後ろの全角スペースも同じく入力する必要はないが、入力してもよい。
慣習的に、あるいは癖で、役物の後ろに全角スペースを入力してしまうのを許容するためである。

第三段落。
改行には二つの意味がある。
レイアウト上の改行（段落の区切りや、段落の塊を分けるもの、見出しのスペーシングなど）と、内容としての改行（数行の改行を挟むことで間を取る、など）がある。
Hearnでは両者を区別し、内容としての改行を扱う。
Newlineの項を見よ。
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

#### Itemize

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
