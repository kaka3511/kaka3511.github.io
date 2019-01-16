---
layout:     post
title:      自己的第一篇MarkDown文章
subtitle:   第一篇MarkDown文章
date:       2019-01-16
author:     BY
header-img: img/2016-04-12 012253.jpg
catalog: true
tags: -MarkDown
---

> 
> # MarkDown第一篇日记 #


![](http://img3.laibafile.cn/p/m/304704726.jpg.com/)

----------

###MarkDown简介
Markdown是一种纯文本格式的标记语言。通过简单的标记语法，它可以使普通文本内容具有一定的格式。

**优点**：
<font color=green size=3>
1、因为是纯文本，所以只要支持Markdown的地方都能获得一样的编辑效果，可以让作者摆脱排版的困扰，专心写作。

2、操作简单。比如:WYSIWYG编辑时标记个标题，先选中内容，再点击导航栏的标题按钮，选择几级标题。要三个步骤。而Markdown只需要在标题内容前加#即可
</font>

**缺点**：
<font color=red size=3>
1、需要记一些语法（当然，是很简单。五分钟学会。

2、有些平台不支持Markdown编辑模式。
</font>


----------

#一、标题
在想要设置为标题的文字前面加#来表示
一个#是一级标题，二个#是二级标题，以此类推。支持六级标题。

注：标准语法一般在#后跟个空格再写文字，貌似简书不加空格也行。

示例：

![](http://img3.laibafile.cn/p/m/304705418.png.com/)

效果如下：
# 这是一级标题
## 这是二级标题
### 这是三级标题
#### 这是四级标题
##### 这是五级标题
###### 这是六级标题

----------

#二、字体

1. 加粗:要加粗的文字左右分别用两个*号包起来

2. 斜体:要倾斜的文字左右分别用一个*号包起来

3. 斜体加粗:要倾斜和加粗的文字左右分别用三个*号包起来

4. 删除线:要加删除线的文字左右分别用两个~~号包起来


示例：

![](http://img3.laibafile.cn/p/m/304705663.png.com/)

效果如下：

**这是加粗的文字**

*这是倾斜的文字*`

***这是斜体加粗的文字***

<del> 这是加删除线的文字</del>

----------
#三、引用
在引用的文字前加>即可。引用也可以嵌套，如加两个>>三个>>>
n个...
貌似可以一直加下去，但没神马卵用

示例：


![](http://img3.laibafile.cn/p/m/304705839.png.com/)

效果如下：
>这是引用的内容
>>这是引用的内容
>>>>>>>>>>这是引用的内容
>

----------
#四、分割线
三个或者三个以上的 - 或者 * 都可以。

示例：

![](http://img3.laibafile.cn/p/m/304705962.png.com/)

效果如下：
可以看到，显示效果是一样的。

![](http://img3.laibafile.cn/p/m/304706205.png.com/)


----------
#五、图片

语法：
![](http://img3.laibafile.cn/p/m/304706297.png.com/)
示例：
![](http://img3.laibafile.cn/p/m/304706339.png.com/)
效果如下：

![blockchain](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg)

----------
#六、超链接
语法：
![](http://img3.laibafile.cn/p/m/304706440.png.com/)
示例：
![](http://img3.laibafile.cn/p/m/304706441.png.com/)
效果如下：

[简书](http://jianshu.com)
[百度](http://baidu.com)

注：Markdown本身语法不支持链接在新页面中打开，如果想要在新页面中打开的话可以用html语言的a标签代替。(target="_blank")

----------

#七、列表
-无序列表
   
语法：

无序列表用 - + * 任何一种都可以
![](http://img3.laibafile.cn/p/m/304706659.png.com/)
效果如下：
·列表内容
·列表内容
·列表内容

-有序列表

语法：

数字加点
![](http://img3.laibafile.cn/p/m/304706661.png.com/)
效果如下：

1. 列表内容
2. 列表内容
3. 列表内容

-列表嵌套	

上一级和下一级之间敲三个空格即可
![](http://img3.laibafile.cn/p/m/304706664.png.com/)

----------

#八、表格
语法：
![](http://img3.laibafile.cn/p/m/304706955.png.com/)
示例：
![](http://img3.laibafile.cn/p/m/304706956.png.com/)
效果如下：
![](http://img3.laibafile.cn/p/m/304707018.png.com/)

----------
#九、代码
语法：

单行代码：代码之间分别用一个反引号包起来
