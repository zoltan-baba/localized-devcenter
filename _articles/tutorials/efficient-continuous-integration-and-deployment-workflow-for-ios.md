---
title: Efficient Continuous Integration and Deployment Workflow for iOS development
menu:
  tutorials:
    weight: 9

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
