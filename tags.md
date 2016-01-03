---
layout: default
title: Tags
---

<ul>
    {% for category in site.categories %}        
        <li><a href="/tags/{ category }">{ category }</a></li>
    {% endfor %}
</ul>
