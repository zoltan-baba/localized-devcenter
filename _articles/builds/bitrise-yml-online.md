---
title: Accessing the bitrise.yml file online
redirect_from:
- "/bitrise-cli/bitrise-yml-online/"
- "/bitrise-cli/bitrise-yml-online"
menu:
  builds:
    weight: 7

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}