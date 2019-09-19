---
title: 第一篇博客
---
这篇博客主要用来记录markdown语法，并对各种markdown文档元素进行预览。

# 一级标题：# 文本

## 二级标题： ## 文本

### 三级标题：### 文本

#### 四级标题：#### 文本

##### 五级标题：##### 文本

###### 六级标题：###### 文本

正文长我这样，直接写文本就是正文

*想要斜体用一个\*号括起来*

**想要粗体用两个\*号括起来**

***想要斜体还想要粗体用三个\*号括起来***

~~删除线用两个波浪号包起来~~

>第一级引用内容利用一个\>表示
>>第二级引用就是两个\>,以此类推
>>>>>>>>>所以可以这么皮一下

***
下面是六亲不认的分割线，用三个或者三个以上的-或者*都可以，但是三个-需要和文本隔开一行，我也不知道为什么：

---

```
This is a piece of code
代码块要用连续的三个\`包起来，还可以指定代码的语言
```
``` html
<div>这是个html容器</div>
```

这是个链接: [baidu](https://baidu.com/)，语法如下：
```
[baidu](https://baidu.com/)
```

图片：
```
![图片alt](图片地址 ''图片title'')

图片alt就是显示在图片下面的文字，相当于对图片内容的解释。
图片title是图片的标题，当鼠标移到图片上时显示的内容。title可加可不加
```
![我举个栗子](https://github.com/GreatHong/GreatHong.github.io/blob/hexo/source/images/example.jpg?raw=true '举个栗子')

无序的列表可以用-+*任意一个作为开头，和内容之间要有空格：

- 第一个
+ 第二个
* 第三个
  
有序列表要用数字加.，也要用空格分开，虽然有些显示上没有区别，仔细看是会有自动的缩进：

1. 第一个
2. 第二个
    - 第二级
3. 第三个

嵌套的列表上级和下级之间用三个空格隔开

表格的不同列用|分割，表头用-和表分开：
```
姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟
```
效果：

姓名|技能|排行
--|:--:|--:
刘备|哭|大哥
关羽|打|二哥
张飞|骂|三弟