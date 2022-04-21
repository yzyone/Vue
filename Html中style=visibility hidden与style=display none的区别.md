# Html style="visibility:hidden"与style="display:none"的区别 #

style="visibility:hidden": 使对象在网页上隐藏,但该对象在网页上所占的空间没有改变.

style="display:none": 使对象在网页上彻底消失,不为被隐藏的对象保留物理空间.

例子:

```
<html>
  <head>
  <title>style="visibility:hidden"与style="display:none"的区别</title>
  </head>
 
  <body>
    <span style="visibility:hidden; background-color:Blue">隐藏区域</span><span style="background-color:Green">显示区域</span>
    <span style="display:none; background-color:Blue">隐藏区域</span><span style="background-color:Green">显示区域</span><br/>
  </body>
</html>
```
