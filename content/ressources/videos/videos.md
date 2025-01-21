---
title: Vidéos
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Vidéos
  order: 2
---
<article class="fr-mb-6w">
	{% set seriesName = "Paroles d'experts" %}
	<h2>Série {{seriesName}}</h2>
	{% set postslist = collections['Vidéo'] | series(seriesName) | limit(3) %}
	{% include "postslist.njk" %}
	<a href="/videos/serie/{{ seriesName | slugify }}">Voir toutes les vidéos de la série {{seriesName}}</a>
</article>

<article class="fr-mb-6w">
	{% set seriesName = "Référents" %}
	<h2>Série {{seriesName}}</h2>
	{% set postslist = collections['Vidéo'] | series(seriesName) | limit(3) %}
	{% include "postslist.njk" %}
	<a href="/videos/serie/{{ seriesName | slugify }}">Voir toutes les vidéos de la série {{seriesName}}</a>
</article>

<article class="fr-mb-6w">
	{% set seriesName = "Autres vidéos" %}
	<h2>Série {{seriesName}}</h2>
	{% set postslist = collections['Vidéo'] | noSeries | limit(3) %}
	{% include "postslist.njk" %}
	<a href="/videos/serie/{{ seriesName | slugify }}">Voir toutes les vidéos de la série {{seriesName}}</a>
</article>
