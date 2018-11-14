---
title: fastlane tools integration
menu:
  fastlane:
    weight: 1
    title: Fastlane tools integration

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
