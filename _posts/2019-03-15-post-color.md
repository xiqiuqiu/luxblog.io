---
layout:     post
title:      "【设计】设计系统梳理--颜色篇"
subtitle:   "该写写老本行了"
date:       2019-03-15
author:     "lux"
header-img: "img/post-bg-color.png"
tags:
    - 设计
    - 记录

---

> 写博客已经好一会了，但是就是没写过设计有关的内容；这怎么行，老本行果断不能丢，所以接下来的内容会以设计相关知识为主，借此机会正好也重新理理自己的脑子🧠。


## 颜色篇

颜色通常应用于元素，文本，按钮和边框的背景。
* 背景颜色
* 主题/辅助色
* 文字颜色
* 功能色
* 边框颜色

### 背景颜色
---
背景颜色最常用用于大块内容或颜色的区域。选择背景颜色时，请确保前景色对比度[达到AA级](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html)的最低WCAG可访问性等级。满足这些标准可确保包括视障群体在内的任何人及不同种类的设备都可访问内容。

由于背景颜色使用面积比较大，常见的为明度稍高的灰色，白色，这类颜色往往有很好的可用性和延展性，是产品设计中的首选。纯色因为亮度太高，在一些特定场景下，如：手机端长时间观看或夜间使用都会带来不好的体验，所以建议加入适当灰色中和。

以下是我经常用做背景色的一些颜色及效果：

#### 灰色
中度灰 ```#f6f8fa```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a6x0srsj208w03w3y9.jpg)

深灰色 ```#24292e```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a770tsqj208w03w3y9.jpg)

亮灰色 ```#fafbfc```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a6xctpej208w03w3y9.jpg)

#### 蓝色
蓝 ```#0366d6```  

![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a779wl5j208w03w3y9.jpg) 

亮蓝 ```#f1f8ff```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a776925j208w03w3y9.jpg)



#### 黄色
黄 ```#ffd33d```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a73fojej208w03w3y9.jpg)

亮黄 ```#fff5b1```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a73c2hvj208w03w3y9.jpg)

#### 红色
红 ```#d73a49```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a6x7p86j208w03w3y9.jpg)

亮红 ```#fffdce0```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a6x4gxrj208w03w3y9.jpg)

#### 绿色
绿 ```#28a745```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a72yraij208w03w3y9.jpg)

亮绿 ```#dcffe4```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a6xgnx4j208w03w3y9.jpg)

#### 紫色
紫 ```#6f42c1```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a7376w8j208w03w3y9.jpg)

亮紫 ```#f5f0ff```
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13a732u86j208w03w3y9.jpg)


### 主题色
---
主题色通常会选择两到三种，即1种主题色和2-3种辅助色即可。切记颜色使用不宜过多。

一般情况下，使用主题色和辅助色的同类色有助于创建和谐的色彩主题，能够在确保文本可访问的情况，将不同层级的UI元素、信息彼此区分。

要测试自己选择的颜色能否有比较好适配效果，这里可以使用google家的[color Tool](https://material.io/tools/color/#!/?view.left=0&view.right=0&primary.color=C62828)工具来实时的将颜色渲染在样机上，方便的查看颜色的适应性

![](https://ws1.sinaimg.cn/large/e66b0ffcly1g1871ip67wj20zr0l7kbe.jpg)

在无障碍选项中，可以会根据你选择的颜色生成文内容文本的可访问性情况，并给出问题提示。

![](https://ws1.sinaimg.cn/large/e66b0ffcly1g1873bwve0j20zr0l7wyq.jpg)

如果你的产品打算跟进使用```Material Design```作为设计语言，你还可以使用google家出的sketch插件[Material Theme Editor ](https://material.io/tools/theme-editor/)里面包含了设计需要的色板，Icon，控件，组件等可以非常方便的设计出符合规范的产品UI。

![](https://ws1.sinaimg.cn/large/e66b0ffcly1g187g4argtg211j0ganpf.gif)


### 文字颜色
---
文字颜色通常来区分和强调信息内容。颜色对比通过[AA级](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html)的最低WCAG可访问等级。这确保了无法看到全色谱的视障人群也能够阅读文本。
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13cjg4atcj21cr0wdn26.jpg)


### 功能色
---
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13k5v67dpj20nu0eg3yy.jpg)

功能色代表了明确的信息以及状态，比如成功，出错，失败，提醒，链接等。功能色的选择尽量遵守用户对色彩的基本认知，同时功能色尽量保持一致，不要过多的自定义干扰用户认知体验。

### 边框颜色
---
默认边框使用实心的1px边框，并使用15%的黑色。
![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13lg06oo6j20nu0egdg4.jpg)


使用提示性的边框时要注意在不同颜色背景下的显示效果，可适量增加Alpha值。用来设置Hover状态；例如，在浅色背景下可将降低边框不透明度。

同样，也可在边框中添加背景色，再加入渐进式的边框色过渡，以实现更多状态切换。

![](https://ws1.sinaimg.cn/large/e66b0ffcly1g13mczg0xnj20nu0egjro.jpg)

