---
layout: page
title: Authors
permalink: /authors
comments: false
---

### YAML Post Example:
```html
---
layout: post
title:  "We all wait for summer"
author: john
categories: [ Lifestyle, Travel ]
tags: [ France ]
image: assets/images/5.jpg
description: "Something about this post here"
---
```

### YAML Page Example
```html
---
layout: page
title: About Memoirs
permalink: /Guide
comments: false <!--comments false / true-->
---
```

### Rating
```html
---
layout: post
title:  "Inception Movie"
author: john
categories: [ Lifestyle ]
tags: [red, yellow]
image: assets/images/11.jpg
description: "My review of Inception movie. Actors, directing and more."
rating: 4.5
---
```

### Paragraph
A paragraph looks like this — dolor amet cray stumptown fingerstache neutra food truck seitan poke cardigan waistcoat VHS snackwave celiac hella. Godard seitan shoreditch flexitarian next level trust fund man braid vegan listicle keytar bitters. Disrupt cray fashion axe unicorn lomo shaman poke glossier keffiyeh snackwave austin tattooed seitan hexagon lo-fi. Lumbersexual irony vaporware, butcher shaman church-key iceland.
**Memoirs Jekyll theme**

```html
**Point**
```
***

### Headings by default:

# This is the default title
## This is the default title
### This is the default title
#### This is the default title
##### This is the default title
###### This is the default title

```html
# This is the default title
## This is the default title
### This is the default title
#### This is the default title
##### This is the default title
###### This is the default title
```

***

### code
backtick(*3) + [code name]
[code name] : css, js, python, ruby, c

```html
<li class="ml-1 mr-1">
    <a target="_blank" href="#">
    <i class="fab fa-twitter"></i>
    </a>
</li>
```

***

### Link
<a target="_blank" href="link" class="btn btn-dark"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-light"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-primary"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-secondary"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-success"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-warning"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-danger"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-light"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-dark"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-info"> 바로가기 &rarr;</a>

```html
<a target="_blank" href="link" class="btn btn-dark"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-light"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-primary"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-secondary"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-success"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-warning"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-danger"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-light"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-outline-dark"> 바로가기 &rarr;</a>
<a target="_blank" href="link" class="btn btn-info"> 바로가기 &rarr;</a>
```

***

### Lists

#### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

***

#### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.


***

### Quotes

> "There's almost no single moment in Portrait of a Lady on Fire that couldn't be captured, mounted, and hung on a wall as high art." <cite>— Entertainment Weekly</cite>

```html
> "There's almost no single moment in Portrait of a Lady on Fire that couldn't be captured, mounted, and hung on a wall as high art." <cite>— Entertainment Weekly</cite>
```
***

### Spoiler

The mind-warping film opened with a hospital patient Simon Cable (Ryan Phillippe) awakening in a <span class="spoiler"> hospital with little knowledge (amnesia perhaps?) of what had happened, and why he was there, etc. He was told by attending Dr. Jeremy Newman (Stephen Rea) that it was July 29, 2002 (Simon thought it was the year 2000 - he was confused - he heard a doctor say 20:00 hours!) and that he had died for two minutes from cardiac arrest following the near-fatal accident -- but he had been revived ("You're as good as new").</span> Dr. Newman: "Simon, this is the 29th of July. The year is 2002. And your wife, whose name is Anna, is waiting outside." 

```html
<span class="spoiler">My hidden paragraph here.</span>
```

***

### Videos

<iframe src="https://www.youtube.com/embed/iWowJBRMtpc" frameborder="0" allowfullscreen></iframe>

***

### Images

![](/assets/images/screenshot.jpg)
*Backyard*
<img src="{{ site.baseurl }}/{{ site.logo }}" alt="logo">
*logo*

```html
![](/assets/images/screenshot.jpg)
*Backyard*
<img src="{{ site.baseurl }}/{{ site.logo }}" alt="logo">
*logo*
```

***
