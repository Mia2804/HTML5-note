# HTML5-note
HTML是超文本，不是编程语言
# 1、基础标签
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
    Mia
</body>
</html>

## 声明
<!DOCTYPE html>声明代表html5版本！ 
## <html>
<html>
</html>
所有数据都要包含在其中
  
## head
<head></head>
定义基础信息，编码格式如UTF-8，标题，文字显示形式（如en代表英文）
<title></title>
  
# 2.标签（标签的使用是成对出现的）
《b》定义加粗
《big》定义大号字体
《small》小号
<small>small</small?
 <br/>
《em》定义着重文字
《i》斜体
《strong》定义加重语气
<strong>strong</strong>
  <br/>
《sub》下标
My<sub>best</sub>Friend
     <br/>
《sup》上标
My<sub>best</sub>Friend
     <br/>
《ins》定义插入字,文字下面是有一个下划线
    <ins>ins</ins>
     <br/>
《del》定义删除字
<del>delet</delet>
     <br/>

HTML元素指的是从开始标签到结束标签所有的代码
1.h1:align对齐方式
    <h1>title_h1</h1>
    <h2>title_h1</h2>
    <h3>title_h1</h3>
    <h4>title_h1</h4>
    <h5>title_h1</h5>
    <h6>title_h1</h6>
    代表了从大到小的六个字号title
    <h1 align="right">标题居右（center）
2.body：bgcolor背景颜色(backgroung设置背景图片)
    <body bgcolor="">
3.P标签——一般代表一个段落
   <p>hello</p>
4.超链接 a标签，target指定在哪里打开链接
    <a href="https://www.github.com/Mia2804.com">Mia的家园</a>
    也可以打开本地！：<a href="news.html">打开本地news</a>
    <a href="https://www.github.com/Mia2804.com" target="">Mia的家园</a>(blank：在新标签中打开，self等等)
5.图片标签 <img>
<img src="images/html.png">
6.换行标签<br/>注意这个br后面加不加/是都可以的
这个表示 空元素在开始标签中进行关闭(空元素是没有属性的)
大多数的HTML元素是可以嵌套的如<p><a></p></a>
大多数的HTML元素可拥有属性

通用属性：
class：规定元素的类名
    <h2 class=“h2id">title_h1</h2>
id：规定元素唯一ID
    
style：规定元素的样式（如CSS样式）
    <style></style>
title：规定元素的额外信息,设置当前就是那个tab标签上的信息
# HTML样式
1. 
