---
layout: post
title: Es6中Map对象和Set对象的介绍及应用
date: 2017-01-03 
tag: iOS
---
今天说一说ES6的Set对象和Map对象。以及这两个对象的应用。目前主流浏览器（chrome32、IE11、Safari7.1以及 Firefox 13以上）都对这2个对象做了基本的支持。因此，和css3一样，es6慢慢走进了前端开发的舞台，未来，我们可以不用再利用Babel对ES6语法进行编译就可以直接支持es6语法了。
### Map 对象

　　Map 对象保存键值对。任何值(对象或者原始值) 都可以作为一个键或一个值。


>* var myMap = new Map();
>*myMap.set("bar", "baz");
>*myMap.set(1, "foo");

>*myMap.size;       // 2
>*myMap.has("bar"); // true

>*myMap.clear();

>*myMap.size;       // 0
>*myMap.has("bar")  // false






