---
layout: default
title: Categories
---

<div class="mx-auto">
    <h1 class="text-center">Categories</h1>
    {% for category in site.categories %}
    <div class="text-center">
        {% capture category_name %}{{ category | first }}{% endcapture %}
        <div id="#{{ category_name | slugize }}"></div>
        <h3>{{ category_name | upcase }}</h3>
        <a name="{{ category_name | slugize }}"></a>
        {% for post in site.categories[category_name] %}
        <article>
            <li class="list-unstyled">
                <a class="text-capitalize" href="{{ site.baseurl }}{{ post.url }}">{{post.title}}</a>
            </li>
        </article>
        {% endfor %}
    </div>
    {% endfor %}
</div>