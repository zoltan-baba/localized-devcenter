---
title: iOS code signing on Bitrise
redirect_from:
- "/ios/code-signing/"
menu:
  ios-code-signing:
    weight: 1

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
