---
title: Vidéos
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Vidéos
  order: 2
---
<h2>Série Paroles d'experts</h2>
{% set postslist = collections['Vidéo'] | series("Paroles d'experts") %}
{% include "postslist.njk" %}

<h2>Série Référents</h2>
{% set postslist = collections['Vidéo'] | series("Référents") %}
{% include "postslist.njk" %}

<h2>Toutes les vidéos</h2>
{% set postslist = collections['Vidéo'] | reverse %}
{% include "postslist.njk" %}
