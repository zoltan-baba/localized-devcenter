---
title: Deploy your Xamarin app
redirect_from:
- "/xamarin/deploy-your-xamarin-app/"
- "/xamarin/deploy-your-xamarin-app"
menu:
  xamarin:
    weight: 4

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}
