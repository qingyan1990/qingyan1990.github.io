---
layout: post
title: "Vue Directives"
date: 2017-03-24 14:52:46 +0800
comments: false
categories: Vue
---

`v-text`

``` html
<span v-text="msg"></span>
<!-- 和下面的一样 -->
<span>{{msg}}</span>
```

`v-html` 更新元素的innerHTML

`v-show` 根据表达式之真假值，切换元素的 display CSS 属性。

`v-if` 根据表达式的值的真假条件渲染元素。在切换时元素及它的数据绑定 / 组件被销毁并重建。如果元素是`<template>`，将提出它的内容作为条件块。

`v-else` `v-else-if`

`v-for`

`v-on`

`v-bind`

`v-model`

`v-pre` 跳过这个元素和它的子元素的编译过程。可以用来显示原始 Mustache 标签。跳过大量没有指令的节点会加快编译。

`v-cloak`

`v-once`

