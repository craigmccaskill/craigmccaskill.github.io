---
layout: page
title: Work
---
{% for post in site.categories.portfolio %}
<figure class="portfolio-box">
  <a href="{{ post.url }}"><img src="/assets/post-imgs/{{ post.img-main }}" alt="{{ post.title }}"></a>
  <figcaption><a href="{{ post.url }}">{{ post.title }}</a></figcaption>
</figure>
{% endfor %}



