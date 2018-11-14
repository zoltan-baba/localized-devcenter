---
title: Steps in YAML
redirect_from:
- "/bitrise-cli/steps/"
- "/bitrise-cli/steps"
menu:
  bitrise-cli:
    weight: 6

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
