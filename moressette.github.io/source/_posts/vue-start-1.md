---
title: Vue-起步
categories: Vue.js
tags: 
    - Vue.js
---
##### 编写一个.vue文件时包含三部分
* &lt;template&gt;
* &lt;script&gt;
* &lt;style&gt;

##### 在自建的.vue文件的template中
div的class，需要在script中export导出，如下：
![](http://p1.bqimg.com/567571/8ba26010aa87ae90.png)

##### 在App.vue内
首先在\<script\>标签中通过 ` import Hello from './conponents/Hello' `引入，然后在` export default `的`components`中注册(大小写不敏感)

![](http://i1.piimg.com/567571/909d6d8d74fad2d9.png)

完成以上操作后，便可以在App.vue的\<template\>标签中使用该` <hello> `标签了


![](http://p1.bpimg.com/567571/f790c2f9a5f65f68.png) 

接下来由于在main.js的components中注册了App(即App.vue)，所以在index.html中就可以使用`<app>`标签了
