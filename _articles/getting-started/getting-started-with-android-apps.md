---
title: Getting started with Android apps
date: 2018-09-21 08:47:45 +0000
redirect_from:
- "/getting-started/Getting-started-with-Android-apps/"
- "/getting-started/Getting-started-with-android-apps/"
- "/getting-started/getting-started-with-Android-apps/"
menu:
  getting-started:
    weight: 10

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
