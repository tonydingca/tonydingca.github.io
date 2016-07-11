# Money life collection

>This is a Blog to collect useful information for Software development

---

## Content
- [Tool/Software] #tools
- [Node Package](#node_package)


<h2 id="tools"> Tools/Software </h2>
<h3 id="web">Web Related <h3>


<h3 id="node_package">Node Package</h3>

##### Very feature and must known package of Node

- [anywhere](https://www.npmjs.com/package/anywhere) - 随时随地将你的当前目录变成一个静态文件服务器的根目录
- [supervisor](https://www.npmjs.com/package/supervisor) - 监控 Node 代码，自动重启。 A supervisor program for running nodejs programs
- [nodemon](https://github.com/remy/nodemon) - 监控 Node 代码，自动重启。 Nodemon is a utility that will monitor for any changes in your source and automatically restart your server.
- [pm2](https://www.npmjs.com/package/pm2) - 是一个带有负载均衡功能的 Node 应用的进程管理器； 是 [Forever](https://www.npmjs.com/package/forever) 的进阶库，想了解的可以看这篇文章[《拥抱PM2》](http://se77en.cc/2013/06/27/goodbye-node-forever-hello-pm2-translation/)
- [async](https://www.npmjs.com/package/async) - 一个流程控制工具包，提供直接而强大的异步功能
- [optimist](https://www.npmjs.com/package/optimist) - 当需要处理 ```CLI``` 中的 ```argv``` 时(即命令行传参)，用它就行了
- [lodash](https://www.npmjs.com/package/lodash) - JS 工具库 ```Underscore.js```的一个 fork 发展而来
- [socket.io](https://github.com/socketio/socket.io) - 预计 Node 的实时框架 聊天室、页游等对实时性有高要求的较适用
- [Mongoose](https://github.com/Automattic/mongoose) - 让 NodeJS 更容易操作 Mongodb 数据库；  附上一篇[Mongoose 学习参考文档](https://cnodejs.org/topic/504b4924e2b84515770103dd)
- [CNPM](http://npm.taobao.org/) - 淘宝 NPM 镜像，提供了 NPM 同步的服务 当然可不仅仅这样，利用 CNPM 可以打造__企业/个人__私有的 NPM 服务 推荐篇搭建私有NPM的文章：[《CNPM搭建私有的NPM服务》](http://blog.fens.me/nodejs-cnpm-npm/)
- [koa](http://koajs.com/) - 玩 Node 都知道 express，但使用 koa 的就少很多，门槛比 Ex 稍高 通过 generator 避免繁琐的回调函数嵌套，强烈推崇 [官方的文章教程](https://github.com/guo-yu/koa-guide)
- [Shipit](https://github.com/shipitjs/shipit) - 一个强大的自动化部署工具。 shipit 很多地方非常类似 gulp，他们的核心都是任务系统。
- [node-inspector](https://www.npmjs.com/package/node-inspector) - Node 调试工具，使用起来跟 Chrome 的 JS 调试器很相似
- [winston](https://www.npmjs.com/package/winston) - Node 服务最流行的日志库之一
- [co](https://www.npmjs.com/package/co) - 用 generator 写法让异步代码同步
- [thenify-all](https://www.npmjs.com/package/thenify-all) - 把异步的方法变成 Promise 的 Promisifies all the selected functions in an object
- [PhantomJS](http://phantomjs.org/) - 一般用来做抓取截图和无界面测试 也可以用来操作 DOM 和网络监测，很好玩的库 [Quick Start](http://phantomjs.org/quick-start.html)
- [ava](https://www.npmjs.com/package/ava) - 偶是应TJ大神推荐而得之的 ```ava``` 未来的测试运行器
- [Mocha](https://github.com/mochajs/mocha) - Node 里最常用的测试框架； 它支持多种 Node 的 Assert libs； 同时支持异步和同步的测试，同时支持多种方式导出结果； 也支持直接在 browser 上跑 JS 代码测试。
- [koa-validate](https://www.npmjs.com/package/koa-validate) - ```koa``` 的校验库 可以非常方便的对 ```queryString``` 或 ```postBody``` 的信息进行验证
- [line-reader](https://www.npmjs.com/package/line-reader) - 基于```steam```的按行读文件，偶处理日志时用哒 要不实现一个按行读文件，又得 ```steam```、 又得 ```chunk```，还是比较麻烦的
- [binary](https://github.com/substack/node-binary) 作者是大神 [substack](https://github.com/substack)，对应的处理 ```PHP/Python``` 中的 ```unpack``` 方法。英文解释：Unpack multibyte binary values from buffers and streams.
- [everyauth](https://www.npmjs.com/package/everyauth)| |OAuth 的集成解决方案
- [shelljs](http://documentup.com/shelljs/shelljs) - 写 Node 时难免需要用 shell 去操作些神马 shelljs 是基于 Node 的 shell 工具，API 及其简单
- [hashids](https://www.npmjs.com/package/hashids) - 看名称就懂，给 userid 加解密用的
- [node-pool](https://github.com/coopernurse/node-pool) - 让 ```Node``` 有连接池的概念
- [colors](https://www.npmjs.com/package/colors) - 花俏的小工具 让打印```console.log```时有更好的展示样式
- [n](https://www.npmjs.com/package/n) - 控制Node的版本，想升级一行代码搞定

> ```supervisor``` 和 ```nodemon``` 这俩都是监控 Node 代码，使得每次修改代码后会，开发 Node 程序必备

