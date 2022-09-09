---
layout: gallery
---



# Pynq Tutorials

<div class="gallery">
{% for item in site.data.pynqtut.docs %}
  <div class="item">
    <a href="{{ item.url }}">
      <img src="{{ item.img }}" alt="">
      <div class="desc">
        <h3>{{ item.project }}</h3>
        <p>{{ item.subtitle }}</p>
      </div>
    </a>
  </div>
  {% endfor %} 
</div>

# Pynq Notebooks

<div class="gallery">
{% for item in site.data.pynqnotebooks.docs %}
  <div class="item">
    <a href="{{ item.url }}">
      <img src="{{ item.img }}" alt="">
      <div class="desc">
        <h3>{{ item.project }}</h3>
      </div>
    </a>
  </div>
  {% endfor %} 
</div>

