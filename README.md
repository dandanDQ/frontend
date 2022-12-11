# Frontend

## 1. JavaScript
- 语言核心
  - 语法、类型、语句、关键字、保留字、操作符、全局对象
- 与浏览器交互
  - DOM：文档对象模型
    - 事件
  - BOM：浏览器对象模型
- 探索 JS 最强大的特性：函数表达式
  - 函数式编程
- 面向对象风格编程
  - 对象、类、继承
- 设计模式
- JS 执行机制：事件循环原理
  - 使用回调的异步编程
- 垃圾回收与内存管理
- 语言标准：ECMAScript
  - 了解 JS 发展的历程
  - 熟悉 ES6、ES7 新的语言标准
- node.js
  - 模块机制
  - 异步 I/O
  - 异步编程
    - 基于事件的非阻塞 I/O 模型
  - 内存控制
  - 网络编程
- 类型系统：Typescript

## 2. HTML
- HTML 元素
  - 把网页比作一个房子的话，HTML 是砖瓦，CSS 则是装潢。
  - 分类
    - 文档和元数据元素、文本元素、组织内容元素、文档分节元素、制表元素、表单元素、嵌入内容
- SEO 原理和优化
  - 什么样的 HTML 文档更容易被搜索引擎识别？
- HTML5
  - 可编程内容
    - canvas
  - 原生多媒体支持
    - video audio...
  - 语义化

- 元素坐标的获取
  - Element.getBoundingClientRect()
  - 鼠标点击位置
    - const { screenX, screenY, clientX, clientY, offsetX, offsetY } = e
  - 元素自身属性
- 页面生命周期
  - DOMContentLoaded、load、beforeunload、unload
- 虚拟列表
  - 原理：减少页面同时呈现的 DOM 节点数量，来减少内存消耗，提高页面性能。

## 3. CSS
- 从浏览器渲染进程理解 CSS
  - 回流（reflow）和重绘（repaint）
- 特指度和层叠
  - 对于 CSS 来说，“层叠” 算是最基本的概念。在这个过程中，有冲突的声明按一定顺序排列，由此确定文档的 最终表现。这个过程中还涉及选择符和与其关联的声明的特指度，以及继承机制。
- 盒模型与布局
  - 布局发展历程：从浮动（float），到弹性盒模型（flex，适用一维)，再到栅格布局（grid，适用二维）     
  - 定位：相对定位（relative）、绝对定位（absolute）、固定定位（fixed）、粘滞定位（sticky）
  - 盒模型：内边距、边框、轮廓、外边距
- 视觉格式化
- 响应式设计

## 4. 前端框架
- 框架对比，概要
  - MVC、MVP、MVVM
- react
  - 学习中..
- vue
  - 基本使用
    - vue2、vue3、vue-router、vuex、pinia
  - 深入原理
    - 响应式原理
    - 模板编译原理
    - 虚拟 DOM
    - diff 算法
- Angular
  - 暂无
- Svelte
  - 一种全新的构建用户界面的方法。传统框架如 React 和 Vue 在浏览器中需要做大量的工作，而 Svelte 将这 些工作放到构建应用程序的编译阶段来处理。

## 5. 计算机网络
- 五层模型
  - 应用层
    - DNS 解析
    - HTTP / HTTPS
  - 传输层
    - TCP 连接
  - 网络层
    - IP 协议
    - 路由协议
  - 数据链路层
  - 物理层
- 从输入 URL 到页面呈现过程中，网络是如何工作的？（理解五层模型）
- web 开发中需要了解的 HTTP
  - 强缓存与协商缓存
  - CORS 跨域资源共享（一种基于 HTTP 头的机制）
  - HTTP 各个版本主要的差异：HTTP1.0 HTTP1.1 HTTP2 HTTP3
  - 常见 HTTP 状态码
  - HTTPS 协议
  - 范围请求
    - 用于传输大文件或者断点续传

## 6. 数据结构与算法
- 数据结构
  - 表、栈、队列
  - 链表
  - 二叉树
    - 深度优先搜索
    - 广度优先搜索
  - 散列表（哈希表）
  - 优先队列（堆）
  - 不相交集（并查集）
  - 图
- 算法
  - 排序算法
    - 选择排序、冒泡排序、快速排序、堆排序、桶排序
  - 贪心算法
  - 分治算法
  - 动态规划
    - 背包问题、股票买卖、小偷问题
  - 回溯算法
  - 二分法
  - 复杂度分析

## 7. 前端工程化
- 系统化、规范化、模块化
- 前端模块化
- 编译和构建工具
  - vite、gulp、webpack、turbopack
  - 万变不离其宗：深入编译原理
- 代码质量和规范
  - 代码规范：eslint、prettier
  - git 分支管理规范和 git commit 规范
  - 项目规范：文件的组织方式和命名方式
- 测试
  - 单元测试
  - 端到端测试
- CI/CD
- 监控
  - 性能监控、错误监控、用户信息收集
- 性能优化
  - 网络
  - 内存优化
    - 解决内存泄露问题

## 8. 其他专题
- WebGL
- canvas
- 这么好用的 web API！
  - Observer API：Intersection Observer、Mutation Observer、Resize Observer、Performance Observer    
- WebSocket
- ...


![](./assets/%E5%89%8D%E7%AB%AF%E7%9F%A5%E8%AF%86%E4%BD%93%E7%B3%BB.png)