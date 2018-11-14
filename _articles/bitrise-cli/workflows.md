---
title: Workflows in YAML
redirect_from:
- "/bitrise-cli/workflows/"
- "/bitrise-cli/workflows"
menu:
  bitrise-cli:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
