---
layout: post
title: "Markdown语法介绍"
date:   2016-05-17 13:40:07 +0800
tag: "工欲善其事，必先利其器"
---
## markdown使用指北

### 标题
***
{% highlight markdown %}
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
{% endhighlight %}

### 列表
***
有序的列表需要在文字前加“1.”。
{% highlight markdown %}
1. 人间大炮一级准备
2. 人间大炮二级准备
3. 人间大炮发射
{% endhighlight %}
如果是数字开头的文字，可以这样写1988\. 内容
无序的列表只需要在文字前加“-”或者“+”或者“*”即可。
{% highlight markdown %}
- 砰
- 砰
- 砰
{% endhighlight %}

### 链接和图片
***
插入链接
{% highlight markdown %}
[文字](地址)
{% endhighlight %}
如果是同主机的资源，可用相对路径。
插入图片
{% highlight markdown %}
![](地址)
{% endhighlight %}
参考式链接可以用[文字][标识]，在别的地方[标识]： http://.. "title"(可选)

### 引用
***
插入引用使用“>”
{% highlight markdown %}
> 孔子日。。。
{% endhighlight %}

### 粗体和斜体
***
{% highlight markdown %}
** 我是粗体 **
* 我是斜体 *
{% endhighlight %}

### 表格
***
{% highlight markdown %}
| name | age | score |
|------|:---:|------:|
| Jack | 18  |   11  |
| Jack | 19  |   60  |
| Jack | 20  |   99  |
{% endhighlight %}
效果

| name | age | score |
|------|:---:|------:|
| Jack | 18  |   11  |
| Jack | 19  |   60  |
| Jack | 20  |   99  |

### 插入代码
***
- 缩进4个空格或是1个制表符
- 行内加入代码，使用反引号’’包起来。

### 注意
***

* 大多数符号后面需要空一个空白字符。
* markdown语法字符加\可以输出成正常字符。
* 需要换行需要在末尾加入两个以上空格，再回车。
