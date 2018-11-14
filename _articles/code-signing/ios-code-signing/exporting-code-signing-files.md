---
title: Exporting code signing files without codesigndoc
menu:
  ios-code-signing:
    weight: 11

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}