---
layout: "page"
title: Archives
---

All of the archives will be here.

<!-- Code below uses a for loop to generate a list of all posts automatically rather than uploading them manually
 -->
<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{post.url}}">{{ post.title }}</a>     
        </li>
    {% endfor %}
</ul>