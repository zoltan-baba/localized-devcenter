---
title: Getting started with Xamarin apps
date: 2018-10-19 11:49:28 +0000
menu:
  getting-started:
    weight: 12

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}