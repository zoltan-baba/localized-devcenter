---
title: Build numbering and app versioning
redirect_from:
- "/builds/build-numbering-and-app-versioning/builds/build-numbering-and-app-versioning"
menu:
  builds:
    weight: 8

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
