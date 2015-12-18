# nico

[![building status](https://secure.travis-ci.org/lepture/nico.png?branch=master)](https://travis-ci.org/lepture/nico)

Nico is a front-end friendly static site generator, best for web developers like you and me.

-----------


## Installation

It's currently under development, and may be not stable enough, taks your own risk.

Install with npm is easy:

```
$ tnpm install @ali/nico-js -g
```

Get more information or help on the [project homepage](http://lab.lepture.com/nico/).


## Contributing

Please do contributing, but before this, have a look at [Contributing Guide](https://github.com/lepture/nico/blob/master/CONTRIBUTING.md).


## 与nico区别

增加对js代码的执行部分
````js
console.log(1);
````

以上代码，不仅能以文档展示，也能够执行这段js，可以做demo的同时执行代码

## 与nico-jsx的区别
nico-jsx是针对react jsx执行的jsx模板编译方案
因为要依赖babel-preset-es2015,而这个文件相当的大，执行加载需要大约10秒
对于执行普通js没必要加载这个文件，所以去掉

## 修改原因
在nico-jsx上面为了执行效率的原因，做了部分去除
