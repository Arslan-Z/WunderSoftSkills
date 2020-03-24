---
title: 001《ScreenToGif》如何快速将gif图调整到300帧以内?
---

微信一直以「克制」著称,为了给用户节省流量,微信公众号后台上传的gif图片不能超过300帧

为保证最终gif图的流畅,可以采用**每隔N帧,抽取1帧的方式**, 一张504帧的图片,我们需要**每隔1帧抽取1帧**

如何用工具实现每隔1帧抽取1帧?

zhaoolee找到一个开源的小工具(昭昭的奇妙工具)ScreenToGif

![](https://www.v2fy.com/asset/change_gif_frame_number/to_252.gif)

调整前的图片504帧: https://www.v2fy.com/asset/change_gif_frame_number/504.gif 

调整后的图片252帧:

![](https://www.v2fy.com/asset/change_gif_frame_number/252.gif)


ScreenToGif下载地址: https://www.lanzous.com/b00nfgo3c


## 计算系数的通用公式:

![](https://www.v2fy.com/asset/change_gif_frame_number/xishu.png)

M帧gif图减少到300帧以内的计算方法: **300/(M-300)**, 结果为小数则只取整数部分

## ScreenToGif下载地址

[https://www.lanzous.com/b00nfgo3c](ttps://www.lanzous.com/b00nfgo3c)

## 小结:

ScreenToGif**每隔N帧,抽取1帧的功能**,让gif图减少帧数的同时, 又保持了流畅性,即使是PhotoShop也没有提供自动化抽取帧数的解决方案, ScreenToGif提供的**每隔N帧,抽取1帧的功能**功能简直称得上小众神技!

---

「奇妙软件技能书」主页：https://www.v2fy.com/WunderSoftSkills
本文属于 「奇妙软件技能书」的一部分，「奇妙软件技能书」以问题作为标题，用gif图解答问题，文章末尾放出软件的下载链接，用最少的字，最简洁的图，传递最有用的奇妙技能; 让「奇妙软件技能」造福人类～











