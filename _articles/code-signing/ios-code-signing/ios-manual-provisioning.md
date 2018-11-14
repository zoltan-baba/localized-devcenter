---
title: Managing iOS code signing files - manual provisioning
menu:
  ios-code-signing:
    weight: 4

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
