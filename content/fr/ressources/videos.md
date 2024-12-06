---
title: Vidéos
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Vidéos
  order: 2
---

L'intro qui va bien

<h2>Série MiNumEco</h2>
{% set tags = collections['Vidéo'] | getAllTags %}
{% if tags | hasTag('MiNumEco') %}
	{% set postslist = collections['Vidéo'] %}
	{% include "postslist.njk" %}
{% endif %}

<h2>Toutes les vidéos</h2>
{% set postslist = collections['Vidéo'] | reverse %}
{% include "postslist.njk" %}
