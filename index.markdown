---
layout: default
title: Mike Skalnik
---
<h2>Posts</h2>
<ul class="posts">
  {% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }} &raquo;</span> <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

To enable Disqus comments + badges for this site, [add it to your Disqus account](http://disqus.com/add/).