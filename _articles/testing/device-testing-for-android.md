---
title: Device testing for Android
date: 2018-10-26 08:33:44 +0000
redirect_from: []
menu:
  testing:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
