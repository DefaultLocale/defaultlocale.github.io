---
layout: default
permalink: archive.html
title:  "All posts"
---

<h3>All posts</h3>
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{post.date | date: "%Y-%m-%d"}}. {{ post.title }}</a>
        </li>
    {% endfor %}
</ul>
