---
title: Steps
redirect_from:
- "/getting-started/builds-and-workflows/getting-started/getting-started-steps"
- "/getting-started/manage-your-bitrise-workflow/"
menu:
  getting-started:
    weight: 8

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
