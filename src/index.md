---
title: Skincare Blog
layout: "index.njk"
---

Hello eleventy people

<ul>
{% for post in collections.posts %}
<li>
    <a href="{{ post.url }}">
    {{ post.data.title }}
    </a>
</li>
{% endfor %}
</ul>