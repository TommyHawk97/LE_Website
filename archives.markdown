---
layout: "page"
title: Archives
---

All of the archives will be here.

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{post.url}}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>