---
title: Setting up configuration
redirect_from:
- "/adding-a-new-app/setting-up-configuration"
menu:
  adding-a-new-app:
    weight: 4

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
