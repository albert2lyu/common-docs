# 浏览器-DOM-javascript

DOM不属于javascript, DOM的接口由浏览器实现提供.

浏览器将网页抽象成DOM,方便解析处理.

javascript只是支持你操作DOM的接口.

DOM跨平台,与具体编程语言无关.

> DOM核心: 
文档对象模型（DOM）是用来表达HTML，XHTML及XML文档中的对象或与其进行交互的约定，它是跨平台的，并且与编程语言无关。通过调用DOM树上对象的方法可以操纵这些对象。文档对象模型核心是由W3C进行标准化的，它将HTML和XML文档抽象成对象，并在其上定义接口以及操纵这些对象的机制，这些定义都是与编程语言无关的。
* DOM核心中定义了文档结构，树模型，以及DOM事件架构，包括：Node， Element， DocumentFragment， Document， DOMImplementation， Event， EventTarget等。
* DOM事件中包括DOM事件架构不太严格的定义以及一些特殊事件。
* DOM 元素遍历 以及 DOM Range 对象等其它内容。
从ECMAScript的角度来看，DOM规范中定义的对象被称作“宿主对象”。
https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/JavaScript_technologies_overview

[从Chrome源码看浏览器如何构建DOM树](https://zhuanlan.zhihu.com/p/24911872)

