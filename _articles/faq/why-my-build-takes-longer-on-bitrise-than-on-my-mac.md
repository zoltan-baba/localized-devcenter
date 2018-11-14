---
title: Why my build takes longer on Bitrise than on my Mac?
menu:
  faq:
    weight: 10

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}