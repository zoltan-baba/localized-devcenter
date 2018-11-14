---
title: Deploying an iOS app for external testing
date: 2018-10-26 12:39:01 +0000
redirect_from: []
menu:
  ios-deploy:
    weight: 3

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}