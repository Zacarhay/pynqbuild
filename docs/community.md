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
      <p>{{ item.description }}</p>
    </a>
  </div>
  {% endfor %} 
</div>
     

