---
title: Enable/Disable a step (optionally, based on a condition)
menu:
  tips-and-tricks:
    weight: 6

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}