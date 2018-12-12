## 📦 Minipack

> 一个用JavaScript写的现代模块打包器的简单例子

### Introduction

作为前端开发者，我们花了大量时间与这些工具打交道如 [Webpack](https://github.com/webpack/webpack), [Browserify](https://github.com/browserify/browserify), 和 [Parcel](https://github.com/parcel-bundler/parcel).

理解这些工具是如何工作的能够帮助我们更好的写代码，通过理解我们的代码如何被转换成bundle以及bundle长啥样也能帮助我们更好的debug.

这个项的目的旨在解释大部分打包器内部是怎么工作的。包含了一个简化版但也足够精致的打包器的简短实现。除了代码还有注释解释了如何做到。

### 酷，从哪开始呢?

转到源码: [src/minipack.js](src/minipack.js).

### 尝试运行

安装依赖

```sh
$ npm install
```

然后运行脚本

```sh
$ node src/minipack.js
```

### 其他参考链接

- [AST Explorer](https://astexplorer.net)
- [Babel REPL](https://babeljs.io/repl)
- [Babylon](https://github.com/babel/babel/tree/master/packages/babel-parser)
- [Babel Plugin Handbook](https://github.com/thejameskyle/babel-handbook/blob/master/translations/en/plugin-handbook.md)
- [Webpack: Modules](https://webpack.js.org/concepts/modules)

