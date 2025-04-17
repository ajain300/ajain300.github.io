---
layout: page
title: Blog
permalink: /blog/
---

# Blog

Here you'll find my thoughts, insights, and experiences on various topics related to my research and professional interests.

{% for post in site.posts %}
  <article class="post">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
    <div class="post-excerpt">
      {{ post.excerpt }}
    </div>
    <a href="{{ post.url | relative_url }}" class="read-more">Read More</a>
  </article>
{% endfor %} 