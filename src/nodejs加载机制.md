几种模块互用   nodejs加载机制   webpack HMR原理  几个加载器的实现    promise 顺序处理   js 序列化 http2  ant design 表单校验  react/vue 是如何转小程序的   面试了一天 除
还有一个如何实现直播间几万弹幕发送  送礼物 互不影响啥的     乱七八糟的  根本没明白什么需求

nodejs模块引用机制

在node中已入模块时，需要经历三个步骤：
1. 路径分析
2. 文件定位
3. 编译执行

模块分类：
1. 核心模块
2. 文件模块

优先级：

缓存模块 > 核心模块 > 用户模块

.js > .json > .node

自定义模块的路径查找