---
layout: page
title: Hello Programming World!
tagline: Supporting tagline
---
{% include JB/setup %}

<h3>Disclaimer</h3>

This is this roughest of rough blogs created through github pages.

<h2> Who Am I </h2>

As a former English major and marketing editor who is venturing into the world of programming, I wanted to give myself a place to vent frustration, a place to celebrate successes, and a place to keep everyone who is curious about my journey through MakerSquare updated. So, as is apt for my generation (so I'm told), I've taken to blogging.

But why not wordpress, tumblr, or some other user friendly blogging platform you ask? Because I like to my things hard on myself? No, in reality, I figured what better what to work on my programming skills than with something that requires more of me. With that said, please read the disclaimer and most of all, don't judge me.

## Recent Blogs

Check out my most recent blogs!

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




