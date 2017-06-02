---
layout: post
title:  "对象属性"
tags: [对象,属性]
excerpt: "
对象的属性之间用逗号分隔，最后一个属性后面可加可不加"
author: nikas
comments: true
date:   2016-07-05 15:00:00
---


对象的属性之间用逗号分隔，最后一个属性后面可以加逗号（trailing comma），也可以不加。

''var o = {
  p: 123,
  m: function () { ... },
}

上面的代码中m属性后面的那个逗号，有或没有都不算错。但是，ECMAScript 3不允许添加逗号，所以如果要兼容老式浏览器（比如IE 8），那就不能加这个逗号。