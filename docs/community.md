---
layout: gallery
---

## Pynq embedded community projects

# V2 of Gallery

<div class="gallery">
{% for item in site.data.gallery.docs %}
  <div class="item">
    <a href="{{ item.url }}">
      <img src="{{ item.img }}" alt="">
      <h3>{{ item.project }}</h3>
      <p>{{ item.college }}</p>
    </a>
  </div>
  {% endfor %} 
</div>
     

