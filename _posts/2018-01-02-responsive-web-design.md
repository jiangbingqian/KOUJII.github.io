---
layout: post
title: "响应式设计"
date: 2018-01-02 01:32:20 +0300
excerpt: "关于媒体查询|弹性布局|弹性图片的知识总结"
tags: [rwd-note]
comments: true
rwd-note: true
---

<h2 id="media">媒体查询</h2>
>CSS3媒体查询可以让我们针对特定的设备能力或条件为网页应用特定的CSS样式。
使用 `@media` 查询,可以针对不同的屏幕尺寸设置不同的样式

#### 语法
```
@media mediatype and|not|only (media feature) {
    CSS-Code;
}
```


**Try**:浏览器览器窗口小于 500px, 背景将变为浅蓝色

```
@media only screen and (max-width: 500px) {
    body {
        background-color: lightblue;
    }
}
```

#### 媒体功能

值|描述|
|:--------|:-------:|
aspect-ratio | 定义输出设备中的页面可见区域宽度与高度的比率
color | 定义输出设备每一组彩色原件的个数。如果不是彩色设备，则值等于0
color-index | 定义在输出设备的彩色查询表中的条目数。如果没有使用彩色查询表，则值等于0
device-aspect-ratio | 定义输出设备的屏幕可见宽度与高度的比率。
device-height | 定义输出设备的屏幕可见高度。
device-width | 定义输出设备的屏幕可见宽度。
grid | 用来查询输出设备是否使用栅格或点阵。
height | 定义输出设备中的页面可见区域高度。
max-aspect-ratio | 定义输出设备的屏幕可见宽度与高度的最大比率。
max-color | 定义输出设备每一组彩色原件的最大个数。
max-color-index	| 定义在输出设备的彩色查询表中的最大条目数。
max-device-aspect-ratio|定义输出设备的屏幕可见宽度与高度的最大比率。
max-device-height | 定义输出设备的屏幕可见的最大高度。
max-device-width | 定义输出设备的屏幕最大可见宽度。
max-height | 定义输出设备中的页面最大可见区域高度。
max-monochrome | 定义在一个单色框架缓冲区中每像素包含的最大单色原件个数。
max-resolution | 定义设备的最大分辨率。
max-width | 定义输出设备中的页面最大可见区域宽度。
min-aspect-ratio | 定义输出设备中的页面可见区域宽度与高度的最小比率。
min-color | 定义输出设备每一组彩色原件的最小个数。
min-color-index | 定义在输出设备的彩色查询表中的最小条目数。
min-device-aspect-ratio	| 定义输出设备的屏幕可见宽度与高度的最小比率。
min-device-width | 定义输出设备的屏幕最小可见宽度。
min-device-height | 定义输出设备的屏幕的最小可见高度。
min-height | 定义输出设备中的页面最小可见区域高度。
min-monochrome | 定义在一个单色框架缓冲区中每像素包含的最小单色原件个数
min-resolution | 定义设备的最小分辨率。
min-width | 定义输出设备中的页面最小可见区域宽度。
monochrome | 定义在一个单色框架缓冲区中每像素包含的单色原件个数。如果不是单色设备，则值等于0
orientation | 定义输出设备中的页面可见区域高度是否大于或等于宽度。
resolution | 定义设备的分辨率。如：96dpi, 300dpi, 118dpcm
scan | 定义电视类设备的扫描工序。
width | 定义输出设备中的页面可见区域宽度
|=====
{: rules="groups"}

---


<h2 id="flexbox">弹性布局</h2>
>弹性比例大小：结果 = 目标/上下文

**使用**`flexbox`

#### 语法：[优秀的教程](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)

---


<h2 id="image">弹性图片</h2>
[简书](https://www.jianshu.com/p/16e2524402b5)在此方面有具体的教程说明





