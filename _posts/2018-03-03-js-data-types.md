---
ID: 229
post_title: JavaScript的数据类型
post_name: js-data-types
post_date: 2018-03-03 10:53:26
layout: post
link: http://www.233lab.com/js-data-types/
published: true
tags:
  - JavaScript
categories:
  - JavaScript
  - 淘金计划
---
ECMAScript中有6种简单数据类型：

- Undefined
- Null
- Boolean
- Number
- String
-  Symbol (更新： ECMAScript 6 新定义类型)

1种复杂数据类型：

- Object

ECMAScript不支持任何创建自定义类型的机制，而所有值最终都将是上述6种数据类型之一。

#### 数值转换
有3个函数可以把非数值转换为数值：`Number()`、`parseInt()`、`parseFloat()`。第一个函数，即转型函数`Number()`可以用于任何数据类型，而另两种函数则专门用于把字符串转换成数值。
这三个函数对于同样的输入会有返回不同的结果。





#### 参考资料
- https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Data_structures      ，by MDN
- JavaScript 高级程序设计（第三版）, by Nicholas C.Zakas