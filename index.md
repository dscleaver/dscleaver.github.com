---
layout: page
title: Leave It To Me Programming
tagline: Home
---
{% include JB/setup %}

## Welcome
Welcome to Leave It To Me Programming a place for me to write about the topics that interest me. For my day job I write scalable web services, and in my free time I learn new programming languages and how they are built. I am also a dedicated husband, father, and martial artist.
 
## Latest Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
