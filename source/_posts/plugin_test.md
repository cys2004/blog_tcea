---
title: Hexo插件测试
cover: https://m.360buyimg.com/babel/jfs/t1/42857/33/21834/110982/6391d6a7E0f7e939b/f80ac21d616260e6.jpg
lang: zh-CN
---
一些插件的测试和模板
<!--more-->

### [APlayer](https://github.com/MoePlayer/hexo-tag-aplayer)
{% aplayer "Oz." "yama" "https://files.catbox.moe/69o4lh.mp3" "https://m.360buyimg.com/babel/jfs/t1/83885/8/23877/7843/6391dfb5E51955899/26e1ca62783eb937.jpg" "lrc:https://files.catbox.moe/kue5hc.lrc" %}
````
//Usage
{% aplayer title author url [picture_url, narrow, autoplay, width:xxx, lrc:xxx] %}

//Option
title : music title
author: music author
url: music file url
picture_url: optional, music picture url
narrow: optional, narrow style
autoplay: optional, autoplay music, not supported by mobile browsers
width:xxx: optional, prefix width:, player's width (default: 100%)
lrc:xxx: optional, prefix lrc:, LRC file url

//Example
{% aplayer "Caffeine" "Jeff Williams" "caffeine.mp3" "picture.jpg" "lrc:caffeine.txt" %}

{% aplayer "Oz." "yama" "https://files.catbox.moe/69o4lh.mp3" "https://m.360buyimg.com/babel/jfs/t1/83885/8/23877/7843/6391dfb5E51955899/26e1ca62783eb937.jpg" "lrc:https://files.catbox.moe/kue5hc.lrc" %}
````
### [DPlayer](https://github.com/MoePlayer/hexo-tag-dplayer)
{% dplayer "url=https://files.catbox.moe/yiyosy.mp4"  "pic=https://m.360buyimg.com/babel/jfs/t1/73739/4/23911/130885/6391e09eE00866593/7102aa15077a6f07.jpg" "loop=yes" "theme=#FADFA3" "autoplay=false" %}
```
{% dplayer "url=https://files.catbox.moe/yiyosy.mp4"  "pic=https://m.360buyimg.com/babel/jfs/t1/73739/4/23911/130885/6391e09eE00866593/7102aa15077a6f07.jpg" "loop=yes" "theme=#FADFA3" "autoplay=false" %}
```