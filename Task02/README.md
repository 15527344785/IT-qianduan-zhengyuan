# 任务3:魔镜介绍页——一个最简单的移动端页面

需要掌握ps切图技能

在实践过程中遇到了一些难点：

首先我们在使用

background：url 进行图片的显示
# 通常我们都会遇到图片不显示的问题，一方面我们用的都是css文件夹，放一个css的样式，通过外部进行链接样式，如果images文件夹不再css文件夹里面，就会出现图片不显示的问题。

# 图片不显示，还有一个原因在于我们没有对放置图片的div元素给一个height属性

background-size来调整图片的大小

整个页面都是采用的rem单位，移动端界面，不能使用px值。

# rem：是css3新增的一个相对单位

用到知识点还有浮动：float

# 自适应网页一般
<meta name="viewport" content="width=device-width, initial-scale=1" />  

viewport是网页默认的宽度和高度，
上面这行代码的意思是：网页宽度默认等于屏幕宽度（width=device-width），
原始缩放比例（initial-scale=1）为1.0，即网页初始大小占屏幕面积的100%。

所有主流浏览器都支持这个设置，包括IE9。对于那些老式浏览器（主要是IE6、7、8），需要使用css3-mediaqueries.js

<!--[if lt IE 9]>  
　　　　<script src="http://css3-mediaqueries-js.googlecode.com/svn/trunk/css3-mediaqueries.js"></script>  
<![endif]-->  

