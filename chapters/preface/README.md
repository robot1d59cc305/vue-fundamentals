# 前言

2011 年 Node.js 的诞生是 JavaScript 的里程碑，不仅使服务器端的 JavaScript 成为可能，也让前端开发进入了一个全新的时代。

强大和愈趋完善的工具链，使得开发者在考虑架构的时候越来越愿意把逻辑放到前端去处理和渲染，甚至达到前后端分离。

这时，以 jQuery 和 Backbone.js 为首的 MVC 设计模式让前端开发者逐渐陷入凌乱之中，由于随着前端处理的业务逻辑所占的比重越来越大，前端需要管理的状态（state）和需要处理的数据（data）会越来越多。

所幸的是，先驱者们机智地把 MVVM 设计模式引入到了 JavaScript 中，通过数据绑定（data binding），使前端开发者能有效地逃离大量的 DOM 操作，从而专注于业务逻辑和状态变化本身。

典型的 MVVM 框架/库有 [Knockout](http://knockoutjs.com/)， Google 出品的 [AngularJS](https://angularjs.org/)、从苹果公司内部脱离出来的 [EmberJS](http://emberjs.com/)、国内开发者司徒正美开发的 [Avalon](https://avalonjs.github.io/)，还有同样是国内开发者尤小右的 [Vue.js](http://vuejs.org)。本书主要讲述 Vue.js。

## 目标读者

本书面向的读者，是有意于了解如何使用 Vue.js 构建中大型 Web 应用程序的进阶开发者。

## 目标版本

本书所使用的 Vue.js 版本为 `v1.0.x`，在写这本书的时候，Vue.js 1.0.0 版本仍然处于 rc 状态，这个版本相对 `v0.12.x` 有不少的变化，但我仍然选择 `v1.0.x`，是因为我已经在生产环境中使用它。如果你在以前曾经使用过 `v0.12.x`，你会发现，这个大版本的变化是让人惊喜的。

**本书所有代码默认使用 ECMAScript 2015, 如果你仍然未开始使用，建议你[从现在开始使用](https://babeljs.io/docs/learn-es2015/)**。
