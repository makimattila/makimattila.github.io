---
layout: homepage
---

## About Me
<div class="about" markdown="1">

I am a PhD student in Economics at Aalto University. I began my doctoral studies in 2021, spent the 2023–24 academic year at the MIT Department of Economics, and am on the academic job market in 2025–26.

[My CV is here.](assets/files/cv.pdf)

I study microeconomics, using game theory and mechanism design to examine how asymmetric information shapes market behavior and optimal regulation. Although primarily theoretical, my work addresses pressing policy challenges such as environmental policy, economic inequality, and the regulation of digital markets, and I occasionally complement theory with empirical evidence. 

Microeconomics is fun, but I also like to wander through Helsinki on sunlit summer nights&mdash;marveling at the Art Nouveau façades, watching the waves of the Baltic Sea and listening to a Sibelius symphony.  

</div>

## Working Papers
{% for p in site.data.papers %}
  {% include paper.html p=p %}
{% endfor %}
