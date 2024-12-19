---
title: Podcasts
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Podcasts
  order: 3
---
## Tous les podcasts
{% set postslist = collections.Podcast | reverse %}
{% include "postslist.njk" %}
