---
layout: default
title: Blog
permalink: /blog
---

## Blog Posts on Jekyll

<ul>
    {% for post in site.posts %}
    <li><a href="{{ site.baseurl }}{{ post.url }}" class="post-preview">{{ post.title }}</a></li>
    {% endfor %}
</ul>

This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)