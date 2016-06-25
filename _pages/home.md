---
title: algoquant Home
subtitle: algoquant's Home Page on GitHub
permalink: /
layout: default
type: page
---

### Welcome to algoquant's Website!  

A website devoted to exploring quantitative and systematic investing.  
You can find more information on the following pages:  
<ul class="pages">
  {% for page in site.pages %}
    <a href="{{ page.url | prepend: site.baseurl }}" style="color:blue" target="_blank"> <b>{{ page.title }}</b> </a> <br> <br>
  {% endfor %}
</ul>

You can also click on the right sidebar to navigate the website.  


