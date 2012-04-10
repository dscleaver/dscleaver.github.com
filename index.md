---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

## Under Construction
This is attempt #2 at getting a blog set up for myself. Looks like Jekyll bootstrap will remove all of the css fiddling that I was doing before.
   
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
