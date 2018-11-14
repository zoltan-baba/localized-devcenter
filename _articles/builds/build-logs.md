---
title: Build logs
date: 2018-10-31 10:43:57 +0000
menu:
  builds:
    weight: 12

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}