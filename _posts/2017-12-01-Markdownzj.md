---
layout: article
title:  "Markdown语法总结"
date:   2017-12-31 22:07:50 +0800
categories: tabnote
image:
  teaser: markdown.png
  feature: markdown.png
---

markdown的基本符号*-+>。#的多少能够调整文字大小。引用为>,段落用回车标记，使用三个以上---进行分隔，*-+都可创建无序列表，数字+点+空格创建有序列表，链接：[链接名称]（网址），图片！[图片名称]（图片地址），在代码前后使用```符号,斜体在字前后加*，加粗在字前后加**，加粗并斜体在字前后加***，表格使用- |符号把内容分割合适的表格样式。

## Markdown语法
### Markdown是什么？
同样是标记语言，但它相比HTML更加简单！一是体现在标记符的数量上，二是体现在标记符的书写上。HTML标记符号非常多，并且需要标记内容的开始和结束位置，而markdown只有四个基本的标记符号，只要在开始位置标记即可。
### Markdown解决什么问题？
当我们需要让文档看起来层次分明，但又不依赖于word这样的编辑工具来书写、排版和读取时，markdown的易写易读优势就非常突出了。并且在我使用一段时间以后，发现使用markdown非常有助于帮助作者在写作时整理自己的逻辑思路和段落层次。
### 怎样读取和书写Markdown？
同HTML一样，你可以使用任何一款纯文本编辑工具来编辑和读取包含markdown格式的文本，但只有在一些特别的工具（如有道云笔记）或网站（如简书）下，才能呈现出渲染后的格式。同时markdown也可以使用HTML来添加格式和排版，这意味着，你即可以使用标准的markdown语法，也可以在其中嵌入HTML标记，但也只能对应其中的一小部分。
### Markdown语法
##### 基本符号*-+>
基本上所有的markdown标记都是基于这四个符号及其组合，需要注意的是，如果以基本符号开头的标记，注意基本符号后分割内容的空格。
## 标题
# 一级标题 
#一级标题
## 二级标题 
##二级标题
### 三级标题      
###三级标题
#### 四级标题
####四级标题
##### 五级标题
#####五级标题
###### 六级标题
######六级标题


## 引用
- 引用的方式：> 引用内容
## 段落
- 段落以自然 回车 作为标记。
## 分隔符
- 连续输入三个以上的---添加横线分隔符。
## 列表
- 使用*-+中的任何一个符号加空格就可以创建无序列表

- 使用数字+点+空格创建有序列表

## 链接
- [链接名称]（网址）
- 直接用尖括号包含网址的方式<网址>。
## 图片
- 像构造链接一样，只需要在前面加！
！[图片名称]（图片地址）
## 代码段


```
  print ("这是一个代码段")；
```
## 字体样式
- *倾斜* 在字体前后加上*
- **加粗**在字体前后加上**
- ***倾斜并加粗***在字体前后加上***
## 表格
- 使用- |符号把内容分割为你认为合适的表格样式就好。
- 使用:符号标识对齐。

      表头1|表头2|表头3

      :----|:-----:|-----:

       左对齐|居中对齐|右对齐

## 保存
- 最后将markdown编写的文档存为 .md 格式，就可以用对应的工具查看效果和编辑了。