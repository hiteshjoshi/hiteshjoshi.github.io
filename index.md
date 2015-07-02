---
layout: page
title: Howdy!
tagline: What's up?
---
{% include JB/setup %}


## This is a blog for all the code I host on github.

Here are some posts you should consider reading instead of this silly page.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

--All done