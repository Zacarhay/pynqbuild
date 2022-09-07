---
layout: gallery
---

## Pynq embedded community projects

# V2 of Gallery

<div class="gallery">
{% for item in site.data.gallery.docs %}
  <div class="item">
    <a href="{{ item.href }}">
      <img src="{{ item.img }}" alt="">
      <h3>{{ item.title }}</h3>
      <p>{{ item.desc }}</p>
    </a>
  </div>
{% endfor %}
</div>       

# V1 of gallery

{% for item in site.data.gallery.docs %}
<div class="gallery">
    <a target="_blank" href="{{ item.img }}">
    <img src="{{ item.img }}" alt="{{ item.title }}" width="600" height="400">
    </a>
    <div class="desc">{{ item.description }}</div>
</div>
{% endfor %}