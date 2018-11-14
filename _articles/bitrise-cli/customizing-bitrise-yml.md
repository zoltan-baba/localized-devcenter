---
title: Customizing bitrise.yml
date: 2018-10-31 09:27:26 +0000
redirect_from: []
menu:
  bitrise-cli:
    weight: 11

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
