---
title: Creating a signed .ipa for Xcode projects
menu:
  ios-code-signing:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}