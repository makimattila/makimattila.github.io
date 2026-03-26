---
layout: homepage
---

## About Me
<div class="about" markdown="1">

I am a PhD candidate in economics at Aalto University. 

In summer 2026, I will join the University of Oslo as an assistant professor (tenure-track). I will also be a part-time research fellow at GRAPE (Warsaw). 

My research is in applied microeconomic theory, focusing on how asymmetric information shapes market behavior and optimal regulation.

[My CV is here.](assets/files/cv.pdf)

</div>

## Working Papers
{% for p in site.data.papers %}
  {% include paper.html p=p %}
{% endfor %}
