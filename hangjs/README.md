# Hangjs Summary

by [junmer](https://github.com/junmer), [slide](http://junmer.github.io/hangjs) by [reveal-md](https://github.com/webpro/reveal-md)

---

## Then.js 异步库的实现原理及优缺点 

* `Callback`: [cps](http://en.wikipedia.org/wiki/Continuation-passing_style), [async](https://github.com/caolan/async)
* `Event`: [EventEmitter](http://nodejs.org/api/events.html)
* `Promise`: [when](https://github.com/cujojs/when), [Promise](https://github.com/then/promise), [Q](https://github.com/kriskowal/q)
* `Generator`: [es6](http://wiki.ecmascript.org/doku.php?id=harmony:generators), [co](https://github.com/visionmedia/co), [gnode](https://github.com/TooTallNate/gnode)
* `Thunk`: [thunks](https://github.com/teambition/thunks) 

----

> [严清](https://github.com/zensh/jsgen)  
> [Then.js 异步库的实现原理及优缺点](http://2014.jsconf.cn/slides/%E4%B8%A5%E6%B8%85-JavaScript%E5%BC%82%E6%AD%A5%E5%BA%93%E5%8E%9F%E7%90%86%E5%8F%8A%E5%AF%B9%E6%AF%94.key.zip)  
> [then.js](https://github.com/zensh/then.js)  

---

## Atom编辑器嵌入Node.js引擎实践

* [Atom](https://github.com/atom/atom) 是GitHub出品的文本编辑器
* [Atom Shell](https://github.com/atom/atom-shell) 是可用Node.js编程的 
最小化[Chromium](https://github.com/chromium/chromium)浏览器

----

> [赵成](https://github.com/zcbenz)  
> [Atom编辑器嵌入Node.js引擎实践](http://2014.jsconf.cn/slides/Practice%20on%20embedding%20Node.js%20into%20Atom%20Editor.pdf)  

---

## 淘宝前后端分离实践 (推荐)

* `吐槽` 前后端分工混乱 
* `主题` NODEJS 拯救世界
* `实施` 接口服务化 ([JSON Schema](http://json-schema.org/))、代码模块化([XMD](http://addyosmani.com/writing-modular-js/))、功能组件化

----

> [赫门](http://weibo.com/threeday0905)  
> [淘宝前后端分离实践](http://2014.jsconf.cn/slides/herman-taobaoweb/index.html)  
> [taobao ued](http://ued.taobao.org/blog/category/bowen/frontend/)  

---

## Google BigQuery API Node.js实践

* [Google BigQuery](https://developers.google.com/bigquery) 很强大
* po主 通过[oauth](http://oauth.net/) 实现了一个 npm module [bigquery](https://github.com/peihsinsu/bigquery)
* 更多可以玩的 [google apis](https://developers.google.com/apis-explorer/)

----

> [苏培欣](https://github.com/zcbenz)  
> [Google BigQuery API Node.js实践](http://2014.jsconf.cn/slides/JSConf%20-%20Google%20BigQuery%20API%20Node.js%E5%AF%A6%E4%BD%9C%E8%A8%98%E9%8C%84.pdf)  
> [OpenNodes](HTTP://OpenNodes.arecord.us)  

---

## Peer-Directed Collaborative Projects

* 万物皆 [module](http://wiki.commonjs.org/wiki/Modules)
* 使用 [stream](https://github.com/substack/stream-handbook) 连接程序
* [browserify](http://browserify.org/) 让Node模块在浏览器里策马奔腾
* 新玩具 [voxel](http://voxeljs.com/)

----

> [James Halliday](https://github.com/substack)  
> [Peer-Directed Collaborative Projects](https://github.com/substack/hangjs-2014)  
> [nodeschool.io](http://nodeschool.io/)  

---

## Patrisika - Theoretical and Practical Code Generation

* 一个语法像 [LISP](http://zh.wikipedia.org/wiki/LISP)，会编译成js的语言？不明觉厉

----

> [be5invis](http://typeof.net/)  
> [patrisika](https://github.com/be5invis/patrisika)  

---

## 如何快速构建MVC应用 

* 介绍了一个成长中node的MVC framework [Rabbit.js](https://github.com/xinyu198736/Rabbit.js)  
* 业界著名: [Sails.js](http://sailsjs.org/), [Geddy.js](http://geddyjs.org/), [Express.js](http://expressjs.com/)
* 我更喜欢po主的另一个作品 [颜文字](http://html-js.com/static/yanwenzi.html)

----

> [小芋头君](http://weibo.com/676588498)  
> [Node.js MVC Construction Rabbit.js快速构建MVC应用](http://2014.jsconf.cn/slides/Rabbit.js-MVC.pdf)  

---

## BlendUI - 让轻应用如Native般流畅 

* 另辟蹊径的解决webapp性能问题
* 在webapp中用JS调用native组件
* BlendUI 用web封装轻量级的Native运行环境 满足性能、灵活性、能力、API四方面要求

----

> [berg](http://cnberg.com/)  
> [BlendUI](https://github.com/Clouda-team/BlendUI)  
> [BlendUI 让轻应用如Native般流畅](http://2014.jsconf.cn/slides/BlendUI.pdf)  

---

## 优化你的Angular Web App 

* 很多干货: 路由切换锁定、合理绑定、数据共享... 
* 一些 `SEO` 方面的技巧，对我们的 `SPA` 项目很适用

----

> [sofish](http://sofi.sh/)  
> [优化你的Angular Web App](http://sofi.sh/2412)  

---

## 开源项目的管理与维护 

* `github` 挖坑指南
* 找到一个 [ 垂直 | 有趣 | 成长 | 爆发 ] 的坑、挖出一个世界

----

> [郭宇](https://github.com/turingou)  
> [开源项目的管理与维护](https://github.com/turingou/hangjs)  
> [github排行榜](http://data.cloudaice.com/)  
> [tessel](https://tessel.io/)  

---

## Massive Javascript Development 

* 大型复杂项目的设计原则
* 细粒度，组件化，信息/事件驱动，异步

----

> [Mikael Karon](https://github.com/mikaelkaron)  
> [Massive Javascript Development](http://2014.jsconf.cn/slides/mikaelkaron-massivejs/massive-js.html)  

---

## Scalable Web Application with TroopJS 

* 其实是楼上的实现, 看[todo mvc](http://todomvc.com/labs/dependency-examples/troopjs_require/)感受一下

----

> [Garry Yao](https://github.com/garryyao)  
> [Scalable Web Application with TroopJS](http://2014.jsconf.cn/slides/garryyao-troopjs/scalable-web-application-with-troopjs.html)  
> [troopjs](https://github.com/troopjs)  

---

## 如何持续技术学习 （推荐）

* 如何做一个有追求的程序员
* 知识管理 + 时间管理 + 心态

----

> [玉伯](http://lifesinger.github.com)  
> [如何持续技术学习](http://2014.jsconf.cn/slides/how-to-continue-to-grow-up.pdf)  

---

## Node.js 與多方服務串接實務 

* 先响应, 后处理, 任务扔队列
* [socket](http://socket.io/) 推反馈
* 异常处理，一个都不能少

----

> [Caesar Chi](https://github.com/clonn/)  
> [Server Connect To API / 3rd Service Pattern](http://2014.jsconf.cn/slides/nodejs_api_connect_jsconfcn_hangjs.pdf)  
> [Node.js Taiwan 社群協作中文電子書](https://github.com/nodejs-tw/nodejs-wiki-book)  

---

## five-lines (深入浅出 node 命令行工具)

* 重点不是用node调几个api
* 脑洞大开的 [NodeOS](https://github.com/NodeOS)

----

> [Jacob Groundwater](https://github.com/groundwater)  
> [five-lines 深入浅出 node 命令行工具](http://2014.jsconf.cn/slides/five-lines.pdf)  
> [Remote Shell Using All Node](http://2014.jsconf.cn/slides/Remote%20Shell%20Using%20All%20Node.mp4)  
> [remote Shell Using All Node - youtube](http://youtu.be/q1djgp5qv28)  

---

## Edge.js

* 通过这个, node 和 .NET 在一起了
* 在一起干什么呢？这是个问题

----

> [Iris](http://irisclasson.com/)  
> [Edge.js](http://tjanczuk.github.io/edge/)  

---

## Hybrid API

* 各种各样的传感器，让webapp更具可玩性

----

> [鬼道](http://luics.github.io/)  
> [Hybrid API](http://2014.jsconf.cn/slides/luics-hybrid-api.html)  
> [W3C Device APIs Working Group](http://www.w3.org/2009/dap/)  
> [Phonegap Docs](http://docs.phonegap.com/en/3.5.0/index.html)  

---

## Storm - Distributed and fault-tolerant realtime computation 

* 一个开放了node api的大数据解决方案

----

> [Luying Li](http://www.linkedin.com/pub/luying-li/20/854/556)  
> [Storm - Distributed and fault-tolerant realtime computation](http://2014.jsconf.cn/slides/Introduction-To-Storm.pdf)  
> [Storm](https://github.com/nathanmarz/storm)  

---

## Web Components标准：前端开发的新一次技术革命

* [Shadow DOM](http://w3c.github.io/webcomponents/spec/shadow/)
* [HTML Imports](http://w3c.github.io/webcomponents/spec/imports/)
* [Custom Elements](http://w3c.github.io/webcomponents/spec/custom/)

----

> [陈本峰](http://weibo.com/chenbenfeng)  
> [Web Components Spec](http://w3c.github.io/webcomponents/explainer/)  
> [x-tags](http://www.x-tags.org/)  
> [polymer](http://www.polymer-project.org/)  
> [try e-charts](http://junmer.github.io/e-charts/)  
> [customelements.io](http://customelements.io/)  
> [amazeui](http://www.amazeui.org/landing/)  

---

# process.exit()

----

> [hangjs](http://2014.jsconf.cn/)  
> [hangjs@github](https://github.com/jsconfcn/hangjs)  
