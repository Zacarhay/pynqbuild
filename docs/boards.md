---
layout: gallery
---
<!-------------------------------------------------------------------------------------------->
<!--Start Who Only-->
<div class="flex-row">
  <div class="flex-item flex-column">
    <h2>Pynq compatible boards</h2>
    <hr>
    <p class="text">
      <zero-md src="./MD/board.md"></zero-md>
    </p>
  </div>
</div>
<!--End Who-->
<!-------------------------------------------------------------------------------------------->
<!--Start Key Only-->
<div class="flex-row">
<div class="flex-item flex-column">
{% for item in site.data.boards.docs limit:2 %}
  <div class="flex-column">
    <div class="card" padding-bottom="20px">
      <div class="imagecontainer">
        <img class="card-img" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
      </div>
      <h1>{{ item.board }}</h1>
      <p class="price">{{ item.subhead }}</p>
      <p>{{ item.info }}</p>
      <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
    </div>
  </div>
{% endfor %}
</div>
</div>
<!--End Who-->
<!-------------------------------------------------------------------------------------------->
<!--Start Key Only-->
<div class="flex-row">
<div class="flex-item flex-column">
{% for item in site.data.boards.docs offest:2 limit:1 %}
  <div class="flex-column">
    <div class="card" padding-bottom="20px">
      <div class="imagecontainer">
        <img class="card-img" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
      </div>   
      <h1>{{ item.board }}</h1>
      <p class="price">{{ item.subhead }}</p>
      <p>{{ item.info }}</p>
      <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
    </div>
  </div>
{% endfor %}
</div>
</div>
<!--End Who-->
<!-------------------------------------------------------------------------------------------->
<!--Start Key Only-->
<h2>Xilinx boards with PYNQ compatibility</h2>
<hr>

<div class="flex-row">
<div class="flex-item flex-column">
{% for item in site.data.boards.docs offset:3 limit:4 %}
  <div class="flex-column">
    <div class="card" padding-bottom="20px">
      <div class="imagecontainer">
        <img class="card-img" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
      </div>   
      <h1>{{ item.board }}</h1>
      <p class="price">{{ item.subhead }}</p>
      <p>{{ item.info }}</p>
      <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
    </div>
  </div>
{% endfor %}
</div>
</div>
<!--End Who-->
<!-------------------------------------------------------------------------------------------->
<!--Start Key Only-->
<h2>Other PYNQ compatible boards</h2>
<hr>

<div class="flex-row">
<div class="flex-item flex-column">
{% for item in site.data.boards.docs offset:7 limit:2 %}
  <div class="flex-column">
    <div class="card" padding-bottom="20px">
      <div class="imagecontainer">
        <img class="card-img" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
      </div>   
      <h1>{{ item.board }}</h1>
      <p class="price">{{ item.subhead }}</p>
      <p>{{ item.info }}</p>
      <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
    </div>
  </div>
{% endfor %}
</div>
</div>
<!--End Who-->
<!-------------------------------------------------------------------------------------------->
<!--Start Key Only-->
<div class="flex-row">
<div class="flex-item flex-column">
{% for item in site.data.boards.docs offset:9 limit:1 %}
  <div class="flex-column">
    <div class="card" padding-bottom="20px">
      <div class="imagecontainer">
        <img class="card-img" src="{{ site.urlimg }}{{ item.img }}" class="img-fluid" alt="{{ item.board }}">
      </div>   
      <h1>{{ item.board }}</h1>
      <p class="price">{{ item.subhead }}</p>
      <p>{{ item.info }}</p>
      <p><button onclick="location.href='{{ item.url }}';" target="_blank">See Vendor Website</button></p>
    </div>
  </div>
{% endfor %}
</div>
</div>

