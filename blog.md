---
layout: page
title: Blog
permalink: /blog/
---

<ul class="post-list">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
    {% if post.excerpt %}<div>{{ post.excerpt | strip_html | truncatewords: 40 }}</div>{% endif %}
  </li>
{% endfor %}
</ul>

<p class="post-meta"><a href="{{ '/feed.xml' | relative_url }}">Subscribe via RSS</a></p>
