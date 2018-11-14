---
title: Starting builds manually
date: 2018-09-25 13:58:51 +0000
redirect_from:
- "/builds/triggering-builds/starting-builds-manually/"
- "/builds/starting-builds-manually/"
menu:
  builds:
    weight: 2

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}