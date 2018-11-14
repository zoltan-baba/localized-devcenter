---
title: Most important concepts
redirect_from:
- "/bitrise-cli/most-important-concepts.md"
menu:
  bitrise-cli:
    weight: 13

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}