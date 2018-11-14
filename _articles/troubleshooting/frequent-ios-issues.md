---
title: Frequent iOS issues
redirect_from:
- "/ios/frequent-ios-issues/"
- "/ios/frequent-ios-issues/#works-in-local-but-not-on-bitriseio"
- "#works-in-local-but-not-on-bitriseio"
menu:
  troubleshooting:
    weight: 4

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}