---
layout: default
---

## Pynq embedded community projects

{% for item in site.data.gallery.docs %}
<div class="gallery">
    <a target="_blank" href="{{ item.img }}">
    <img src="{{ item.img }}" alt="Cinque Terre" width="600" height="400">
    </a>
    <div class="desc">{{ item.description }}</div>
</div>
{% endfor %}