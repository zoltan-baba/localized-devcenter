---
title: iOS code signing - troubleshooting
date: 2018-10-11 11:28:48 +0000
menu:
  ios-code-signing:
    weight: 13

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
