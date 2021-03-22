# Blog知识体系
-------

这是我的个人博客，用于记录自己在前端道路上的成长，文章将和 [https://bubuzou.com/](https://bubuzou.com/) 这个网站同步更新，喜欢的可以关注一下哈😘。众所周知，前端开发入门简单，但是如果要深入这个岗位其实是需要付出巨大的努力和时间的，因为前端知识繁杂，涉及到的点和面很多，而且前端技术日新月异更新速度可谓非常之快。所以如果想要在这个岗位深耕下去，就必须得有一个知识图谱来引导我们去学习。`winter` 老师也说过学习前端要建立自己的知识体系，然后自从我在掘金上看过字节大佬 `ConardLi` 精心写的这篇 [一名【合格】前端工程师的自检清单](https://juejin.im/post/5cc1da82f265da036023b628)之后，就感觉前端的知识体系差不多就是这么回事了，于是就决定先按照这个路线来学习，后面也会慢慢扩充自己的知识体系，也欢迎大家跟我一起来学习💪。

**文章列表直接看**：[Issues](https://github.com/Bulandent/blog/issues)

![web_knowledge](https://bubuzou.oss-cn-shenzhen.aliyuncs.com/blog/202006/web_knowledge.png)


也欢迎大家关注我的公众号：「大海我来了」，会经常更新前端干货文章。
![gzh](https://bubuzou.oss-cn-shenzhen.aliyuncs.com/blog/202009/gzh.png)

# 目录
- [一、JavaScript基础](#一JavaScript基础)
    - [变量和类型](#变量和类型-)
    - [原型和原型链](#原型和原型链-)
    - [作用域和闭包](#作用域和闭包-)
    - [执行机制](#执行机制-)
    - [语法和API](#语法和API-)
- [二、HTML和CSS](#二HTML和CSS)
    - [HTML](#HTML-)
    - [CSS](#CSS-)
    - [手写](#手写-)
- [三、计算机基础](#三计算机基础)
    - [编译原理](#编译原理-)
    - [网络协议](#网络协议-)
    - [设计模式](#设计模式-)
- [四、数据结构和算法](#四数据结构和算法)
    - [JavaScript编码能力](#JavaScript编码能力-)
    - [手动实现前端轮子](#手动实现前端轮子-)
    - [数据结构](#数据结构-)
    - [算法](#算法-)
- [五、运行环境](#五运行环境)
    - [浏览器API](#浏览器API-)
    - [浏览器原理](#浏览器原理-)
    - [Node](#Node-)
- [六、框架和类库](#六框架和类库)
    - [TypeScript](#TypeScript-)
    - [React](#React-)
    - [Vue](#Vue-)
    - [多端开发](#多端开发-)
    - [数据流管理](#数据流管理-)
    - [实用库](#实用库-)
    - [开发和调试](#开发和调试-)
- [七、前端工程](#七前端工程)
    - [项目构建](#项目构建-)
    - [nginx](#nginx-)
    - [开发提速](#开发提速-)
    - [版本控制](#版本控制-)
    - [持续集成](#持续集成-)
    - [代码质量](#代码质量-)
- [八、项目](#八项目)
    - [性能优化](#性能优化-)
    - [前端安全](#前端安全-)

## 一、JavaScript基础 

### 变量和类型 [⬆](#目录)

- [ ] 1.JavaScript规定了几种语言类型
- [ ] 2.JavaScript对象的底层数据结构是什么
- [ ] 3.Symbol类型在实际开发中的应用、可手动实现一个简单的
- [ ] 4.JavaScript中的变量在内存中的具体存储形式
- [ ] 5.基本类型对应的内置对象，以及他们之间的装箱拆箱操作
- [ ] 6.理解值类型和引用类型
- [ ] 7.null和undefined的区别
- [ ] 8.至少可以说出三种判断JavaScript数据类型的方式，以及他们的优缺点，如何准确的判断数组类型
- [ ] 9.可能发生隐式类型转换的场景以及转换原则，应如何避免或巧妙应用
- [ ] 10.出现小数精度丢失的原因，JavaScript可以存储的最大数字、最大安全数字，JavaScript处理大数字的方法、避免精度丢失的方法

学习与总结：

- [JavaScript中的数据类型](https://github.com/Bulandent/blog/issues/3)

### 原型和原型链 [⬆](#目录)

- [ ] 1.理解原型设计模式以及JavaScript中的原型规则
- [ ] 2.instanceof的底层实现原理，手动实现一个instanceof
- [ ] 3.实现继承的几种方式以及他们的优缺点
- [ ] 5.至少说出一种开源项目(如Node)中应用原型继承的案例
- [ ] 6.可以描述new一个对象的详细过程，手动实现一个new操作符
- [ ] 7.理解es6 class构造以及继承的底层实现原理

### 作用域和闭包 [⬆](#目录)

- [ ] 1.理解词法作用域和动态作用域
- [ ] 2.理解JavaScript的作用域和作用域链
- [ ] 3.理解JavaScript的执行上下文栈，可以应用堆栈信息快速定位问题
- [ ] 4.this的原理以及几种不同使用场景的取值
- [ ] 5.闭包的实现原理和作用，可以列举几个开发中闭包的实际应用
- [ ] 6.理解堆栈溢出和内存泄漏的原理，如何防止
- [ ] 7.如何处理循环的异步操作
- [ ] 8.理解模块化解决的实际问题，可列举几个模块化方案并理解其中原理

### 执行机制 [⬆](#目录)

- [ ] 1.为何try里面放return，finally还会执行，理解其内部机制
- [ ] 2.JavaScript如何实现异步编程，可以详细描述EventLoop机制
- [ ] 3.宏任务和微任务分别有哪些
- [ ] 4.可以快速分析一个复杂的异步嵌套逻辑，并掌握分析方法
- [ ] 5.使用Promise实现串行
- [ ] 6.Node与浏览器EventLoop的差异
- [ ] 7.如何在保证页面运行流畅的情况下处理海量数据

学习与总结：

- [深入理解Promise](https://github.com/Bulandent/blog/issues/9)

### 语法和API [⬆](#目录)

- [ ] 1.理解ECMAScript和JavaScript的关系
- [ ] 2.熟练运用es5、es6提供的语法规范，
- [ ] 3.熟练掌握JavaScript提供的全局对象（例如Date、Math）、全局函数（例如decodeURI、isNaN）、全局属性（例如Infinity、undefined）
- [ ] 4.熟练应用map、reduce、filter 等高阶函数解决问题
- [ ] 5.setInterval需要注意的点，使用settimeout实现setInterval
- [ ] 6.JavaScript提供的正则表达式API、可以使用正则表达式（邮箱校验、URL解析、去重等）解决常见问题
- [ ] 7.JavaScript异常处理的方式，统一的异常处理方案

学习与总结：

- [送你一份精心总结的3万字ES6实用指南（全）](https://github.com/Bulandent/blog/issues/10)
- [让人爱不释手的 JS 扩展操作符 13 用](https://github.com/Bulandent/blog/issues/23)

## 二、HTML和CSS

### HTML [⬆](#目录)

- [ ] 1.从规范的角度理解HTML，从分类和语义的角度使用标签
- [ ] 2.常用页面标签的默认样式、自带属性、不同浏览器的差异、处理浏览器兼容问题的方式
- [ ] 3.元信息类标签(head、title、meta)的使用目的和配置方法
- [ ] 4.HTML5离线缓存原理
- [ ] 5.可以使用Canvas API、SVG等绘制高性能的动画

### CSS [⬆](#目录)

- [ ] 1.CSS盒模型，在不同浏览器的差异
- [ ] 2.CSS所有选择器及其优先级、使用场景，哪些可以继承，如何运用at规则
- [ ] 3.CSS伪类和伪元素有哪些，它们的区别和实际应用
- [ ] 4.HTML文档流的排版规则，CSS几种定位的规则、定位参照物、对文档流的影响，如何选择最好的定位方式，雪碧图实现原理
- [ ] 5.水平垂直居中的方案、可以实现6种以上并对比它们的优缺点
- [ ] 6.BFC实现原理，可以解决的问题，如何创建BFC
- [ ] 7.可使用CSS函数复用代码，实现特殊效果
- [ ] 8.PostCSS、Sass、Less的异同，以及使用配置，至少掌握一种
- [ ] 9.CSS模块化方案、如何配置按需加载、如何防止CSS阻塞渲染
- [ ] 10.熟练使用CSS实现常见动画，如渐变、移动、旋转、缩放等等
- [ ] 11.CSS浏览器兼容性写法，了解不同API在不同浏览器下的兼容性情况
- [ ] 12.掌握一套完整的响应式布局方案

学习与总结：

- [图解Flexbox](https://github.com/Bulandent/blog/issues/2)
- [良好的CSS编码习惯](https://github.com/Bulandent/blog/issues/8)
- [1.5 万字 CSS 基础拾遗（核心知识、常见需求）](https://github.com/Bulandent/blog/issues/27)

### 手写 [⬆](#目录)

- [ ] 1.手写图片瀑布流效果
- [ ] 2.使用CSS绘制几何图形（圆形、三角形、扇形、菱形等）
- [ ] 3.使用纯CSS实现曲线运动（贝塞尔曲线）
- [ ] 4.实现常用布局（三栏、圣杯、双飞翼、吸顶），可是说出多种方式并理解其优缺点

## 三、计算机基础

### 编译原理 [⬆](#目录)

- [ ] 1.理解代码到底是什么，计算机如何将代码转换为可以运行的目标程序
- [ ] 2.正则表达式的匹配原理和性能优化
- [ ] 3.如何将JavaScript代码解析成抽象语法树(AST)
- [ ] 4.base64的编码原理
- [ ] 5.几种进制的相互转换计算方法，在JavaScript中如何表示和转换

### 网络协议 [⬆](#目录)

- [ ] 1.理解什么是协议，了解TCP/IP网络协议族的构成，每层协议在应用程序中发挥的作用
- [ ] 2.三次握手和四次挥手详细原理，为什么要使用这种机制
- [ ] 3.有哪些协议是可靠，TCP有哪些手段保证可靠交付
- [ ] 4.DNS的作用、DNS解析的详细过程，DNS优化原理
- [ ] 5.CDN的作用和原理
- [ ] 6.HTTP请求报文和响应报文的具体组成，能理解常见请求头的含义，有几种请求方式，区别是什么
- [ ] 7.HTTP所有状态码的具体含义，看到异常状态码能快速定位问题
- [ ] 8.HTTP1.1、HTTP2.0带来的改变
- [ ] 9.HTTPS的加密原理，如何开启HTTPS，如何劫持HTTPS请求
- [ ] 10.理解WebSocket协议的底层原理、与HTTP的区别

学习与总结：

- [6 分钟了解 HTTP 发展史](https://github.com/Bulandent/blog/issues/26)

### 设计模式 [⬆](#目录)

- [ ] 1.熟练使用前端常用的设计模式编写代码，如单例模式、装饰器模式、代理模式等
- [ ] 2.发布订阅模式和观察者模式的异同以及实际应用
- [ ] 3.可以说出几种设计模式在开发中的实际应用，理解框架源码中对设计模式的应用

## 四、数据结构和算法

### JavaScript编码能力 [⬆](#目录)

- [ ] 1.多种方式实现数组去重、扁平化、对比优缺点
- [ ] 2.多种方式实现深拷贝、对比优缺点
- [ ] 3.手写函数柯里化工具函数、并理解其应用场景和优势
- [ ] 4.手写防抖和节流工具函数、并理解其内部原理和应用场景
- [ ] 5.实现一个sleep函数

学习与总结：

- [详细设计一个文章页目录插件](https://github.com/Bulandent/blog/issues/7)

### 手动实现前端轮子 [⬆](#目录)

- [ ] 1.手动实现call、apply、bind
- [ ] 2.手动实现符合Promise/A+规范的Promise、手动实现async await
- [ ] 3.手写一个EventEmitter实现事件发布、订阅
- [ ] 4.可以说出两种实现双向绑定的方案、可以手动实现
- [ ] 5.手写JSON.stringify、JSON.parse
- [ ] 6.手写一个模版引擎，并能解释其中原理
- [ ] 7.手写懒加载、下拉刷新、上拉加载、预加载等效果

### 数据结构 [⬆](#目录)

- [ ] 1.理解常见数据结构的特点，以及他们在不同场景下使用的优缺点
- [ ] 2.理解数组、字符串的存储原理，并熟练应用他们解决问题
- [ ] 3.理解二叉树、栈、队列、哈希表的基本结构和特点，并可以应用它解决问题
- [ ] 4.了解图、堆的基本结构和使用场景

### 算法 [⬆](#目录)

- [ ] 1.可计算一个算法的时间复杂度和空间复杂度，可估计业务逻辑代码的耗时和内存消耗
- [ ] 2.至少理解五种排序算法的实现原理、应用场景、优缺点，可快速说出时间、空间复杂度
- [ ] 3.了解递归和循环的优缺点、应用场景、并可在开发中熟练应用
- [ ] 4.可应用回溯算法、贪心算法、分治算法、动态规划等解决复杂问题
- [ ] 5.前端处理海量数据的算法方案

## 五、运行环境

### 浏览器API [⬆](#目录)

- [ ] 1.浏览器提供的符合W3C标准的DOM操作API、浏览器差异、兼容性
- [ ] 2.浏览器提供的浏览器对象模型 (BOM)提供的所有全局API、浏览器差异、兼容性
- [ ] 3.大量DOM操作、海量数据的性能优化(合并操作、Diff、requestAnimationFrame等)
- [ ] 4.浏览器海量数据存储、操作性能优化
- [ ] 5.DOM事件流的具体实现机制、不同浏览器的差异、事件代理
- [ ] 6.前端发起网络请求的几种方式及其底层实现、可以手写原生ajax、fetch、可以熟练使用第三方库
- [ ] 7.浏览器的同源策略，如何避免同源策略，几种方式的异同点以及如何选型
- [ ] 8.浏览器提供的几种存储机制、优缺点、开发中正确的选择
- [ ] 9.浏览器跨标签通信

学习与总结：

- [浏览器专题之事件机制](https://github.com/Bulandent/blog/issues/13)
- [浏览器专题之本地存储](https://github.com/Bulandent/blog/issues/15)
- [Web Worker 综述](https://github.com/Bulandent/blog/issues/19)

### 浏览器原理 [⬆](#目录)

- [ ] 1.各浏览器使用的JavaScript引擎以及它们的异同点、如何在代码中进行区分
- [ ] 2.请求数据到请求结束与服务器进行了几次交互
- [ ] 3.可详细描述浏览器从输入URL到页面展现的详细过程
- [ ] 4.浏览器解析HTML代码的原理，以及构建DOM树的流程
- [ ] 5.浏览器如何解析CSS规则，并将其应用到DOM树上
- [ ] 6.浏览器如何将解析好的带有样式的DOM树进行绘制
- [ ] 7.浏览器的运行机制，如何配置资源异步同步加载
- [ ] 8.浏览器回流与重绘的底层原理，引发原因，如何有效避免
- [ ] 9.浏览器的垃圾回收机制，如何避免内存泄漏
- [ ] 10.浏览器采用的缓存方案，如何选择和控制合适的缓存方案

学习与总结：

- [浏览器专题之缓存篇](https://github.com/Bulandent/blog/issues/12)
- [从输入url到页面显示发生了什么](https://github.com/Bulandent/blog/issues/14)
- [探究网页资源究竟是如何阻塞浏览器加载的](https://github.com/Bulandent/blog/issues/18)

### Node [⬆](#目录)

- [ ] 1.理解Node在应用程序中的作用，可以使用Node搭建前端运行环境、使用Node操作文件、操作数据库等等
- [ ] 2.掌握一种Node开发框架，如Express，Express和Koa的区别
- [ ] 3.熟练使用Node提供的API如Path、Http、Child Process等并理解其实现原理
- [ ] 4.Node的底层运行原理、和浏览器的异同
- [ ] 5.Node事件驱动、非阻塞机制的实现原理

学习与总结：

- [使用nvm来管理Node版本](https://github.com/Bulandent/blog/issues/5)

## 六、框架和类库

### TypeScript [⬆](#目录)

- [ ] 1.理解泛型、接口等面向对象的相关概念，TypeScript对面向对象理念的实现
- [ ] 2.理解使用TypeScript的好处，掌握TypeScript基础语法
- [ ] 3.TypeScript的规则检测原理
- [ ] 4.可以在React、Vue等框架中使用TypeScript进行开发

### React [⬆](#目录)

- [ ] 1.React和vue选型和优缺点、核心架构的区别
- [ ] 2.React中setState的执行机制，如何有效的管理状态
- [ ] 3.React的事件底层实现机制
- [ ] 4.React的虚拟DOM和Diff算法的内部实现
- [ ] 5.React的Fiber工作原理，解决了什么问题
- [ ] 6.React Router和Vue Router的底层实现原理、动态加载实现原理
- [ ] 7.可熟练应用React API、生命周期等，可应用HOC、render props、Hooks等高阶用法解决问题
- [ ] 8.基于React的特性和原理，可以手动实现一个简单的React

### Vue [⬆](#目录)

- [ ] 1.熟练使用Vue的API、生命周期、钩子函数
- [ ] 2.MVVM框架设计理念
- [ ] 3.Vue双向绑定实现原理、Diff算法的内部实现
- [ ] 4.Vue的事件机制
- [ ] 5.从template转换成真实DOM的实现机制

学习与总结：

- [34条我能告诉你的Vue之实操篇](https://github.com/Bulandent/blog/issues/6)
- [基于Vue的Jest单元测试入门与实践](https://github.com/Bulandent/blog/issues/11)
- [如何做到发送一次请求上传多个文件（使用 el-upload）](https://github.com/Bulandent/blog/issues/21)
- [vue-quill-editor插入图片路径太长问题解决](https://github.com/Bulandent/blog/issues/22)

### 多端开发 [⬆](#目录)

- [ ] 1.单页面应用（SPA）的原理和优缺点，掌握一种快速开发SPA的方案
- [ ] 2.理解Viewport、em、rem的原理和用法，分辨率、px、ppi、dpi、dp的区别和实际应用
- [ ] 3.移动端页面适配解决方案、不同机型适配方案
- [ ] 4.掌握一种JavaScript移动客户端开发技术，如React Native：可以搭建React Native开发环境，熟练进行开发，可理解React Native的运作原理，不同端适配
- [ ] 5.掌握一种JavaScript PC客户端开发技术，如Electron：可搭建Electron开发环境，熟练进行开发，可理解Electron的运作原理
- [ ] 6.掌握一种小程序开发框架或原生小程序开发
- [ ] 7.理解多端框架的内部实现原理，至少了解一个多端框架的使用

学习与总结：

- [小程序升级WePY2踩坑记](https://github.com/Bulandent/blog/issues/4)

### 数据流管理 [⬆](#目录)

- [ ] 1.掌握React和Vue传统的跨组件通信方案，对比采用数据流管理框架的异同
- [ ] 2.熟练使用Redux管理数据流，并理解其实现原理，中间件实现原理
- [ ] 3.熟练使用Mobx管理数据流，并理解其实现原理，相比Redux有什么优势
- [ ] 4.熟练使用Vuex管理数据流，并理解其实现原理
- [ ] 5.以上数据流方案的异同和优缺点，不情况下的技术选型

### 实用库 [⬆](#目录)

- [ ] 1.至少掌握一种UI组件框架，如antd design，理解其设计理念、底层实现
- [ ] 2.掌握一种图表绘制框架，如Echart，理解其设计理念、底层实现，可以自己实现图表
- [ ] 3.掌握一种GIS开发框架，如百度地图API
- [ ] 4.掌握一种可视化开发框架，如Three.js、D3
- [ ] 5.工具函数库，如lodash、underscore、moment等，理解使用的工具类或工具函数的具体实现原理

### 开发和调试 [⬆](#目录)

- [ ] 1.熟练使用各浏览器提供的调试工具
- [ ] 2.熟练使用一种代理工具实现请求代理、抓包，如charls
- [ ] 3.可以使用Android、IOS模拟器进行调试，并掌握一种真机调试方案
- [ ] 4.了解Vue、React等框架调试工具的使用

## 七、前端工程

### 项目构建 [⬆](#目录)

- [ ] 1.理解npm、yarn依赖包管理的原理，两者的区别
- [ ] 2.可以使用npm运行自定义脚本
- [ ] 3.理解Babel、ESLint、webpack等工具在项目中承担的作用
- [ ] 4.ESLint规则检测原理，常用的ESLint配置
- [ ] 5.Babel的核心原理，可以自己编写一个Babel插件
- [ ] 6.可以配置一种前端代码兼容方案，如Polyfill
- [ ] 7.Webpack的编译原理、构建流程、热更新原理，chunk、bundle和module的区别和应用
- [ ] 8.可熟练配置已有的loaders和plugins解决问题，可以自己编写loaders和plugins

### nginx [⬆](#目录)

- [ ] 1.正向代理与反向代理的特点和实例
- [ ] 2.可手动搭建一个简单的nginx服务器、
- [ ] 3.熟练应用常用的nginx内置变量，掌握常用的匹配规则写法
- [ ] 4.可以用nginx实现请求过滤、配置gzip、负载均衡等，并能解释其内部原理

### 开发提速 [⬆](#目录)

- [ ] 1.熟练掌握一种接口管理、接口mock工具的使用，如yapi
- [ ] 2.掌握一种高效的日志埋点方案，可快速使用日志查询工具定位线上问题
- [ ] 3.理解TDD与BDD模式，至少会使用一种前端单元测试框架

### 版本控制 [⬆](#目录)

- [ ] 1.理解Git的核心原理、工作流程、和SVN的区别
- [ ] 2.熟练使用常规的Git命令、git rebase、git stash等进阶命令
- [ ] 3.可以快速解决线上分支回滚、线上分支错误合并等复杂问题

学习与总结：

- [Git常用操作命令一览](https://github.com/Bulandent/blog/issues/1)

### 持续集成 [⬆](#目录)

- [ ] 1.理解CI/CD技术的意义，至少熟练掌握一种CI/CD工具的使用，如Jenkins
- [ ] 2.可以独自完成架构设计、技术选型、环境搭建、全流程开发、部署上线等一套完整的开发流程（包括Web应用、移动客户端应用、PC客户端应用、小程序、H5等等）

### 代码质量 [⬆](#目录)

- [ ] 1. 能够熟练使用ESLint进行代码校验
- [ ] 2. 熟悉前端单元测试框架 Mocha、Jest等

学习与总结：

- [基于Vue的Jest单元测试入门与实践](https://github.com/Bulandent/blog/issues/11)

## 八、项目

### 性能优化 [⬆](#目录)
- [ ] 1.了解前端性能衡量指标、性能监控要点，掌握一种前端性能监控方案
- [ ] 2.了解常见的Web、App性能优化方案
- [ ] 3.SEO排名规则、SEO优化方案、前后端分离的SEO
- [ ] 4.SSR实现方案、优缺点、及其性能优化
- [ ] 5.Webpack的性能优化方案
- [ ] 6.Canvas性能优化方案
- [ ] 7.React、Vue等框架使用性能优化方案

学习与总结：

- [jpg、gif、png和svg用于web上，我们该如何选择最合适的图像格式？](https://github.com/Bulandent/blog/issues/17)
- [preload、prefetch、preconnect 和 dns-prefetch 知多少](https://github.com/Bulandent/blog/issues/20)
- [为你的网站加上 WebP 格式的图片吧](https://github.com/Bulandent/blog/issues/24)
- [2分钟了解下一代图片压缩格式 AVIF](https://github.com/Bulandent/blog/issues/25)

### 前端安全 [⬆](#目录)

- [ ] 1.XSS攻击的原理、分类、具体案例，前端如何防御
- [ ] 2.CSRF攻击的原理、具体案例，前端如何防御
- [ ] 3.HTTP劫持、页面劫持的原理、防御措施

学习与总结：

- [浏览器专题之安全篇](https://github.com/Bulandent/blog/issues/16)
