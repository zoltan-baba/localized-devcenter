---
title: How to use the Generic File Storage
menu:
  tutorials:
    weight: 7

---
 {% capture filename %}{{ page.url}}{% endcapture %}
 {% assign num = filename | size | minus: 1 %}
 {% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
