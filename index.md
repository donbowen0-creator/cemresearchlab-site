---
layout: default
title: Home
---

<p class="tag">Research program</p>

# Why do people exposed to the same conditions so often arrive at different outcomes?

<p class="lede">The Criminogenic Embeddedness Model (CEM) is a life-course theory of how strain, social control, and social learning interact to shape criminal trajectories. This site is the home of CEM, its companion Recovery Embeddedness Model (REM), and the research testing both.</p>

<a class="button" href="{{ '/cem/' | relative_url }}">About CEM</a>
<a class="button secondary" href="{{ '/publications/' | relative_url }}">Publications</a>

{% include book-card.html heading="The book" blurb="introduces the model, its four pathways, eight propositions, and a provisional measurement agenda. The full text is free to read and download." %}

## Latest from the blog

<ul class="post-list">
{% for post in site.posts limit:3 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
  </li>
{% endfor %}
</ul>
