---
permalink: /blog/
layout: default
title: "Ish Dhand's Blog: Thoughts on quantum optics and computation"
published: true
---

# Blog

<ul>
    {% for post in site.posts %}
    {% capture readtime %}{{ post.content | number_of_words | plus:91 | divided_by:180.0 | append:'.' | split:'.' | first }}{% endcapture %}
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date_to_string }} |
        {% if readtime == '0' %} &lt; 1{% else %}{{ readtime }}{% endif %} min. read </p>
        {{ post.excerpt }}
    {% endfor %}
</ul>
