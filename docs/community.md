---
layout: default
---

## Pynq embedded community projects

{% for item in site.data.gallery.docs %}
<div class="container">
    <div class="item" id="{{ item.id }}">
    <img src="{{ item.img }}" alt="">
    <div class="text">
        <h3> {{ item.title }}</h3>
        <p>{{ item.desc }}</p>
    </div>
    <div class="button">Learn More</div>
</div>
{% endfor %}