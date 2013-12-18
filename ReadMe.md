
ieBetter.js
================
It's created for IE6-IE8.


Why need this?
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
• 选择器相关API<br>
*.querySelector<br>
*.querySelectorAll<br>
*.getElementsByClassName<br><br>
• 事件相关API<br>
*.addEventListener<br>
*.removeEventListener<br>
*.dispatchEvent<br>
document.createEvent<br>
init[|Mouse|UI]Event<br>
input<br>
window.onhashchange<br><br>
• DOM特性相关API<br>
window.getComputedStyle<br><br>
• ES5 Object扩展<br>
Object.create<br>
Object.keys<br>
• Date对象<br>
Date.now<br><br>
• ES5 Function扩展<br>
Function.bind<br><br>
• ES5 String扩展<br>
String.trim<br><br>
• ES5 数组方法扩展<br>
Array.isArray<br>
Array.forEach<br>
Array.map<br>
Array.filter<br>
Array.some<br>
Array.every<br>
Array.indexOf<br>
Array.lastIndexOf<br>
Array.reduce<br>
Array.reduceRight

You can visit API document to get more infomation: [http://rawgithub.com/zhangxinxu/ieBetter/master/index.html](http://rawgithub.com/zhangxinxu/ieBetter/master/index.html)

Still, you can [visit here](http://www.zhangxinxu.com/wordpress/?p=3835) to some other information.


License
-------------------
[The MIT License](https://github.com/zhangxinxu/ieBetter/blob/master/LICENSE.md)




