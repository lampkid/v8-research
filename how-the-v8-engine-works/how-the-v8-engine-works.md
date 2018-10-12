---
layout: post
title: "How the V8 engine works?"
description: "How it works and how to write performant JavaScript code for the engine"
category: javascript
---

### hidden class
#### 什么时候会创建hidden class？
- 属性变更的时候
- 多次调用函数时，每次调用传入的参数类型不一致

### boxing operation
当一个数大于31位所能表示的时候，v8会将该数转为double并用一个对象存储

### Array
- fast elements: 线性的，连续的。
- dictionary elements：非线性的，hash table，比如删除数组中的某一个key

### Compile
- Full compiler
- optimizing compiler

> Inline Caches

> De-optimiztion

### Resources

- Google I/O 2012 "Breaking the JavaScript Speed Limit with V8" with Daniel Clifford, tech lead and manager of the V8 team:
<a href="https://www.youtube.com/watch?v=UJPdhx5zTaw" title="video" target="_blank">video</a> and
<a href="http://v8-io12.appspot.com" title="slides" target="_blank">slides</a>.
- V8: an open source JavaScript engine:
<a href="http://www.youtube.com/watch?v=hWhMKalEicY" title="video" target="_blank">video</a> of Lars Bak, V8 core engineer.
- Nikkei Electronics Asia blog post: <a href="http://techon.nikkeibp.co.jp/article/HONSHI/20090106/163615/" title="go to techon.nikkeibp.co.jp" target="_blank">Why Is the New Google V8 Engine So Fast?</a>


## 来源
https://github.com/ThibaultLaurens/thibaultlaurens.github.io/blob/master/_posts/2013-04-29-how-the-v8-engine-works.md

