---
layout: page
title: Blog
permalink: /blog/
---

# Blog Articles

Welcome to my blog! Here you'll find articles about Salesforce development, cloud technologies, and software engineering.

{% for post in site.posts %}
  <article>
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p class="post-meta">{{ post.date | date: "%B %d, %Y" }} | {% for tag in post.tags %}<span class="tag">{{ tag }}</span> {% endfor %}</p>
    <p>{{ post.description }}</p>
    <a href="{{ post.url }}">Read more →</a>
  </article>
  <hr>
{% endfor %}
