---
layout: page
title: Hello Programming World!
tagline: Supporting tagline
---
{% include JB/setup %}

#Disclaimer

This is this roughest of rough blogs created through github pages.

As a former English major and marketing editor who is venturing into the world of programming, I wanted to give myself a place to vent frustration, a place to celebrate successes, and a place to keep everyone who is curious about my journey through MakerSquare updated.

## Update Author Attributes


## Recent Blogs

Check out my most <em>recent</em> blogs!

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




