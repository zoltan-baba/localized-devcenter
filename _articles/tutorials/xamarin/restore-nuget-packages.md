---
title: Restore NuGet packages
redirect_from:
- "/xamarin/restore-nuget-packages"
menu:
  xamarin:
    weight: 2

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}