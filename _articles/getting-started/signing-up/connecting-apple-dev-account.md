---
title: Connecting your Apple Developer Account to Bitrise
redirect_from:
- "/signing-up/connecting-apple-dev-account"
menu:
  signing-up:
    weight: 6

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
