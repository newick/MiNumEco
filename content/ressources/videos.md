---
title: Vidéos
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Vidéos
  order: 2
---
<h2>Série Référents</h2>

<h2>Toutes les vidéos</h2>
{% set postslist = collections['Vidéo'] | reverse %}
{% include "postslist.njk" %}
