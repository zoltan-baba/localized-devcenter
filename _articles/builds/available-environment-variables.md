---
title: Available environment variables
redirect_from:
- "/faq/available-environment-variables/"
- "/faq/available-environment-variables/#exposed-by-the-bitrise-cli"
menu:
  builds:
    weight: 11

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}