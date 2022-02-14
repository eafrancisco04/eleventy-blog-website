---
title: Skincare Blog
layout: "index.njk"
---

Hello eleventy people

<ul class="blogs">
{% for post in collections.posts %}
<li>
    <img src="/img/{{ img }}.jpg" alt="skincare" class="preview">
    <a href="{{ post.url }}">
    {{ post.data.title }}
    </a>
</li>
{% endfor %}
</ul>