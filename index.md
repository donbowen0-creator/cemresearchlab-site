---
layout: default
title: Home
---

<p class="tag">Research program</p>

# Why do people exposed to the same conditions so often arrive at different outcomes?

<p class="lede">The Criminogenic Embeddedness Model (CEM) is a life-course theory of how strain, social control, and social learning interact to shape criminal trajectories. This site is the home of CEM, its companion Recovery Embeddedness Model (REM), and the research testing both.</p>

<a class="button" href="{{ '/cem/' | relative_url }}">About CEM</a>
<a class="button secondary" href="{{ '/research/' | relative_url }}">Research projects</a>

<div class="card">
  <h3>The book</h3>
  <p><em>Criminogenic Embeddedness and Criminal Trajectories: A Life-Course Model (CEM) of Strain, Control, and Social Learning</em> (2026) introduces the model, its four pathways, eight propositions, and a provisional measurement agenda.</p>
  <p><a href="https://www.amazon.com/dp/B0HFMHM93F">Amazon</a> · <a href="https://doi.org/10.5281/zenodo.21961664">Zenodo (DOI: 10.5281/zenodo.21961664)</a></p>
</div>

## Latest from the blog

<ul class="post-list">
{% for post in site.posts limit:3 %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
  </li>
{% endfor %}
</ul>
