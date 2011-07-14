---
layout: page
title: Archives
---

# Archives

List of all {{ site.posts.size }} posts.

<ul>
    {% for post in site.posts %}
    <li>
        {{ post.date | date: "%b %d, %Y" }} &mdash; <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
    {% endfor %}
</ul>
