---
title: Getting started with React Native apps
date: 2018-10-12 13:16:58 +0000
redirect_from: []
menu:
  getting-started:
    weight: 11

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}