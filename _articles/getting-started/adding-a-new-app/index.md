---
title: Adding a new app
redirect_from:
- "/tutorials/deploy/android-deployment/getting-started/adding-a-new-app"
- "/adding-a-new-app/"
menu:
  adding-a-new-app:
    weight: 1

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
