---
title: Skincare Blog
layout: "index.njk"
---
Hello eleventy people

<ul class="blogs">
{% for post in collections.posts %}
<li class="articles">
    <!-- <img src=" {{ img }} " alt="skincare" class="product"></img> -->
    <a href="{{ post.url }}">
    {{ post.data.title }}
    </a>
</li>
{% endfor %}
</ul>