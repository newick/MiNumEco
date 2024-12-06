---
title: Podcasts
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Podcasts
  order: 3
---


On enregistre des podcasts et ils sont cools !

<h2>Tous les podcasts</h2>
{% set postslist = collections.Podcast | reverse %}
{% include "postslist.njk" %}
