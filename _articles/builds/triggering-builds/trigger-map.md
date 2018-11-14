---
title: Using the Trigger Map to trigger builds
redirect_from:
- "/webhooks/trigger-map/"
- "/webhooks/trigger-map"
menu:
  triggering-builds:
    weight: 5
    title: Triggering builds with the Trigger map

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
