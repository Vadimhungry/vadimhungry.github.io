---
layout: default
title: "Blog posts"
permalink: /blog/
lang: en
---
<h1>{{ page.title }}</h1>


{% for post in site.posts %}

<div>
    <h2>{{ post.date | date: "%Y-%m-%d" }} <a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
</div>

{% endfor %}

