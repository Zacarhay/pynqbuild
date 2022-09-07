---
layout: default
---

## Pynq embedded community projects

<section id="portfolio">

{% for item in site.data.gallery.docs %}
<div class="project">
    <img class="project__image" src="{{ item.img }}" />
    <p>{{ item.title }}</p>
    <h3 class="grid__title"> {{ item.desc }}</h3>
    <div class="grid__overlay">
    <button class="viewbutton">View More</button>
    </div>
</div>
{% endfor %}

</section>