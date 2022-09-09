---
layout: gallery
---



# PYNQ Alveo community projects and tutorials
PYNQ can be used with [Alveo accelerator boards](https://www.xilinx.com/products/boards-and-kits/alveo.html) and [AWS-F1](https://aws.amazon.com/ec2/instance-types/f1/). The following examples can be installed on the host computer and run on the Alveo board or on an AWS-F1 instance. 

<div class="gallery">
{% for item in site.data.pynqprojalveo.docs %}
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
     
<!-------------------------------------------------------------------------------------------->
<!--Start FINN-->
<div class="flex-row">
  <div class="flex-item flex-column">
    <h2>Machine Learning on Xilinx FPGAs with FINN</h2>
    <hr>
    <p class="text">
      <img class="image image-wrap-text max-width-400" src="./images/FINN.png">
      <zero-md src="./MD/communitymd/FINN.md"></zero-md>
    </p>
  </div>
</div>
<!--End FINN-->
<!-------------------------------------------------------------------------------------------->
