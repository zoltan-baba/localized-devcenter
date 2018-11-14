---
title: Connecting your GitHub/GitLab/Bitbucket account to Bitrise
redirect_from:
- "/getting-started/adding-a-new-app/connecting-account-bitrise"
menu:
  signing-up:
    weight: 5

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}