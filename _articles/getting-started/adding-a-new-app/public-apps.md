---
title: Public apps
redirect_from:
- "/adding-a-new-app/public-apps/"
menu:
  adding-a-new-app:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}