---
title: Sensitive input in public apps
redirect_from:
- "/sensitive-input-field/"
- sensitive-input-field/#set-a-sensitive-input-in-a-step/
menu:
  builds:
    weight: 10

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}