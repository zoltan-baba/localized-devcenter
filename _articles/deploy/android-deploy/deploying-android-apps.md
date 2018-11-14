---
title: Deploying Android apps
date: 2018-10-26 13:00:41 +0000
redirect_from:
- "/tutorials/deploy/android-deployment/"
menu:
  android-deploy:
    weight: 1

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
