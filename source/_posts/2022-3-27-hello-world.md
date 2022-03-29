---
title: 【 學習日誌】如何使用 Hexo + GitHub Pages 架設個人網誌
date: 2022-3-27
tags: 
    - 學習 
    - 前端文章
---
本篇主要介紹如何使用 Hexo 並搭配 GitHub 來快速架設網誌。從介紹什麼是 Hexo 框架，該如何安裝、建立環境，接著介紹一些常用指令，以及如何部署到 GitHub 上。

## Hexo介紹

Hexo 其實就是一個基於 Node.js 開發的網誌框架，具有下列幾項特點：
--編譯速度非常快
--能夠支援 Markdown 語法解析文章，並透過主題渲染靜態檔案
--具有豐富的外掛套件
--支援一鍵部署

### 新增文章

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### 靜態網站產生器

``` bash
hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
