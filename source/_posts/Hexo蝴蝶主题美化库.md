---
title: Hexo蝴蝶主题美化库
date: 2020-08-31 18:02:42
tags:
- Hexo
- Butterfly
---

前情提要:本文章的所有美化♣只能运行在🦋蝴蝶主题，如果您使用其他主题遇到问题，请不要找我!





# 添加Pace.js

本JS支持其他主题!但是添加方式可能不同

Pace.js是一种网页加载进度条，它使用ajax

官网:https://github.hubspot.com/pace/

添加方法:

在您的🦋蝴蝶主题配置文件的inject:
  head:配置处添加

``` yaml
- <script src="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/js/pace.js"></script>
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/pace.css">
```

即可，本美化库使用的是'Flash'主题

效果:

![image-20200831181148660](https://cdn.jsdelivr.net/gh/slblog-github/BlogFlies/Blog/Pic/image-20200831181148660.png)

这里使用的是官网的演示

# 更棒的字体

本字体支持其他主题!但是添加方式可能不同

该字体来自:[木槿](https://xiabor.com)的博客，本人只负责扒下给各位使用

添加方法:

在您的🦋蝴蝶主题的source/css/_third-party文件夹处的normalize.min.css添加

``` css
@font-face { font-family:MyFont;
src: url(https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/font/Font.woff2)}
body{font-family:MyFont!important;}
```

即可

效果:

![image-20200831181725985](https://cdn.jsdelivr.net/gh/slblog-github/BlogFlies/Blog/Pic/image-20200831181725985.png)

# 小巧版Aplayer

本CSS支持其他主题!但添加方式可能略有不同

添加方式:

在您的🦋蝴蝶主题的配置文件的inject:
  bottom:配置处添加

```yaml
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/aplayer.css">
```

即可

效果:

![image-20200831182238012](https://cdn.jsdelivr.net/gh/slblog-github/BlogFlies/Blog/Pic/image-20200831182238012.png)

鼠标放上后会自动跳出Cover和播放按钮，再次点击箭头后可以显示正常版吸底Aplayer

# 渐变背景

本CSS不支持其它主题!如需要请自行修改对应的CSSID

添加方式:

在您的🦋蝴蝶主题的配置文件的inject:
  head:配置处添加

``` yaml
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/banner.css">
```

即可

效果:

![image-20200831182525028](https://cdn.jsdelivr.net/gh/slblog-github/BlogFlies/Blog/Pic/image-20200831182525028.png)

# 更好看的Button

本CSS支持其它主题!但添加方式可能略有不同

在您的🦋蝴蝶主题的配置文件的inject:
  bottom:配置处添加

``` yaml
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/bf.button.css">
```

即可

效果:

![image-20200831182702467](https://cdn.jsdelivr.net/gh/slblog-github/BlogFlies/Blog/Pic/image-20200831182702467.png)

使用方法:

``` html
<a href="地址" target="_blank" rel="noopener" class="效果" data-pjax-state=""><span class="one-pan-tip one-pan-tip-mark one-pan-tip-success">文字</span></a>
```

其中效果请自行在CSS中摸索

# Font Awesome字体动画效果

本CSS支持其它主题!但添加方式可能略有不同

在您的🦋蝴蝶主题的配置文件的inject:
  head:配置处添加

``` yaml
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/font-awesome-animation.min.css">
```

即可

效果:

百度一下不就知道了吗(bushi

使用方法:

百度一下不就知道了吗(bushi

# 页脚渐变

本CSS不支持其它主题!

在您的🦋蝴蝶主题的配置文件的inject:
  head:配置处添加

``` yaml
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/footer.css">
```

即可

效果:

可以看[我的博客](https://blog.slqwq.cn)

# 想要其他效果?

本CSS部分支持其它主题!添加方法略有不同

在您的🦋蝴蝶主题的配置文件的inject:
  head:配置处添加

```yaml
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/normalize.min.css">
- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/butterfly-magic-library@1.0.0/css/main.style.css">
```

即可