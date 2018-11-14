---
title: Connecting a repository
redirect_from:
- https:/getting-started/adding-a-new-app/connecting-your-repository
menu:
  adding-a-new-app:
    weight: 2

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
