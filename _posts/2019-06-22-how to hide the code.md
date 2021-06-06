---
layout: page
title: 想要藏点东西？简单代码隐藏html页面内容。
excerpt_separator: "<!--more-->"
categories:
     - 网站设计
---

在web页面构建的过程中，如果你不想一段代码现实中页面上，但又希望保留这段代码，以方便未来的某时某日重新启用，这里有两种简单的方法能够实现。

## [display属性](http://www.w3school.com.cn/cssref/pr_class_display.asp)

<!--more-->

### 定义
display属性规定元素应该生成的框的类型。 说明:这个属性用于定义建立布局时元素生成的显示框类型。对于 HTML 等文档类型，如果使用 display 不谨慎会很危险，因为可能违反 HTML 中已经定义的显示层次结构。对于 XML，由于 XML 没有内置的这种层次结构，所有 display 是绝对必要的。 

### 运用
利用display:none 我们可以隐藏掉我们不希望显示的内容。
![display效果演示图](https://gitee.com/QiuYuAn0303/Kamen_Rider/raw/gh-pages(try)/assets/images/display_yanshi.PNG)


## <!----....--->标签

### 定义
被注释的代码不会被显示在页面当中，当注释被删除时，原有的代码又能从新发挥作用，所以可以用注释隐藏浏览器不支持的代码。

### 运用

![注释效果演示图](https://gitee.com/QiuYuAn0303/Kamen_Rider/raw/gh-pages(try)/assets/images/zhushiyanshi.PNG)
