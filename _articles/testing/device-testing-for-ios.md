---
title: Device testing for iOS
date: 2018-10-17 10:31:27 +0000
menu:
  testing:
    weight: 4

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}