---
title: Contact
nav:
  order: 4
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Our lab is part of the University of York [Department of Biology](https://www.york.ac.uk/biology/), and the [York Structural Biology Laboratory](https://www.york.ac.uk/chemistry/research/ysbl/) (YSBL) and [York Biomedical Research Institute](https://www.york.ac.uk/biomedical-research-institute/) (YBRI).

You can find us in the Department of Biology.

{%
  include button.html
  type="email"
  text="alex.cook@york.ac.uk"
  link="alex.cook@york.ac.uk"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/8ZdMBoK7YZ4eymSe9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
