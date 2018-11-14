---
title: Quick start guide to Bitrise
redirect_from:
- "/getting-started/adding-a-new-app/"
- "/getting-started/create-your-first-app-on-bitrise/"
- "/getting-started/add-your-first-step-to-your-workflow/"
menu:
  getting-started:
    weight: 1

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}