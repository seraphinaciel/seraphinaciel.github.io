---
layout: post
title:  a vs button vs input
date:   2018-07-24 15:01:35 +0300
image:  02.jpg
tags:   Basic
---
* a태그 :  보통 페이지 링크를 걸 때 주로 사용되는 일반적인 방식(연결)
* 보안을 위해 _blank에 rel="noreferrer noopener" 추가! <a href="..." target="_blank" rel="noopener"></a>
* button :  값을 전달하는 사용자 인터페이스의 기능을 정의하는 마크업
* input : 값을 받거나 전달할 때 사용하는 마크업
{% highlight js %}
<input type="text" id="agree"><label for="agree">동의합니다.</label>
{% endhighlight %} 
