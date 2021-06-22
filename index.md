@[TOC](HTML学习总结)

# HTML

HTML是超文本标记语言（HyperText Markup Language）的缩写，是为“网页创建和其它可在网页浏览器中看到的信息”设计的一种标记语言。
HTML 不是一门编程语言，而是一种用于定义内容结构的标记语言。
##  HTML文档结构
HTML 使用"标记"（markup）来注明文本、图片和其他内容，以便于在浏览器中显示。HTML 标记包含一些规定的"元素"如 <head>，<title>，<body>，<header>，<footer>，<article>，<section>，<p>，<div>，<span>，<img>，<aside>，<audio>，<canvas>，<datalist>，<details>，<embed>，<nav>，<output>，<progress>，<video> 等等。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210601081035730.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyOTg1MTc5,size_16,color_FFFFFF,t_70)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210601081227277.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyOTg1MTc5,size_16,color_FFFFFF,t_70)



##  HTML元素
html文档由HTML元素定义
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021060108131621.png)
HTML 元素以开始标签起始
HTML 元素以结束标签终止
元素的内容是开始标签与结束标签之间的内容
某些 HTML 元素具有空内容（empty content）
空元素在开始标签中进行关闭（以开始标签的结束而结束）
大多数 HTML 元素可拥有属性

##  超链接
没有超链接就没有万维网（World Wide Web）。基本上，我们可以把任何东西加上超链接，不过常用的是文本、图片等。

超链接语法

```c
<a href="https://www.baidu.com/" target="_blank">百度一下</a>
```

说明：

href即为要跳转去的地址 URL（Uniform Resorce Locator)
target属性为_blank表示在新的页面打开超链接（默认是在当前页面打开即_self）
超链接标签包含的内容（当前为文字"百度一下"）即为显示在页面上供用户点击的

##  图片及文件路径img

在页面插入一张图片如下：

```bash
<img src="https://mdbootstrap.com/img/logo/mdb192x192.jpg" alt="MDB Logo" width="200" height="200">
```

<img src="https://mdbootstrap.com/img/logo/mdb192x192.jpg" alt="MDB Logo" width="200" height="200">
说明：

src属性为要显示图片文件的位置 URL，即图片文件的路径
alt属性当获取图片出现问题时显示的文字（占位符）
可为图片指定高宽度，但不建议（可能导致图片变形）
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210601081825159.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQyOTg1MTc5,size_16,color_FFFFFF,t_70)

HTML作为web技术基础，相对比较简单，但是缺少css等其他工具的辅助，仅仅使用HTML的网页比较缺乏美感，仍需要继续学习
