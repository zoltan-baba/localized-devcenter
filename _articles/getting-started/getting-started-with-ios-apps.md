---
title: Getting started with iOS apps
date: 2018-09-12 15:27:42 +0000
redirect_from: []
menu:
  getting-started:
    weight: 9

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}