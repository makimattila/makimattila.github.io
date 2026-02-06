---
layout: homepage
---

## About Me
<div class="about" markdown="1">

I am a PhD student in Economics at Aalto University. I began my doctoral studies in 2021, spent the 2023–24 academic year at the MIT Department of Economics, and will graduate in 2026. My research is in microeconomic theory, focusing on how asymmetric information shapes market behavior and optimal regulation. 

[My CV is here.](assets/files/cv.pdf)

</div>

## Working Papers
{% for p in site.data.papers %}
  {% include paper.html p=p %}
{% endfor %}
