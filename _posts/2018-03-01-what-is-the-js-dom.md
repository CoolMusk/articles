---
ID: 172
post_title: 什么是JavaScript DOM
post_name: what-is-the-js-dom
post_date: 2018-03-01 20:08:03
layout: post
link: >
  http://www.233lab.com/what-is-the-js-dom/
published: true
tags:
  - JavaScript

categories:
  - JavaScript
  - 淘金计划
---
> JavaScript淘金计划 · 好书精读栏目 第1篇
> 
> 精读《JavaScript DOM核心编程》
                           
今天来谈谈一个JavaScript中常见的概念：DOM( Document Object Model，文档对象模型)。

DOM作为组成JavaScript的三大“巨头”之一，与ECMAScript、BOM并列，它提供的是访问和操作网页的方法和接口。

它就像一个扫描仪，能够把整个HTML或XML页面映射成一个多层节点结构，HTML页面中每个组成部分都是某种类型的节点，节点中又包含着不同类型的数据，那么可以得到一个表示整个HTML页面的树形图，开发人员借助DOM提供的API，就可以轻松自在地对任何节点的数据和类型进行改造。

比方说这样：
```JavaScript
// 举一个例子
<html>
    <head>
        <title> One Page </title>
    </head>
    <body>
        <p>  Hello World! </p>
    </body>
</html>
```
可以清楚的看出，`<html>` ` </html>`中有两个节点`head` `body`，`head`下又有`title`，而`body`下有`p`。

DOM
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE3MzUyODM3NDJdfQ==
-->