# 第一章 JavaScript简介
JavaScript诞生于1995 年，当时主要用于**简单的数据验证**。

**JavaScript**现已发展成为一门强大的**编程语言**。

它既**简单**（入门快），又**复杂**（学得越多，越觉得学得还不够多）

> Directory

- 1.1 JavaScript简史
- 1.2 JavaScript实现
    - 1.2.1 ECMAScript
    - 1.2.2文档对象模型（DOM）
    - 1.2.3 浏览器对象模型（BOM）
- 1.3 JavaScript版本
- [小结](#小结)

## 1.1 JavaScript简史
1995年，Netscape 公司为了服务其Netscape Navigator 2浏览器，开发了名为**LiveScript** 的脚本语言。

在Netscape Navigator 2 正式发布前夕，Netscape 搭上媒体热炒Java 的顺风车，把`LiveScript` **改名**为`JavaScript`。

JavaScript 1.0获得巨大成功，微软就在其IE 3 中加入了名为JScript 的JavaScript 实现，这意味着有了两个不同的JavaScript 版本：Netscape公司的JavaScript，以及微软公司的JScript。

**欧洲计算机制造商协会**（`ECMA`）委派各公司中的精英，完成了一种名为**ECMAScript的标准**。

## 1.2 JavaScript实现
一个完整的JavaScript实现由一下三部分组成：

- 核心（**ECMAScript**）
- 文档对象模型（**DOM**）
- 浏览器对象模型（**BOM**）

### 1.2.1 ECMAScript
ECMAScript：提供核心语言功能。

实现ECMAScript 的**宿主环境**：Web浏览器、Node（一种服务端JavaScript 平台）、Adobe Flash等。

ECMA-262第3 版标志着ECMAScript 成为了一门真正的编程语言。

### 1.2.2文档对象模型（DOM）
文档对象模型（**DOM**），全称 `Document Object Model`，是针对XML 但经过扩展用于HTML 的应用程序编程接口（API，Application Programming Interface）。

DOM把整个页面映射为一个多层节点结构。

示例HTML：
```
<html>
    <head>
        <title>Sample Page</title>
    </head>
    <body>
        <p>Hello World!</p>
    </body>
</html>
```

对应的DOM:
![图1-2](https://user-images.githubusercontent.com/13659856/35961787-d2f184b8-0ce9-11e8-9029-93afbc3d2ee9.PNG)

借助DOM 提供的API，开发人员可以轻松自如地删除、添加、替换或修改任何节点。

DOM 并不只是针对JavaScript 的，其他语言也都实现了DOM。

### 1.2.3 浏览器对象模型（BOM）
开发人员使用BOM 可以控制浏览器显示的页面以外的部分。

JavaScript中的以下扩展，一般可作为BOM的组成部分：

- 弹出新浏览器窗口的功能
- 移动、缩放和关闭浏览器窗口的功能
- 提供浏览器详细信息的 navigator 对象
- 提供浏览器所加载页面的详细信息的 location 对象
- 提供用户显示器分辨率详细信息的 screen 对象
- 对cookies 的支持
- 像XMLHttpRequest 和IE 的ActiveXObject 这样的自定义对象

## 1.3 JavaScript版本
作为Netscape“继承人”的Mozilla 公司，Mozilla 基金会继续开发JavaScript，添加新的特性、关键字和语法，JavaScript 的版本号继续递增。

目前，JavaScript 2.0 还没有目标实现。

大多数浏览器在提及对JavaScript 的支持情况时，一般都以ECMAScript 兼容性和对DOM的支持情况为准。

## 小结
JavaScript是一种专为网页交互而设计的脚本语言啊，由下列三个不同的部分组成：

- ECMAScript，由ECMA-262定义，提供核心语言功能；
- 文档对象模型（DOM），提供访问和操作网页内容的方法和接口；
- 提供与浏览器交互的方法和接口。
