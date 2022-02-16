---
title: Skincare Blog for Beginners
layout: "index.njk"
---

<div class="blogs">
{% for post in collections.posts %}
<ul class="articles">
    <li class="blog-preview">
        <a href="{{ post.url }}">
        <img src="{{ post.data.img}}" class="preview-pic">
        <br>
        {{ post.data.title }}
        </a>
    </li>
</ul>
{% endfor %}
</div>