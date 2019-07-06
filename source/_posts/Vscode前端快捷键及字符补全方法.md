---
layout: posts
title: 'Vscode前端快捷键及字符补全方法'
date: 2018-11-17 14:50:57
tags:
- 
categories: 
---
1. 快捷键的使用
<!-- |快捷键|说明|
|:---:|:---:|
|Tab|补全代码|
|Ctrl+/|添加或取消注释|
|Ctrl++/-|放大或缩小|
|F12|浏览器中为调试| -->
2. 补全代码
+ 多项输入: *,例如：ul>li*5
<ul> 
<li></li> 
<li></li> 
<li></li> 
<li></li> 
<li></li> 
</ul> 
+ Class类：. , 缩写：div.top*2（Class类可以多次使用）
<div class="top"></div> 
<div class="top"></div> 

缩写：p.class1.class2.class3 
<p class="class1 class2 class3"></p> 
+ Id类：# , 缩写：div#top(一个Id类只能使用一次) 
<div id="top"></div> 

缩写：form#search.wide 
<form id="search" class="wide"></form> 
+ 自增符号：$ , 缩写：ul>li.item$*5 
<ul> 
<li class="item1"></li> 
<li class="item2"></li> 
<li class="item3"></li> 
<li class="item4"></li> 
<li class="item5"></li> 
</ul> 
+ 子元素：> , 缩写： nav>ul>li 
<nav> 
<ul> 
<li></li> 
</ul> 
</nav> 
+ 兄弟元素：+ , 缩写：div+div>p>span+em 
css 
<div></div> 
<div> 
<p><span></span><em></em></p> 
</div> 
+ 自定义属性：[] 
缩写：p[title=”Hello world”] 
css 
<p title="Hello world"></p> 

缩写：td[rowspan=2 colspan=3 title] 
css 
<td rowspan="2" colspan="3" title=""></td> 

缩写：[a=’value1’ b=”value2”](a,b为属性，value为属性值。具体使用见上面的例子) 
css 
<div a="value1" b="value2"></div> 

+ 文本：{} 
缩写：a{Click me} 
css 
<a href="">Click me</a> 
