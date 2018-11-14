---
title: Deploying an iOS app for simulators
date: 2018-11-10 14:34:02 +0000
menu:
  ios-deploy:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}