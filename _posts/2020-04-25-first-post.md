---
layout: single
title: 'First post!'
tags: [git, n00b]
categories: [misc]
---

```
$ git remote add origin git@gitserver:/srv/git/project.git
```

{% capture fig_img %}
[![xkcd - git](/assets/images/xkcd-git.png)](https://xkcd.com/1597/)
{% endcapture %}

{% capture fig_caption %}
source: https://xkcd.com/1597/
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: “<p>” | remove: “</p>” }}
  <figcaption>{{ fig_caption | markdownify | remove: “<p>” | remove: “</p>” }}</figcaption>
</figure>
