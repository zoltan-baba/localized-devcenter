---
title: I can't see my GitHub organization / repository on the Add New App page
menu:
  faq:
    weight: 8

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
