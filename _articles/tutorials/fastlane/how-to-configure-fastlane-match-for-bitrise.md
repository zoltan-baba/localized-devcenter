---
title: How to configure fastlane match for Bitrise
menu:
  fastlane:
    weight: 2

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
