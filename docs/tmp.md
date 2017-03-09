MarkDown简单示例
==

#请对比查看源文件与显示效果

## 1. 标题,井号(#)

#  1个#号就类似于 h1,即标题1
## 2个#号就类似于 h2,即标题2
...
#########以此类推,直到 h9

	#  1个#号就类似于 h1,即标题1
	## 2个#号就类似于 h2,即标题2
	...
	#########以此类推,直到 h9

## 2.超链接

使用方括号,小括号的方式: [CNCounter](http://www.baidu.com)

	[CNCounter](http://www.baidu.com)

还可以采用嵌入html:


<a name="#relative_post">点击跳到嵌入的HTML锚点</a>

<a href="http://blog.csdn.net/renfufei">铁锚博客</a>


	<a name="#relative_post">点击跳到嵌入的HTML锚点</a>
	
	<a href="http://blog.csdn.net/renfufei">铁锚博客</a>
	
	##<a name="relative_post">相关文章</a>

## 3. 图片

类似于在超链接前面加上一个英文的感叹号:

![图片描述,可以为空,类似于 alt](http://avatar.csdn.net/4/9/C/1_renfufei.jpg)

	![图片描述,可以为空,类似于 alt](http://avatar.csdn.net/4/9/C/1_renfufei.jpg)

当然,图片也可以是相对路径啦, `./`, `../` 之类的都允许,和 html的相对路径引用是一样的:

![](11_Git_CMD.png)

	![](11_Git_CMD.png)
	![](./11_Git_CMD.png)


## 4. 字体格式

**黑体**
*斜体*
***黑体斜体***

	**黑体**
	*斜体*
	***黑体斜体***


## 5. 源代码引用

源代码引用,只需要段前和段后有空行,并且源码的每一行前面都有制表符(\t),或者4个空格的缩进就会被解析为源码原样引用显示. 类似于  html 的 `code`, `pre` 标签.

另一种行内源码的表示方式是使用键盘上方数字键那一行最左边,数字1左边的 ` 符号括起来即可,注意不是单引号.

	多行级别的源代码
	多行级别的源代码
	多行级别的源代码
	多行级别的源代码
	多行级别的源代码

还可以是 `行内级别的源码`.

## 6. 数字列表

1. 数字列表
1. 数字列表
1. 数字列表
1. 数字列表
1. 数字列表

####

	数字. 文字
	数字.(空格)文字


## 7. 无序列表

- 无序列表
- 无序列表
- 无序列表
- 无序列表
- 无序列表
- 无序列表

可以是减号


	- 无序列表
	- 无序列表
	- 无序列表
	- 无序列表
	- 无序列表
	- 无序列表

也可以是 * 号

* 无序列表
* 无序列表
* 无序列表
* 无序列表
* 无序列表
* 无序列表

###

	 * 无序列表
	 * 无序列表
	 * 无序列表
	 * 无序列表
	 * 无序列表
	 * 无序列表

##<a name="relative_post">相关文章</a>

1. [目录](GitHelp.md)
1. [安装及配置Git](01_GitInstall.md)
1. [安装及配置TortoiseGit](02_TortoiseGit.md)
1. [基本使用方法](03_Usage.md)
1. [MarkDown示例](04_MarkDownDemo.md)
1. [解决 TortoiseGit 诡异的 Bad file number 问题](05_BadFileNumber.md)
1. [加入QQ群GitHub家园: 225932282](http://jq.qq.com/?_wv=1027&k=WHbwkD)



日期: 2014-11-27

作者: [铁锚: http://blog.csdn.net/renfufei](http://blog.csdn.net/renfufei)




---
__Advertisement :)__

- __[pica](https://nodeca.github.io/pica/demo/)__ - high quality and fast image
  resize in browser.
- __[babelfish](https://github.com/nodeca/babelfish/)__ - developer friendly
  i18n with plurals support and easy syntax.

You will like those projects!

---

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

> Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
>
> Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\<ins>](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\<mark>](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::
