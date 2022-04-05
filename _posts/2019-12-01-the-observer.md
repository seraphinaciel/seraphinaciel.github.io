---
layout: post
title:  "css로 폰트 위치를 변경하자"
author: sera
categories: [ expand ]
tags: [ css, html ]
image: assets/images/thum-exp.jpg
---

<div class="rotateBox">
	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus animi eligendi nemo facilis similique eum quae doloribus atque modi, recusandae sit optio corrupti, ratione tempore soluta maxime in. <em>Quo, qui.</em></p>
	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Necessitatibus animi eligendi nemo facilis similique eum quae doloribus atque modi, recusandae sit optio corrupti, ratione tempore soluta maxime in. Quo, qui.</p>
	<p>Lorem ipsum dolor sit amet, <span><b>c</b><b>o</b><b>n</b><b>s</b><b>e</b><b>c</b><b>t</b><b>e</b><b>t</b><b>u</b><b>r</b></span> dipisicing lit Necessitatibus animi eligendi nemo facilis similique eum quae doloribus atque modi, recusandae sit optio corrupti, ratione tempore soluta maxime in. Quo, qui.</p>
</div>
<style>
	.rotateBox{background: gray;width:500px;height: 500px;margin:2rem auto;display: flex;flex-direction: column;justify-content: center;text-align:center;position: relative}
	.rotateBox p{}
	.rotateBox em{transform: rotate(-90deg);display: inline-block;background: red;position:absolute;top:3ex;left:-3ex;}
	.rotateBox span{width:2ch;text-align:center;position:absolute;top:0;right:2ch;background:green}
	.rotateBox b{width:1ch;transform: skewX(15deg);word-break: break-all; display:block;color:white;}
</style>
