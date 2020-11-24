---
title: 語言簡介
type: docs
permalink: intro/
lang: zh-TW
---

## 標籤插件

Hexo 提供了大量「標籤插件」，可以在文章中快速插入 jsFiddle 程式區塊、Gist 程式區塊、YouTube Iframe 播放器、Vimeo 播放器等。具體可以參考 Hexo 文件中 [標籤插件](https://hexo.io/docs/tag-plugins) 舉例。

## 原生標籤插件

```
{% [標籤名稱] [可選參數] %}
  [可選內容]
{% end[標籤名稱] %}
```

## 主題標籤插件

提示資訊「標籤插件」有支持兩個可選參數：

- 樣式
  - none（預設樣式，即直接留空）
  - dark
  - primary
  - link
  - info
  - success
  - warning
  - danger
- 標題

> 如果你想使用 提示信息 的默认样式，但是又想要传入标题参数，此时 `note` 和 标题 之间需要传入 `none`。

**默认（none）样式样例**

{% note %}
这是一条普通的提示信息
{% endnote %}

**success 样式样例**

{% note success %}
这是一条可以用来标注推荐内容的提示信息
{% endnote %}

**warning 样式样例**

{% note warning %}
这是一条可以用来标注警告内容的提示信息
{% endnote %}

**danger 样式样例**

{% note danger %}
这是一条可以用来标注危险内容的提示信息
{% endnote %}

**dark 样式样例**

{% note dark %}
这是一条普通的提示信息
{% endnote %}

**primary 样式样例**

{% note primary %}
这是一条普通的提示信息
{% endnote %}

**link 样式样例**

{% note link %}
这是一条普通的提示信息
{% endnote %}

**info 样式样例**

{% note info %}
这是一条普通的提示信息
{% endnote %}

**带样式和标题样例**

{% note danger 危险！ %}
这是一条可以用来标注危险内容的提示信息
{% endnote %}

**使用默认样式的标题样例**

{% note ' ' For Windows 用户 %}
使用 Node.js 官方安装程序时务必确保 **Add to PATH** 处于勾选状态
{% endnote %}