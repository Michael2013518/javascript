# Javascript

## Type
1. Undefined
2. Null
3. Boolean
4. String
5. Number
6. Symbol
7. Object
## Void 0
1. 通过采用void 0取undefined比采用字面上的undefined更靠谱更安全，应该优先采用void 0这种方式。
2. 填充<a>的href确保点击时不会产生页面跳转; 填充<image>的src，确保不会向服务器发出垃圾请求。

[[谈谈Javascript中的void操作符](https://segmentfault.com/a/1190000000474941)]<https://segmentfault.com/a/1190000000474941>

## Undefined、Null

Undefined类型表示未定义，它的类型只有一个值，就是undefined。任何变量在赋值前是Undefined类型，值为undefined。JavaScript的代码undefined是一个变量，而并非是一个关键字。

null表示定义了但是为空，Null类型也只有一个值，就是null，它的语义表示空值，与undefined不同，null是JavaScript关键字，所以在任何代码中，你都可以放心用null关键字来获取 null值

**比较两个浮点数是否相等：console.log(Math.abs(0.1+0.2-0.3)<=Number.EPSILON)**

ES6 在Number对象上面，新增一个极小的常量Number.EPSILON。根据规格，它表示 1 与大于 1 的最小浮点数之间的差。Number.EPSILON实际上是 JavaScript 能够表示的最小精度。误差如果小于这个值，就可以认为已经没有意义了，即不存在误差了，即两个值相等。

