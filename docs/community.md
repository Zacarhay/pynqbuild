---
layout: gallery
---



# Pynq embedded community projects

<div class="gallery">
{% for item in site.data.gallery.docs %}
  <div class="item">
    <a href="{{ item.url }}">
      <img src="{{ item.img }}" alt="">
      <div class="desc">
        <h3>{{ item.project }}</h3>
        <p>{{ item.college }}</p>
      </div>
    </a>
  </div>
  {% endfor %} 
</div>
     

