# 一、React-Native

## 1、概述

React Native (简称RN)是Facebook于2013年开源的跨平台移动应用开发框架，是Facebook早先开源的JS框架 React 在原生移动应用平台的衍生产物，目前支持iOS和安卓两大平台。RN使用Javascript语言，类似于HTML的JSX，以及CSS来开发移动应用，因此熟悉Web前端开发的技术人员只需很少的学习就可以进入移动应用开发领域。

**React Native使你能够在Javascript和React的基础上获得完全一致的开发体验，构建世界一流的原生APP。**

官网地址：https://reactnative.cn/

## 2、优缺点

### 优点

* 跨平台，支持ios和android原生APP
* 开发语言为js语言，易容上手
* 灵活度高，第三方插件全面，解决方案丰富
* 大厂支持，Facebook维护
* 易与原生集成，可调用原生ios或android组件
* 可二次封装，社区活跃度较高

### 缺点

* 需要有react基础

## 3、基于RN的优秀UI库

* react-native-elements
* NativeBase
* ant-design-mobile
* beeshell

# 二、Weex

## 1、概述

Weex 是阿里出品目前托管于apache，Weex致力于使开发者能基于通用跨平台的 Web 开发语言和开发经验，来构建 Android、iOS 和 应用。简单来说，在集成了 WeexSDK 之后，你可以使用 JavaScript 语言和前端开发经验来开发移动应用。

Weex 渲染引擎与 DSL 语法层是分开的，Weex 并不强依赖任何特定的前端框架。目前 [Vue.js](https://vuejs.org/) 和 [Rax](https://alibaba.github.io/rax/) 这两个前端框架被广泛应用于 Weex 页面开发，同时 Weex 也对这两个前端框架提供了最完善的支持。Weex 的另一个主要目标是跟进流行的 Web 开发技术并将其和原生开发的技术结合，实现开发效率和运行性能的高度统一。在开发阶段，一个 Weex 页面就像开发普通网页一样；在运行时，Weex 页面又充分利用了各种操作系统的原生组件和能力。

官网地址：https://weex.apache.org/zh/guide/introduction.html

## 2、优缺点

### 优点

- 跨平台，支持ios和android原生APP
- 开发语言为js语言，易容上手
- 易与原生集成，可调用原生ios或android组件

### 缺点

- 需要有vue或者react基础
- 阿里目前维护活跃度较低，基本趋于暂停维护状态

## 3、基于Weex的优秀UI库

- RaxUI
- Element
- iview

# 三、Flutter

## 1、概述

Flutter是谷歌的移动UI框架，可以快速在iOS和Android上构建高质量的原生用户界面。 Flutter可以与现有的代码一起工作。在全世界，Flutter正在被越来越多的开发者和组织使用，并且Flutter是完全免费、开源的。

Flutter的热重载可帮助您快速地进行测试、构建UI、添加功能并更快地修复错误。在iOS和Android模拟器或真机上可以在亚秒内重载，并且不会丢失状态。

使用Flutter内置美丽的Material Design和Cupertino（iOS风格）widget、丰富的motion API、平滑而自然的滑动效果和平台感知，为您的用户带来全新体验。

Flutter拥有丰富的工具和库，可以帮助您轻松地同时在iOS和Android系统中实现您的想法和创意。 如果您没有任何移动端开发体验，Flutter是一种轻松快捷的方式来构建漂亮的移动应用程序。 如果您是一位经验丰富的iOS或Android开发人员，则可以使用Flutter作为视图(View)层， 并可以使用已经用Java / ObjC / Swift完成的部分（Flutter支持混合开发）。

官网地址：https://flutterchina.club/

## 2、优缺点

### 优点

- 跨平台，支持ios和android原生APP
- 支持web开发
- 易与原生集成，可调用原生ios或android组件
- 性能与原始app一致，可达到游戏app性能标准
- 自带UI库，目前支持ios和安卓风格的组件非常全面

### 缺点

- dart语言，谷歌新开发语言
- 目前不够成熟，市场活跃度不高，不是主流
- 第三方插件不够全面

# 四、Taro

## 1、概述

Taro是京东出品的一套遵循 React 语法规范的多端统一开发框架。

多端统一开发框架，支持用 React 的开发方式编写一次代码，生成能运行在微信/百度/字节跳动/支付宝小程序、H5、React Native 等平台的应用

现如今市面上端的形态多种多样，Web、React-Native、微信小程序等各种端大行其道，当业务要求同时在不同的端都要求有所表现的时候，针对不同的端去编写多套代码的成本显然非常高，这时候只编写一套代码就能够适配到多端的能力就显得极为需要。

使用 **Taro**，我们可以只书写一套代码，再通过 **Taro** 的编译工具，将源代码分别编译出可以在不同端（微信/百度/支付宝/字节跳动小程序、H5、React-Native 等）运行的代码。

官网地址：https://taro.aotu.io/

## 2、优缺点

### 优点

- 跨平台，支持微信/百度/支付宝/字节跳动小程序、H5、React-Native
- 自带UI库，组件较多
- 容易上手

### 缺点

- 灵活度较差，现有组件不支持定制开发，有特殊需求需要重写
- 封装度较高，不易于扩展



# 五、Uni

## 1、概述

Uni是一个使用 [Vue.js](https://vuejs.org/) 开发**跨平台**应用的前端框架，开发者编写一套代码，可编译到iOS、Android、H5、小程序等多个平台。

官网地址：https://uniapp.dcloud.io/

## 2、优缺点

### 优点

- 跨平台，支持微信/百度/支付宝/头条、H5、IOS，Android
- 自带UI库，组件较多
- 容易上手

### 缺点

- 灵活度较差，现有组件不支持定制开发，有特殊需求需要重写

- 封装度较高，不易于扩展

- 目前社区维护，组件兼容性以及问题尚处于未知阶段


# 六、框架对比



**React Native、Weex、Flutter**

RN目前属于主流跨平台解决方案，且比较稳定，建议采用RN技术。Weex目前市场占有率较低，不建议采用。Flutter市场占有率主键上升，属于新技术，目前正式推出时间较短，RN相当于一个长大的成年人，Flutter属于刚出生的婴儿，不建议采用。



**Taro，Uni**

这两种属于基于react和vue的高度封装产品，适用于小型，短期，用户要求较低，没有定制化的项目。我们目前属于政府项目，用户需求不明确，变更较频繁，不建议采用这两种技术。

一句话，Taro和Uni属于私活神器，不建议在正式项目中采用。
