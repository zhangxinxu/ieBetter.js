
ieBetter
================
It's created for IE6-IE8.


why need this?
-----------------
Modern browser is so powerfull. For some project, this is no any reason to include a JavaScript library. For example, jQuery.

So, what we need is just a file of JavaScript witch is created only for IE6-IE8, and the use of this file is that it make IE6-IE8 like a modern browser(Chrome, IE9+, ...)

How to use?
----------------
Simplely, include 'ieBetter.js', then just use APIs as in modern browser. For example, you can use <code>document.querySelector</code> to select the DOM element, and so on. The APIs that you can use see below.

<pre>document.querySelector("#id");</pre>

APIs and Demos
------------------
So far, the APIs that has supported are:
• 选择器相关API
*.querySelector
*.querySelectorAll
*.getElementsByClassName
• 事件相关API
*.addEventListener
*.removeEventListener
*.dispatchEvent
document.createEvent
init[|Mouse|UI]Event
input
window.onhashchange
• DOM特性相关API
window.getComputedStyle
• ES5 Object扩展
Object.create
Object.keys
• Date对象
Date.now
• ES5 Function扩展
Function.bind
• ES5 String扩展
String.trim
• ES5 数组方法扩展
Array.isArray
Array.forEach
Array.map
Array.filter
Array.some
Array.every
Array.indexOf
Array.lastIndexOf
Array.reduce
Array.reduceRight

You can visit API document to get more infomation: [http://rawgithub.com/zhangxinxu/ieBetter/master/index.html](http://rawgithub.com/zhangxinxu/ieBetter/master/index.html)

Still, you can [visit here](http://www.zhangxinxu.com/wordpress/?p=3835) to some other information.


License
-------------------
[The MIT License](https://github.com/zhangxinxu/powerSwitch/blob/master/LICENSE.md)




