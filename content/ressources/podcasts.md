---
title: Podcasts
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Podcasts
  order: 3
---

## Saison 1
{% set postslist = collections.Podcast | series("Saison 1") %}
{% include "postslist.njk" %}

## Tous les podcasts
{% set postslist = collections.Podcast | reverse %}
{% include "postslist.njk" %}
