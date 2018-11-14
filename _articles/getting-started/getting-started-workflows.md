---
title: Workflows
redirect_from:
- "/getting-started/manage-your-workflow/"
menu:
  getting-started:
    weight: 7

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}