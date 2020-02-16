Node.js安装
===

![](../imgs/node.js.png)


> Node.js 是一个基于Chrome JavaScript 运行时建立的一个平台， 用来方便地搭建快速的， 易于扩展的网络应用· Node.js 借助事件驱动， 非阻塞 I/O 模型变得轻量和高效， 非常适合 run across distributed devices 的 data-intensive 的实时应用·

Node.js的安装，请移步这里：

> [在 Windows、Mac OS X 與 Linux 中安裝 Node.js 網頁應用程式開發環境](http://www.gtwang.org/2013/12/install-node-js-in-windows-mac-os-x-linux.html)

安装完成这后，你可以在终端模式下检验一下：

```bash
$ node -v
v0.10.28
```

看到些提示，就表示你已成功安装上了`Node.js`。

Gitbook命令行速览
====

Gitbook是一个命令行工具，使用方法：

**本地预览**

```bash
$ gitbook serve ./图书名称
```

**输出一个静态网站**

```bash
$ gitbook build ./repository --output=./outputFolder
```

**查看帮助**

```bash
$ gitbook -h

  Usage: gitbook [options] [command]

  Commands:

    build [options] [source_dir] Build a gitbook from a directory
    serve [options] [source_dir] Build then serve a gitbook from a directory
    pdf [options] [source_dir] Build a gitbook as a PDF
    ebook [options] [source_dir] Build a gitbook as a eBook
    init [source_dir]      Create files and folders based on contents of SUMMARY.md

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

网络发展历史
===

![](./imgs/www.png)


> Web 使用一种名为 HTTP（HyperText Transfer Protocol，超文本传输协
  议  1 ）的协议作为规范，完成从客户端到服务器端等一系列运作流程。而协议
  是指规则的约定。可以说，Web 是建立在 HTTP 协议上通信的。


**http的诞生**

1989年http诞生、1990年第一台web服务器和web浏览器诞生、1992年第一个网站上线。
> [日本第一个主页 http://www.ibarakiken.gr.jp/www/](http://www.ibarakiken.gr.jp/www/)



**浏览器之争**

1994年网景公司发布Netscape Navigator，
1995微软发布 Internet Explorer 1.0 和 2.0，
2000 年前后，网景衰落。
但2004 年，Mozilla发布了 Firefox 浏览器，第二次大战开启
Internet Explorer发布6，7,8,9,10版本。另外，Chrome、Opera、Safari 等
浏览器也纷纷抢占市场份额。


**HTTP/1.0**

HTTP 正式作为标准被公布是在 1996 年的 5 月，版本被命名为HTTP/1.0。虽说是初期标准，但该协议标准至今
仍被广泛使用在服务器端。

**HTTP/1.0**

1997 年 1 月公布的 HTTP/1.1 是目前主流的 HTTP 协议版本。当初的
标准是 RFC2068，之后发布的修订版 RFC2616 就是当前的最新版本可见，
作为 Web 文档传输协议的 HTTP，它的版本几乎没有更新。新一代 HTTP/2.0 
正在制订中，但要达到较高的使用覆盖率，仍需假以时日。

