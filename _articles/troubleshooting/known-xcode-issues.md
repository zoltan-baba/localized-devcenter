---
title: List of known Xcode issues
redirect_from:
- "/ios/known-xcode-issues/"
menu:
  troubleshooting:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
