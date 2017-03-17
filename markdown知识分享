


# Markdown使用精简介绍
## 概述

Markdown 的目标是实现「易读易写」。

>一份使用 Markdown 格式撰写的文档应该可以直接以纯文本发布，并且看起来不会像是由许多标签或是格式指令所构成。

## 使用 Markdown 的优点

* 专注你的文字内容而不是排版样式，安心写作。
* 轻松的导出 HTML、PDF 和本身的 .md 文件。
* 纯文本内容，兼容所有的文本编辑器与字处理软件。
* 随时修改你的文章版本，不必像字处理软件生成若干文件版本导致混乱。
* 可读、直观、学习成本低。
* 可使用的工具众多。
* 容易使用版本控制

## 使用Markdown编写的文档看上去是这个样子
![avatar](https://pic4.zhimg.com/d5422732754a69792853b6028f2a75df_b.png)

![avatar](https://pic4.zhimg.com/913472cc774261a1afb2147a6c3fc85f_b.png)

![avatar](https://pic3.zhimg.com/9b86b66fd57bc60d2223f7fa1a4d27c6_b.png)

![avatar](http://upload-images.jianshu.io/upload_images/1779314-a59af5ad9c40
3d2d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## Markdown简要语法规则
### 标题
在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 # 号即可。
```
#一级标题
##二级标题
###三级标题
```

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

### 区块引用

看起开就像这样
>这里是引用的内容

```
>这里是引用的内容
```
***
并且支持多行的引用
>Material Design 是专为设计适用于多个平台和设备的视觉、运动与互动效果而制定的综合指南。 如果
要在您的 Android 应用中使用 Material Design，请遵循Material Design 规范内所述的指导方针
，并使用 Android 5.0（API 级别 21）所提供的新组件与功能。

```
>Material Design 是专为设计适用于多个平台和设备的视觉、运动与互动效果而制定的综合指南。
 如果要在您的 Android 应用中使用 Material Design，请遵循Material Design 规范内所
 述的指导方针，并使用 Android 5.0（API 级别 21）所提供的新组件与功能。
```
***
或者嵌套引用
>CardView 扩展 FrameLayout 类并让您能够显示卡片内的信息，这些信息在整个平台中拥有一致的呈现
方式。CardView 小部件可拥有阴影和圆角。如果要使用阴影创建卡片，请使用
card_view:cardElevation 属性。CardView 在 Android 5.0（API 级别 21）及更高版本中使用
真实高度与动态阴影，而在早期的 Android 版本中则返回编程阴影实现。如需了解详细信息，请参阅保持
兼容性使用这些属性自定义 CardView 小部件的外观：
>>如果要在您的布局中设置圆角半径，请使用 card_view:cardCornerRadius 属性。
>>>下列代码示例将展示如何将 CardView 小部件包括在您的布局中

```
或者嵌套引用
>CardView 扩展 FrameLayout 类并让您能够显示卡片内的信息，这些信息在整个平台中拥有一致的呈现方式。
CardView 小部件可拥有阴影和圆角。如果要使用阴影创建卡片，请使用 card_view:cardElevation 属性。
CardView 在 Android 5.0（API 级别 21）及更高版本中使用真实高度与动态阴影，而在早期的 Android
版本中则返回编程阴影实现。如需了解详细信息，请参阅保持兼容性使用这些属性自定义 CardView 小部件的外观：
>>如果要在您的布局中设置圆角半径，请使用 card_view:cardCornerRadius 属性。
>>>下列代码示例将展示如何将 CardView 小部件包括在您的布局中
```

### 列表
Markdown 支持有序列表和无序列表。
无序列表
*   Red
*   Green
*   Blue

```
*   Red
*   Green
*   Blue
```
```
+   Red
+   Green
+   Blue
```
```
-   Red
-   Green
-   Blue
```
效果相同
* * *

有序列表

1.  Bird
2.  McHale
3.  Parish

```
1.  Bird
2.  McHale
3.  Parish
```
或者
```
1.  Bird
1.  McHale
1.  Parish
```
或者
```
3. Bird
1. McHale
8. Parish
```
你可以完全不用在意数字的正确性。
***
*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.

多行的列表自动缩进

### 代码区块
    这是一个代码区块。

### 分隔线
---
```
***
或者
---
```
### 链接
This is [an example](http://example.com/ "Title") inline link.
```
This is [an example](http://example.com/ "Title") inline link.
```


```html
<p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
title attribute.</p>
```

[This link](http://example.net/) has no title attribute.


```
[This link](http://example.net/) has no title attribute.
```
### 强调

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

```
*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

```
强调也可以直接插在文字中间：

un*frigging*believable
```
un*frigging*believable
```
### 代码
行内代码：
Use the `printf()` function.

区域代码：
区域文档支持语法高亮

##### java代码

```java
public static void main(String arg){
  System.out.println("Hello World");
}
```
##### CSS代码
```css
body  {
     font-family: Verdana, sans-serif;
     }

td, ul, ol, ul, li, dl, dt, dd  {
     font-family: Verdana, sans-serif;
     }

p  {
     font-family: Times, "Times New Roman", serif;
     }
```
##### javascript代码

```javascript
/**
* nth element in the fibonacci series.
* @param n >= 0
* @return the nth element, >= 0.
*/
function fib(n) {
  var a = 1, b = 1;
  var tmp;
  while (--n >= 0) {
    tmp = a;
    a += b;
    b = tmp;
  }
  return a;
}

document.write(fib(10));
```


### 图片
可以使用本机上的图片文件，或者引用网络的地址


![avatar](http://img1.imgtn.bdimg.com/it/u=2372297862,56418493&fm=23&gp=0.jpg)
### 自动链接
<http://example.com/>

### 其他功能
~~这是一段错误的文本。~~


HTML标签
<table>
    <tr>
        <th rowspan="2">值班人员</th>
        <th>星期一</th>
        <th>星期二</th>
        <th>星期三</th>
    </tr>
    <tr>
        <td>李强</td>
        <td>张明</td>
        <td>王平</td>
    </tr>
</table>
todo列表
- [ ] **七月旅行准备**
    - [ ] 准备邮轮上需要携带的物品
    - [ ] 浏览日本免税店的物品
    - [x] 购买蓝宝石公主号七月一日的船票

Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：
```
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
```



## Markdown编辑工具
工具介绍网站：
https://sspai.com/post/27792



并且Markdown被很多的网络编辑器，博客，网络日志支持
简书，网易云笔记，印象笔记都能够使用Markdown格式来进行编辑。


Atom：
https://atom.io
Atom工具介绍

<http://www.jianshu.com/p/dd97cbb3c22d>
<https://www.v2ex.com/t/249859>

## 将我的文档跟踪版本，并且发布发博客
Markdown非常容易进行版本管理并且容易被发布，以便于社区使用与修改
使用github发布markdown文档
<https://github.com/AU4U/My-Design-Patterns-Notes>


## Markdown相关资源
