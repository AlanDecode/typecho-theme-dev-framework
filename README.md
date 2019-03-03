# 一个 Typecho 主题开发起步框架

我在为 Typecho 写主题时发现了几个问题：

- 某些代码可以复用，没必要每次都写一遍
- Typecho 文档不充分，某些方法每次用到都要现查
- 某些方法 Typecho 的接口太复杂或者压根就没有实现
- 某些方法在不同的 Typecho 版本行为不一致
- 我的主题都有比较相似的目录结构

因此我准备把自己的最佳实践打包一下，美其名曰一个「框架」，其实只是为了减少一些无谓的工作量。

~~是不是闻到了 JQuery 的味道~~

使用时，直接下载本框架，并在其中删改、添加代码。Utils.php 与 Contents.php 中提供了一些常用的代码，可以看看。

**非常欢迎各种 pull request**

目录结构：

```
index.php
post.php
page.php
archive.php
404.php
functions.php
includes
    |-- head.php
    |-- header.php
    |-- footer.php
libs
    |-- Utils.php
    |-- Contents.php
assets
    |-- main.css
    |-- main.js
```


## License

MIT © [AlanDecode](https://github.com/AlanDecode)