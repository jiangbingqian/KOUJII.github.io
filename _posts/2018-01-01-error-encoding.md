---
layout: post
title: "本地运行博客时，出现编码错误，该如何解决？"
date: 2018-01-01 20:32:20 +0300
excerpt: " Error:  incompatible character encodings: GBK and UTF-8"
tags: [rwd-note]
comments: true
rwd-note: true
---
### 错误如下：
![tu](/assets/img/error.png)
```
 Error:  incompatible character encodings: GBK and UTF-8
```
这句话的意思是：不兼容的字符编码：GBK and UTF-8

---

### 解决方法
以我的情况来看，问题出在目录名是中文
```
C:\Users\博熙\Desktop\Moon-gh-pages
```
“博熙”是中文，因此只需要把本地博客移至C盘即可，便摆脱了这个问题
![tu](/assets/img/success.png)