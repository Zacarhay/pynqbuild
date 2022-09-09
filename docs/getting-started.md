---
layout: default
---

<div style="padding-top:30px" width="100%"><center><a href="https://pynq.readthedocs.io/en/latest/getting_started.html" class="button" style="width: 100% !important">Board Setup</a></center></div>

## Development Boards

PYNQ supports Zynq based boards (Zynq, Zynq Ultrascale+, Zynq RFSoC), <a href="https://www.xilinx.com/products/som/kria.html">Kria SOMs</a>, <a href="https://www.xilinx.com/products/boards-and-kits/alveo.html">Xilinx Alveo</a> accelerator boards and <a href="https://aws.amazon.com/ec2/instance-types/f1/">AWS-F1</a> instances.

See the <a href="https://pynq.readthedocs.io/en/latest/getting_started/alveo_getting_started.html">PYNQ Alveo Getting Started guide</a> for details on installing PYNQ for use with Alveo and AWS-F1. 

## Downloadable PYNQ Images

If you have a Zynq board, you need a PYNQ SD card image to get started. You can download a pre-compiled PYNQ image from the table below. If an image is not available for your board, you can build your own SD card image (see details below).

<center><table class="pynq_images">
<tbody><tr><th>Board</th><th>SD card image</th><th>Documentation</th></tr>
  <tr>
  <td>PYNQ-Z2</td>
  <td><a href="https://bit.ly/pynqz2_2_7">v2.7</a> </td>
  <td><a href="https://pynq.readthedocs.io/en/v2.6.1/getting_started/other_boards.html">PYNQ setup guide</a></td>
 </tr>
 <tr>
  <td>PYNQ-Z1</td>
  <td><a href="https://bit.ly/pynqz1_2_7">v2.7</a></td>
  <td><a href="https://pynq.readthedocs.io/en/v2.6.1/getting_started/pynq_z1_setup.html">PYNQ setup guide</a></td>
 </tr>
 <tr>
  <td>PYNQ-ZU</td>
  <td><a href="https://bit.ly/pynqzu_2_7">v2.7</a></td>
  <td><a href="https://github.com/Xilinx/PYNQ-ZU">GitHub project page</a></td>
 </tr>
 <tr>
  <td>Kria KV260 Starter Kit*</td>
  <td><a href="https://www.xilinx.com/products/som/kria/kv260-vision-starter-kit/kv260-getting-started-ubuntu/setting-up-the-sd-card-image.html">Ubuntu image</a></td>
  <td><a href="https://github.com/Xilinx/Kria-PYNQ">Kria PYNQ setup</a></td>
 </tr>
 <tr>
  <td>ZCU104</td>
  <td><a href="https://bit.ly/zcu104_2_7">v2.7</a></td>
  <td><a href="https://pynq.readthedocs.io/en/v2.6.1/getting_started/zcu104_setup.html">PYNQ setup guide</a></td>
 </tr>
 
 <tr>
  <td>RFSoC 2x2</td>
  <td><a href="https://bit.ly/rfsoc2x2_2_7">v2.7</a></td>
  <td><a href="https://www.rfsoc-pynq.io">RFSoC 2x2 GitHub Pages</a></td>
 </tr>
 <tr>
  <td>ZCU111</td>
  <td><a href="https://bit.ly/zcu111_2_7">v2.7</a></td>
  <td><a href="https://github.com/Xilinx/PYNQ_RFSOC_Workshop">PYNQ RFSoC workshop</a></td>
 </tr>
 <tr>
  <td>Ultra96V2</td>
  <td><a href="https://bit.ly/u96v2_v2_7">v2.7</a></td>
  <td><a href="http://avnet.me/ultra96_pynq_docs">Avnet PYNQ documentation</a></td>
 </tr>
 <tr>
  <td>Ultra96 (legacy)</td>
  <td><a href="https://bit.ly/u96v1_2_7">v2.7</a></td>
  <td class="plain_style">See Ultra96V2</td>
 </tr>
 <tr>
  <td>TySOM-3-ZU7EV</td>
  <td><a href="https://github.com/aldec/PYNQ_251_TySOM-3-ZU7EV_pre-built">v2.5</a></td>
  <td><a href="https://github.com/aldec/TySOM-3-ZU7EV">GitHub project page</a></td>
 </tr>
 <tr>
  <td>TySOM-3A-ZU19EG</td>
  <td><a href="https://github.com/aldec/PYNQ_251_TySOM-3A-ZU19EG_pre-built">v2.5</a></td>
  <td><a href="https://github.com/aldec/TySOM-3A-ZU19EG">GitHub project page</a></td>
 </tr>
</tbody></table></center>
*For the Kria KV260, follow the guide for the Ubuntu image and then follow the Kria PYNQ setup instructions to install PYNQ.

## Build a PYNQ SD Card Image

See the <a href="https://pynq.readthedocs.io/en/latest/pynq_sd_card.html">PYNQ image build guide</a> or details on building the PYNQ image. 
The following rootfs files can be used for rebuilding an image for a custom board:

- <a href="https://bit.ly/pynq_aarch64_2_7">PYNQ rootfs aarch64 v2.7</a>
- <a href="https://bit.ly/pynq_arm_2_7">PYNQ rootfs arm v2.7</a>
 
## Recommended getting started board

<center><div class="small-12 columns b60"><p><a href="https://www.tulembedded.com/FPGA/ProductsPYNQ-Z2.html"><img src="http://lh3.googleusercontent.com/gMS-DWfKG4hTjUpAnOpT51ReoTOgWxQGLcyW1754gOTt-JhIbmtlT6FVllAp6OTkqH-5Lcz1NsygD2FtbVYfXJeZ6w=s388" class="alignleft" width="350" height="350" alt="Blog of Feeling Responsive"></a> <table class="boards">
<tbody><tr><th width=""></th><th width="">PYNQ-Z2</th>
</tr><tr><td>Device</td><td>Zynq Z7020</td></tr>
<tr><td>Memory</td><td>512MB DDR3</td></tr>
<tr><td>Storage</td><td>MicroSD</td></tr>
<tr><td>Video</td><td>HDMI In &amp; Out ports</td></tr>
<tr><td>Audio</td><td>ADAU1761 codec with HP + Mic, Line in</td></tr>
<tr><td>Network</td><td>10/100/1000 Ethernet</td></tr>
<tr><td>Expansion</td><td>USB host (PS)</td></tr>
<tr><td>GPIO</td><td>1x Arduino Header</td></tr>
<tr><td></td><td>2x Pmod*</td></tr>
<tr><td></td><td>1x RaspberryPi header*</td></tr>
<tr><td>Other I/O</td><td>6x user LEDs</td></tr>
<tr><td></td><td>4x Pushbuttons</td></tr>
<tr><td></td><td>2x Dip switches</td></tr>
<tr><td>Dimensions</td><td>3.44” x 5.51” (87mm x 140mm)</td></tr>
</tbody></table><a href="https://www.tulembedded.com/FPGA/ProductsPYNQ-Z2.html" title="See the TUL Wwebpage"><strong>TUL Webpage&nbsp;›</strong></a></p></div></center>

 [1]: {{ site.url }}{{ site.baseurl }}/documentation/
