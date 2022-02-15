---
title: Skincare Blog
layout: "index.njk"
---

<div class="blogs">
{% for post in collections.posts %}
<h2 class="articles">
    <a href="{{ post.url }}">
    <img src="{{ post.data.img}}" class="preview-pic">
    {{ post.data.title }}
    </a>
</ul>
{% endfor %}
</div>