---
title: Don't mark the Build as failed if a given step would fail (ignore the error
  of the Step)
menu:
  tips-and-tricks:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
