---
title: Available Stacks
redirect_from:
- "/docs/available-stacks"
menu:
  infrastructure:
    weight: 1

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
