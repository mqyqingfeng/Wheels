# 一起造轮子

如果你想造些轮子，不妨可以看看这里。

## 为什么造轮子？

vczh 在知乎问题 [如何能以后达到温赵轮三位大神的水平？](https://www.zhihu.com/question/35864522)下的回答：

> 这十几年我一共做了三件事：
> 
> 1、不以赚钱为目的选择学习的内容；
> 
> 2、以自己是否能造出轮子来衡量学习的效果；
> 
> 3、坚持每天写自己的代码，前10年每天至少6个小时，不包含学习和工作的时间。
> 
> 就做了一点微小的工作，很惭愧，谢谢大家。

## 仓库目的

记录自己造过的一些轮子，方便大家参考实现。

如果你造过比较好的轮子，也欢迎发起 PR。

## 要求

原生实现

## 注意

现在的轮子主要偏 DOM 类。

## 目录

1. [EventEmitter](#1eventemitter)
2. [返回顶部](#2返回顶部)
3. [顶部进度条](#3顶部进度条)
4. [滚动时固定顶部](#4滚动时固定顶部)
5. [懒加载](#5懒加载)
6. [预加载](#6预加载)
7. [下拉刷新](#7下拉刷新)
8. [上拉加载](#8上拉加载)
9. [日历](#9日历)

## 列表

### 1.EventEmitter

难度：⭐️

介绍：一个简单的 EventEmitter，可在浏览器中使用，帮助你实现事件的订阅和发布。

地址：[https://github.com/mqyqingfeng/EventEmitter
](https://github.com/mqyqingfeng/EventEmitter)

备注：**首要阅读**，负责组件的事件系统。

参考：[EventEmitter.js](https://github.com/Olical/EventEmitter)

### 2.返回顶部

难度：⭐️

介绍：原生 JavaScript 实现的回到顶部库，适应 PC 和移动，兼容到 IE7+。

地址：[https://github.com/mqyqingfeng/ScrollToTop
](https://github.com/mqyqingfeng/ScrollToTop)

Demo：[https://mqyqingfeng.github.io/ScrollToTop/](https://mqyqingfeng.github.io/ScrollToTop/)

预览：

![回到顶部](https://raw.githubusercontent.com/mqyqingfeng/Wheels/master/images/ScrollToTop.gif)

### 3.顶部进度条

难度：⭐️

介绍：仿阮一峰老师的《ECMAScript 6 入门》的顶部进度条。

地址：[https://github.com/mqyqingfeng/progress-indicator
](https://github.com/mqyqingfeng/progress-indicator)

Demo：[https://mqyqingfeng.github.io/progress-indicator/](https://mqyqingfeng.github.io/progress-indicator/)

预览：

![进度条](https://raw.githubusercontent.com/mqyqingfeng/Wheels/master/images/progress-indicator.gif)

### 4.滚动时固定顶部

难度：⭐️

介绍：原生 JavaScript 实现的固定在顶部效果，兼容到 IE7+。

地址：[https://github.com/mqyqingfeng/Sticky
](https://github.com/mqyqingfeng/Sticky)

Demo：[https://mqyqingfeng.github.io/Sticky/](https://mqyqingfeng.github.io/Sticky/)

预览：

![滚动时固定顶部](https://raw.githubusercontent.com/mqyqingfeng/Wheels/master/images/Sticky.gif)

### 5.懒加载

难度：⭐️

介绍：原生 JavaScript 懒加载库，兼容到 IE8+。

地址：[https://github.com/mqyqingfeng/LazyLoad
](https://github.com/mqyqingfeng/LazyLoad)

Demo：[https://mqyqingfeng.github.io/LazyLoad/](https://mqyqingfeng.github.io/LazyLoad/)

预览：

![懒加载](https://raw.githubusercontent.com/mqyqingfeng/Wheels/master/images/LazyLoad.gif)

参考：[Echo.js](https://github.com/toddmotto/echo)

### 6.预加载

难度：⭐️

介绍：原生 JavaScript 实现的预加载库，兼容到 IE7+。

地址：[https://github.com/mqyqingfeng/Preload
](https://github.com/mqyqingfeng/Preload)

Demo：[https://mqyqingfeng.github.io/Preload/](https://mqyqingfeng.github.io/Preload/)

预览：

![预加载](https://raw.githubusercontent.com/mqyqingfeng/Wheels/master/images/Preload.gif)

### 7.下拉刷新

难度：⭐️⭐️

介绍：移动端下拉刷新库，原生 JavaScript 实现。

地址：[https://github.com/mqyqingfeng/pulltorefresh
](https://github.com/mqyqingfeng/pulltorefresh)

Demo：[https://mqyqingfeng.github.io/pulltorefresh/](https://mqyqingfeng.github.io/pulltorefresh/)

预览：

![下拉刷新](https://raw.githubusercontent.com/mqyqingfeng/Wheels/master/images/pulltorefresh.gif)

参考：[pulltorefresh.js](https://github.com/BoxFactura/pulltorefresh.js)

### 8.上拉加载

难度：⭐️

介绍：移动端上拉加载库，原生 JavaScript 实现。

地址：[https://github.com/mqyqingfeng/pulltoload
](https://github.com/mqyqingfeng/pulltoload)

Demo：[https://mqyqingfeng.github.io/pulltoload/](https://mqyqingfeng.github.io/pulltoload/)

预览：

![下拉刷新](https://raw.githubusercontent.com/mqyqingfeng/Wheels/master/images/pulltoload.gif)

## 使用方法

打开地址，拷贝 clone 地址， git clone 到本地后，打开 docs/index.html 即可

### 9.日历

难度：⭐️⭐️

介绍：原生 JavaScript 实现的日历📅，兼容没试 -_-|||。

作者：[Haner](https://github.com/haner199401)

地址：[https://github.com/haner199401/calendar](https://github.com/haner199401/calendar)

Demo：[https://haner199401.github.io/calendar/](https://haner199401.github.io/calendar/)

预览：

![日历](https://raw.githubusercontent.com/haner199401/haner199401.github.io/develop/images/my-calendar.gif)

### 10.打字效果

难度：⭐️

介绍：原生 JavaScript 实现的自动打字效果。

地址：[https://github.com/mqyqingfeng/AutoType](https://github.com/mqyqingfeng/AutoType)

Demo：[https://mqyqingfeng.github.io/AutoType/](https://mqyqingfeng.github.io/AutoType/)

预览：

![打字](https://raw.githubusercontent.com/mqyqingfeng/AutoType/master/demonstration.gif)

## 说明

如果有对实现方式的疑问或者发现错误，可以在相应库的 issues 进行提问或勘误。

如果对你有所帮助，欢迎 star，对作者也是一种鼓励。

## 更多轮子

1. 瀑布流
2. 移动端手势库
3. 拖动
4. 自适应的输入框
