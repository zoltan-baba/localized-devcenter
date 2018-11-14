---
title: Generate and deploy multiple flavor APKs in a single workflow
date: 2018-10-26 12:56:08 +0000
redirect_from: []
menu:
  android-deploy:
    weight: 2
    title: Generating and deploying multiple flavor APKs in a single build

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
