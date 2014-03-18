---
layout: page
title: BGI Cancer Research
tagline: demo v0.1
---
{% include JB/setup %}


TODO:
    
    Add Group Information here.
    
    list:
	1. Who we are.
	2. What we do.
	3. What we have done.

    
###Member:

<ul class="posts">
  {% for post in site.posts %}
	<li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


