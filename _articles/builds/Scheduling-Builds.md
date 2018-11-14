---
title: Scheduling your builds
redirect_from:
- "/builds/scheduling-builds/"
- "/builds/scheduling-builds"
menu:
  builds:
    weight: 3

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
