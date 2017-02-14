---
title: 前端工程师手册-2017【译】
date: 2017-02-10 16:47:16
tags:
---

原文：[https://github.com/FrontendMasters/front-end-handbook-2017](https://github.com/FrontendMasters/front-end-handbook-2017)

![](http://7xnjo6.com1.z0.glb.clouddn.com/Artboard.jpg)

## 什么是前端工程师

前端工程师，也称为客户端开发，是网站或者Web应用程序生成HTML，CSS和Javascript的最佳实践，以便用户可以直接与之交互。与前端领域相关的挑战是创建网站的工具和技术，因此开发人员需要不断地了解领域的发展情况。

设计网站的目的是确保当用户打开网站时很方便的阅读和相关的内容。进一步说，用户现在使用各种各样的设备，从而迫使设计者考虑兼容大量的屏幕尺寸和分辨率，他们必须确保网站可以在不同的浏览器（跨浏览器），不同的操作系统（跨平台）和不同的设备（跨设备）上运行，这一方面开发者要好好地规划

### HTML, CSS, & JavaScript:

前端开发人员使用Web构建开发网站和应用程序技术（即HTML，CSS，DOM和JavaScript），运行在[web平台](https://en.wikipedia.org/wiki/Open_Web_Platform)或作为非Web平台环境的编译入口（即, [NativeScript](https://www.nativescript.org/)）

通常，一个人进入前端开发领域，通过学习HTML, CSS, and JS并可以运行在a web browser, headless browser, WebView，或可以运行在原生编译环境中，这四个运行时的方案如下所述

**Web Browsers**


Web浏览器是用于检索，呈现和遍历WWW上的信息的软件。

通常，浏览器运行在台式机或笔记本电脑，平板电脑或手机上，但后期
浏览器可以运行在任何设备上（即，在冰箱，在汽车等）。

最常见的网络浏览器（按照最常用的顺序显示）：

* Chrome
* Internet Explorer (注意：不是Edge，指IE 9到IE 11)
* Firefox
* Safari

**Headless Browsers**

无头浏览器是一个没有图形用户界面的Web浏览器从命令行界面以程序方式控制以用于网页的目的自动化（例如，功能测试，数据挖掘，单元测试等）。
想像一下无头的浏览器作为一个浏览器，您可以从命令行运行，可以检索和遍历web页面。

最常见的无头浏览器是：

* PhantomJS
* slimerjs
* trifleJS

**Webviews**

Webviews是在原生操作系统中的原生应用程序去运行网页。 想一想
webview就像iframe或来自嵌入在本机设备中的Web浏览器的单个选项卡
（例如，iOS，android，windows）上运行的应用程序。

最常见的webview开发解决方案是：

* Cordova (通常用于本地手机/平板电脑应用程序)
* NW.js (通常用于桌面应用程序)
* Electron (通常用于桌面应用程序)

**Native from Web Tech**

最终，从web浏览器开发中学到的知识可以被前端开发人员所使用，开发人员可以不受浏览器引擎驱动的环境制定代码，近来开发环境被设计出了一种没有web引擎的web技术（CSS和JavsScript）他可以创造原生应用程序

这些环境的一些示例是：

* NativeScript
* React Native

## Part I. 前端实践

第一部分广泛地描述了前端工程的实践。

### 前端工作职位

下面这个列表是各种前端职位的描述，最通用的标题是“前端开发者”或“前端工程师”。注意任何包含“前端”，“客户端”，“网络用户界面”，“HTML”，“CSS”或“JavaScript”通常推断一个人是否有一定程度的专业知识。

---

**前端开发人员**

通用标题，描述一个开发人员在一定程度上熟练使用HTML，
CSS，DOM和JavaScript，并在网络平台上实现这些技术。

---
**前端工程师（又叫JavaScript开发人员或全栈JavaScript开发人员）**

要求开发人员有计算机科学，工程背景，并在前端技术中使用这些技能。
这个角色通常需要具备计算机科学学位和多年的软件开发经验。当“JavaScript应用程序”包含在标题中，这将表示开发人员应该是一个拥有高级JavaScript开发，软件开发和应用程序开发技能（即有多年
构建前端应用程序的经验）。

---
**CSS / HTML开发人员**

熟练掌握HTML和CSS的开发人员，排除是否会JavaScript技术。

---
**前端Web设计师**

当标题中包含词“设计师”时，这将表示设计者将会拥有前端技能（即HTML和CSS），还有专业设计（​​视觉设计和互动设计）技能。

---
**Web /前端用户界面（又称 UI）开发人员/工程师**

当标题中包含“界面”或“UI”时，这将表示除了前端开发人员技能之外，开发人员应该具有交互设计技能，前端工程技能。

---
**移动/平板电脑前端开发人员**

当标题中包含“移动”或“平板电脑”字样时，这将表示开发人员拥有在移动或平板设备上运行开发的前端经验（在web平台上，即在浏览器中）。

---
**前端SEO专家**

当词“SEO”包括在标题中时，这将表示开发者具有制定前端技术以实现SEO战略的广泛经验。

---
**前端辅助功能**

当标题中包含“辅助功能”一词时，这将表示开发人员拥有丰富的制作前端技术支持可访问性的经验要求和标准。

---
**前端开发部署**

当词“部署”包括在作业标题中时，这将表示开发者具有有关合作的软件开发实践的丰富经验，集成，部署，自动化和测量。

---
**前端测试/ QA**

当标题中包含“测试”或“QA”一词时，这将表示开发人员具有测试和管理涉及单元的软件的丰富经验测试，功能测试，用户测试和A / B测试。


注意，如果你在职位信息中看到了“全栈”或者“Web开发工程师”，这些可能被雇主用来描述负责整个web/app开发的各个方面，即前端（可能包括设计）和后端。

## 前端开发采用的Web技术

前端开发人员使用以下核心Web技术（请考虑按照这个顺序学习它们）：


1. 统一资源定位符（又名 URLs）
2. 超文本传输协议（又名 HTTP）
3. 超文本标记语言（又名 HTML）
4. 级联样式表（又名 CSS）
5. JavaScript编程语言（又名 ECMAScript 262）
6. JavaScript对象表示法（又名 JSON）
7. 文档对象模型（又名 DOM）
8. Web API（又名 HTML5和浏览器API）
9. Web内容无障碍指南（又名 WCAG）和可访问的富Internet应用程序（又名ARIA）

**超文本标记语言（又名 HTML）**

---

``` 
超文本标记语言（通常称为HTML）是标准标记用于创建网页的语言。
Web浏览器可以读取HTML文件并进行渲染它们变成可见或可听的网页。
HTML描述了网站的结构语义上与提示一起用于呈现，使其成为标记语言，
而不是编程语言。 
```

相关的文档

* [All W3C HTML Spec](http://www.w3.org/standards/techs/html#w3c_all)
* [The elements of HTML from the Living Standard](https://html.spec.whatwg.org/multipage)
* [Global attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes)
* [HTML 5.2 from W3C](http://w3c.github.io/html/)
* [HTML attribute reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes)
* [HTML element reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
* [The HTML Syntax from the Living Standard](https://html.spec.whatwg.org/multipage/syntax.html#syntax)

**级联样式表（又名 CSS）**

---

```
级联样式表（CSS）是用于描述外观的样式表语言，是一个格式化的以标记语言编写的文档。 虽然最常用的是在HTML和XHTML中改变网页用户界面的风格
语言可以应用于任何种类的XML文档，包括纯XML，SVG和XUL。 除了HTML和JavaScript之外，CSS是大多数使用的基础技术，网站创建视觉上引人入胜的网页，Web应用程序的用户界面，和许多移动应用程序的用户界面。
```

相关的文档

* [All W3C CSS Specifications](http://www.w3.org/Style/CSS/current-work#roadmap)
* [Cascading Style Sheets Level 2 Revision 2 (CSS 2.2) Specification](https://drafts.csswg.org/css2/)
* [CSS reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
* [Selectors Level 3](http://www.w3.org/TR/css3-selectors/)

**文档对象模型（又名 DOM）**

---

```
文档对象模型（DOM）是一个跨平台的，和语言无关的，用于表示和与HTML，XHTML和XML中的对象交互约定文件。 每个文档的节点都以树结构组织，称为DOM树。 DOM树中的对象可以通过使用对象上的方法来寻址和操纵。 DOM的公共接口在其应用程序中指定编程接口（API）。
```

相关文档

* [Document Object Model (DOM) Level 3 Events Specification](https://www.w3.org/TR/DOM-Level-3-Events/)
* [DOM Living Standard](https://dom.spec.whatwg.org/)
* [W3C DOM4](https://www.w3.org/TR/2015/REC-dom-20151119/)

**JavaScript编程语言（又名 ECMAScript 262）**

---

```
JavaScript是一种高级，动态，无类型，解释性编程语言。 它已在ECMAScript语言规范中标准化。 除了HTML和CSS，它是万维网内容生产的三个基本技术之一; 大多数网站已经使用了这种语言，它不需要插件就可以被所有现代网络浏览器所支持。 JavaScript是基于原型的具有第一类函数，
使其成为一种多范式语言，支持面向对象，命令式，和函数式编程风格。 它有一个API用于处理文本，数组，日期和正则表达式，但不包括任何I / O，如网络，存储或图形设施，依赖于嵌入它们的主机环境中的这些。
```

相关链接

* [ECMAScript® 2017 Language Specification](https://tc39.github.io/ecma262/)

**Web APIs (又叫 HTML5 和他的小伙伴们？？？？)**

---

```
当使用JavaScript编写Web代码时，有很多API可用。
下面是您可以使用的所有接口（即对象类型）的列表
同时开发您的Web应用程序或网站
```
[所有接口列表](https://developer.mozilla.org/en-US/docs/Web/API)

相关链接

* [Hypertext Transfer Protocol -- HTTP/1.1](https://tools.ietf.org/html/rfc2616)
* [HTTP/2](https://http2.github.io/)


**超文本传输协议（又名 HTTP）**
---

```
统一资源定位符（URL）（也称为web地址）是对指定资源在计算机网络上的位置的资源的引用进行检索的机制。 URL是统一资源标识符（URI）的特定类型，虽然许多人可以将这两个术语互换使用。 URL是指访问指示资源的方法，URI是标识一个资源。 URL通常引用网页（http），但也用于文件传输（ftp），电子邮件（mailto），数据库访问（JDBC）和许多其他应用程序。
```

相关链接

* [Uniform Resource Locators (URL)](http://www.w3.org/Addressing/URL/url-spec.txt)
* [URL Living Standard](https://url.spec.whatwg.org/)


**JavaScript对象表示法（又名JSON）**

---

```
它是用于异步浏览器/服务器通信（AJAJ）的主要数据格式，主要替代XML（由AJAX使用）。 尽管最初派生自JavaScript脚本语言，但JSON是一种与语言无关的数据格式。 用于解析和生成JSON数据的代码很容易在许多编程语言中可用。 JSON格式最初是由Douglas Crockford指定的。 它目前由两个竞争标准，RFC 7159和ECMA-404描述。 ECMA
标准是最小的，只描述允许的语法语法，而RFC也提供一些语义和安全考虑。 JSON的官方Internet媒体类型是application / json。 JSON文件扩展名为.json。
```

[— Wikipedia](https://en.wikipedia.org/wiki/JSON)

相关链接

* [Introducing JSON](http://json.org/)
* [JSON API](http://jsonapi.org/)
* [The JSON Data Interchange Format](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf)

**Web内容无障碍指南（又名 WCAG）和可访问富Internet应用程序（又名ARIA）**

---

```
可访问性是指残疾人的产品，设备，服务或环境的设计。 可访问设计的概念确保意味着与人的辅助技术（例如，计算机屏幕阅读器）兼容的“直接访问”（即，无辅助的）和“间接访问”。
```
[— Wikipedia](https://en.wikipedia.org/wiki/Accessibility)

* [Accessible Rich Internet Applications (WAI-ARIA) Current Status](http://www.w3.org/standards/techs/aria#w3c_all)
* [Web Accessibility Initiative (WAI)](http://www.w3.org/WAI/)
* [Web Content Accessibility Guidelines (WCAG) Current Status](http://www.w3.org/standards/techs/wcag#w3c_all)








































