---
layout: page
title: SVG动画之混合特效
excerpt_separator: "<!--more-->"
categories:
     - SVG动画
tags:
     - svg
---

### 放大并变换颜色

通过在css中transform属性以及fill的使用，能够在svg图像在放大的同时改变图像的颜色。

![悬停放大并改变颜色的CSS代码](https://gitee.com/QiuYuAn0303/Kamen_Rider/raw/gh-pages/assets/images/CSS_hover%20and%20change%20color.PNG)

<!--more-->
<style>
 .dd:hover{
transform: scale(1.5);
transition-duration:5s;
fill: aqua;}
</style>
<div class="dd">
<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" x="0px" y="0px" viewBox="0 0 100 100" enable-background="new 0 0 100 100" xml:space="preserve"><path d="M76.7,32.5c0,0.3-4.6,1.2-7.8,3.5c-2.6,1.9-3.8,4.3-3.9,4.7c-0.1,0.7,1.1,1.1,2.1,1.3c1.1,0.1,3-1.9,3.3-1.7  c0.3,0.2-1.4,2.8-3.2,2.7c-1.8-0.2-2.9-0.3-4.8-0.5c-1.9-0.2-5.2,2.6-5.6,3.8c-0.2,0.7-0.2,1-0.1,1.2c0.1,0,0.1,0,0.1,0  s2.2-1.7,3.5-2.5c1.3-0.8,3.8-1.4,3.8-1.4s0.2,4-1.5,6c-0.6,0.7-1.4,1.2-3,1.8c-1.5,0.6-2.3,1.8-2.3,1.8s0.6,1.1,0.2,2.8  C57.5,57.4,57,58,57,58.2v0c0,0.4,0.3,2,0.9,2.4c0.7,0.5,1.1,2.2,1,2.2c-0.1,0-0.3-0.3-0.4-0.1c-0.1,0.2,1,2.5,0.8,2.8  c-0.6-0.3-0.5-0.4-0.7-0.3c-0.3,0.4,1.2,5.7,0.7,6.5c-0.1,0-0.3-0.8-0.5-0.6s0.2,3.3-0.4,3.3c-0.3-0.3-0.6-0.2-0.9,0.2  c-0.4,0.4-0.5,1.8-0.9,2.3c-0.1,0.1-0.4-0.3-0.6-0.4C55,77,54.6,80,54.5,79.7c-0.2-0.3-0.7-0.6-1-0.3c-0.9,1.3-2.8,3.7-3,3.6  c-0.3-0.1-0.9-2.1-1.2-2.3c-0.3-0.1-0.5,0.8-0.7,0.4c-0.2-0.4-1.5-2.7-2.5-3.5c-1.1-1.6-0.4,0.3-0.8,0.2c-0.3-0.1-2.6-3.8-2.4-5.5  c0.2-1.7-0.3,0.3-0.6,0.2c-0.5-0.8,0.2-3.3,0.1-3.8c-0.1-0.6-0.8,0.2-1,0c-0.2-0.1,0.1-1.9,0.3-3.3c0.2-1.4,0.7-1.7,0.7-2.3  c-0.1,0-0.9,0.3-0.9,0.3s0.2-1,1.3-2.7c1-1.7,0.6-2.1,1.1-2.5c-0.2-0.2-0.7-0.9-0.9-2.3c-0.3-1.8,0.1-2.8,0.1-2.8s-0.8-1.2-2.3-1.8  c-1.5-0.6-2.4-1.1-3-1.8c-1.8-2.1-1.5-6-1.5-6s2.5,0.6,3.8,1.4c1.3,0.8,3.5,2.5,3.5,2.5s0,0,0.1,0c0.1-0.1,0.1-0.4-0.1-1.2  c-0.3-1.3-3.7-4-5.6-3.8c-1.9,0.2-3,0.4-4.8,0.5c-1.8,0.2-3.5-2.5-3.2-2.7c0.3-0.2,2.2,1.8,3.3,1.7c1.1-0.1,2.3-0.5,2.2-1.3  c0-0.3-1.3-2.8-3.9-4.7c-3.1-2.3-7.8-3.2-7.8-3.5c0-0.3,2.2-0.4,1.5-0.6s-1-5.2-0.7-5.2c0.3,0,1,5.3,4,6.2c2.1,0.6,1.9-0.7,1.9-0.7  s0.6-4.3-0.7-6c-1.2-1.7-1.9-6.3-1.5-6.4c0.3-0.1,0.8,4,1.7,4.1c0.9,0,4.2-7.1,4.8-6.7c0.6,0.3-2.5,4.9-3.3,7.5  c-0.6,2.6,0.4,2.5,0.9,1.7c0.5-0.9,3.2-6.8,3.2-6.4c0.1,0.4-0.4,2.8-1.7,6c-1.6,3.2-2,3.7-1.5,6.8c1.6,2.9,3.8,6,5.6,7.6  c0.4,0,1-2.5,1.3-2.4c0.3,0-0.4,2.5,0.1,3.1c0.5,0.5,3.6,1.8,4.1,2.5c0.5,0.7,0.9-3.3,1.1-3.3c0.4,0.5-0.4,3.9,0.7,4.6  c0.6,0.9,1.6,2.3,2.4,2.7c0,0,0.8-0.5,2.3-0.5s2.6,0.5,2.6,0.5c0.8-0.3,1.8-1.8,2.4-2.7c1.1-0.7,0.2-4.2,0.7-4.6  c0.2,0,0.6,4,1.1,3.3c0.5-0.7,3.6-1.9,4.1-2.5c0.5-0.5-0.2-3,0.1-3.1c0.3,0,0.8,2.4,1.3,2.4c1.9-1.6,4.1-4.7,5.7-7.6  c0.5-3.1,0.1-3.6-1.5-6.8c-1.3-3.2-1.7-5.6-1.7-6c0-0.4,2.7,5.6,3.2,6.4c0.5,0.8,1.5,0.9,0.9-1.7c-0.9-2.6-3.9-7.2-3.3-7.5  c0.6-0.3,3.9,6.8,4.8,6.7c0.9-0.1,1.3-4.1,1.7-4.1c0.3,0-0.3,4.7-1.6,6.4c-1.2,1.7-0.7,6-0.7,6s-0.1,1.2,1.9,0.7  c3-0.9,3.7-6.2,4-6.2c0.3,0.1-0.1,5-0.7,5.2C74.5,32.1,76.7,32.2,76.7,32.5z"></path></svg></div>

### 移动中变换颜色

利用position实现SVG图像的移动，用animation确定动画名称，动画播放时间以及次数，用@keyframes来规定移动的方向以及制定位置SVG的颜色。

![移动并改变颜色的css代码](https://gitee.com/QiuYuAn0303/Kamen_Rider/raw/gh-pages/assets/images/CSS_relative%20and%20change%20color.PNG)
<style>
.gkd svg{
position: relative;
animation:deer 4s infinite;}			
			
@keyframes deer
{0%   {fill:black; left:0px; top:0px;}
25%  {fill:#00BFFF; left:200px; top:0px;}
50%  {fill:darkturquoise; left:200px; top:200px;}
75%  {fill:darkslateblue; left:0px; top:200px;}
100% {fill:black; left:0px; top:0px;}}

</style>
		
<div class="gkd">
<svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:a="http://ns.adobe.com/AdobeSVGViewerExtensions/3.0/" x="0px" y="0px" width="114px" height="108.4px" viewBox="0 0 114 108.4" enable-background="new 0 0 114 108.4" xml:space="preserve">
<polygon id="mystar_1_"  points="57,0 74.6,35.7 114,41.4 85.5,69.2 92.2,108.4 57,89.9 21.8,108.4 28.5,69.2 0,41.4,39.4,35.7 "/>
</svg>
</div>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

### 结语
在这里我只展示了两种比较简单的混合特效，更多复杂的动画还要继续学习才能完成。