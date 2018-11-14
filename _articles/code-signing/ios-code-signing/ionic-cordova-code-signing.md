---
title: Code signing with Ionic and Cordova projects
menu:
  ios-code-signing:
    weight: 8

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
