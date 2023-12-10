---
layout: default
title: "Blog posts"
permalink: /blog/
---
<h1>{{ page.title }}</h1>
<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        {{ post.excerpt }}
    </li>
    {% endfor %}
</ul>