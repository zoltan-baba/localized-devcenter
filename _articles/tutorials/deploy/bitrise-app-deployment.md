---
title: Bitrise OTA App Deployment
menu:
  deployment-tutorials:
    weight: 2

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
