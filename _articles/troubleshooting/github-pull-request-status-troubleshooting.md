---
title: Build status indicator on GitHub/GitLab/Bitbucket does not work
redirect_from:
- "/faq/github-pull-request-status-troubleshooting"
- "/faq/github-pull-request-status-troubleshooting/"
- "/faq/github-pull-request-status-troubleshooting/#make-sure-to-select-a-service-credential-user-who-has-a-connected-github-account"
menu:
  troubleshooting:
    weight: 7

---
{% capture filename %}{{ page.url}}{% endcapture %}
{% assign num = filename | size | minus: 1 %}
{% translate_file {{ filename | slice: 0, num | replace_first:'/','' | append: ".md" }} %}