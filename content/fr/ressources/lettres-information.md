---
title: Lettres d'information
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Lettres d'information
  order: 4
---

On publie des lettres d'informations sur Linkedin.

<a href="https://www.linkedin.com/newsletters/7242864226900279296/?displayConfirmation=true" target="_blank" class="fr-btn" title="S‘abonner à notre lettre d’information">S'abonner</a>

<h2>Tous les lettres précédentes</h2>
plkop
{% set postslist = collections['lettre-d-information'] | reverse %}
{% include "postslist.njk" %}
