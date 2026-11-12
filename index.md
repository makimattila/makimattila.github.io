---
layout: homepage
---

## About Me
<div class="about" markdown="1">

I'm an Assistant Professor in the Department of Economics at the University of Oslo and a part-time research fellow at GRAPE in Warsaw. I did my PhD at Aalto University. 

In my research, I use mechanism design and game theory to study regulation and market design.

[My CV is here.](assets/files/cv.pdf)

</div>

## Publications
{% for p in site.data.publications %}
  {% include paper.html p=p %}
{% endfor %}

## Working Papers
{% for p in site.data.papers %}
  {% include paper.html p=p %}
{% endfor %}
