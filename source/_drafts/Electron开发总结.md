title: Electron开发总结
tags:
    - electron
    - javscript
---

# Electron开发总结与分享

### 什么是Electron
> Electron is a framework for creating native applications with web technologies like JavaScript, HTML, and CSS. 

##### 整体框架
- HTML, CSS, Javascript
- Chromium
- Node
- V8 Engine

##### 谁在使用

### 特性
##### 基于Chromium
##### 独立的Node运行环境
##### 主进程(Main Process)和渲染线程(Render Process)
##### 跨平台

### 与Web页面开发比较
##### 需要注意

##### 知识储备
- NodeJS
- 页面开发
- C++
- 操作系统

### 构建经验
##### 编译及运行
- 入口Main.js
- Debug
##### API
- App
- BrowserWindow
- 进程通信
- WebView

##### 利用WebKit
- 使用前沿的特性 ES6, CSS3
- 数据存储
##### 打包


### 优势与适用场景
##### 优势
- 快速
- 灵活性
- 热更新

##### 限制
- 不过多依赖系统底层
- 性能要求不太高

##### 适用场景
- 页面监控
- 工具
- 交互复杂的Desktop App


### 需要进一步学习
- Crash
- Performance

### 问题清单
##### 安装问题
##### Electron与Node,Chromium版本问题
> Electron’s version of Chromium is usually updated within one or two weeks after a new stable Chromium version is released, depending on the effort involved in the upgrade.

When a new version of Node.js is released, Electron usually waits about a month before upgrading in order to bring in a more stable version.

In Electron, Node.js and Chromium share a single V8 instance—usually the version that Chromium is using. Most of the time this just works but sometimes it means patching Node.js.

### 参考链接
- https://zhuanlan.zhihu.com/p/20225295?columnSlug=FrontendMagazine