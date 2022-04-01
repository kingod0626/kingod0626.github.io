---
title: 【學習日誌】javascript基礎介紹
date: 2022-4-1
tags: 
    - 學習 
    - 前端文章
---


## javascript宣告變數的三種方法

``` bash
var //現較少用到 不常使用 

let //可於後續程式改變其值

const //不可於後續程式改變其值

```
## javascript內容字串穿插不同型別的2種方法

``` bash
let myName ="Tom";
let myAge = 18;
let content = "您好我是"+myName+"，我今年"+myAge+"歲" //原版用法
let content = `您好我是${myName}，我今年${myAge}歲` //ES6新增的用法

```
## 一些特殊用法

``` bash
myEmail=myEmail.trim() //除去空白字元
length=myEmail.length //計算字元長度
typeof name //查資料型別
```