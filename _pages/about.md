---
layout: page
title: Memoirs, a free minimalist Jekyll blogging theme with modern design 
permalink: /about
comments: false
image: assets/images/screenshot.jpg
imageshadow: true
---

This website is a demonstration to see **Memoirs Jekyll theme** in action. The theme is compatible with Github pages, in fact even this demo itself is created with Github Pages and hosted with Github. 

<a target="_blank" href="https://bootstrapstarter.com/jekyll-theme-memoirs/" class="btn btn-dark"> Get Memoirs for Jekyll &rarr;</a>


<div class="list-authors mt-5">
<!-- {% for author in site.authors %}    -->
    <div id="{{ site.name }}" class="authorbox position-relative pb-5 pt-5 mb-4 mt-4 border">   
        <div class="row">
            <div class="wrapavname col-md-3 text-center">
                {% if author[1].gravatar %}
                <img  class="author-thumb" src="https://www.gravatar.com/avatar/{{ site.gravatar }}?s=250&d=mm&r=x" alt="{{ site.name }}">
                {% else %}
                <img  class="author-thumb" src="{{site.baseurl}}/{{ site.avatar }}" alt="{{ site.name }}">
                {% endif %}

                <p class="mt-4 mb-0 small text-center">


                        <a target="_blank" class="d-inline-block mx-1 text-dark" href="{{ site.web }}"><i class="fa fa-link"></i></a> 

                        <a target="_blank" class="d-inline-block mx-1 text-dark" href="{{ site.twitter }}"><i class="fab fa-twitter"></i></a>

                        <a class="d-inline-block mx-1 text-dark" href="mailto:{{ site.email }}"><i class="fa fa-envelope"></i></a>
                </p>
                
            </div>
            <div class="col-md-9">
                <h3>{{ site.display_name }}</h3>
                <p class="mt-3 mb-0">{{ site.description }}</p> 
            </div>
        </div> 
    </div>    
<!-- {% endfor %} -->
</div>

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Please send your message to {{site.name}}. We will reply as soon as possible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Address*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Message*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Send">
</form>
