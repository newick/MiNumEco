---
title: Documents de référence
layout: layouts/landing.njk
eleventyNavigation:
  parent: ressources
  title: Documents de référence
  order: 1
---

<div class="fr-grid-row fr-grid-row--gutters fr-mb-6v">
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/publications/referentiel-general-ecoconception/",
			title: "Référentiel général d'écoconception de services numériques (RGESN)",
			image: {
				src: "/img/referentiel-general-ecoconception/referentiel-ecoconception.webp",
				alt: ""
			}
		}) }}
	</div>
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/publications/guide-pratique-achats-numeriques-responsables/",
			title: "Guide pratique pour des achats numériques responsables",
			image: {
				src: "/img/guide-pratique-achats-numeriques-responsables/guide-achats-numerique-responsable.webp",
				alt: ""
			}
		}) }}
	</div>
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/publications/bonnes-pratiques/",
			title: "Guide de bonnes pratiques numérique responsable pour les organisations",
			image: {
				src: "/img/bonnes-pratiques/guide-bonnes-pratiques-vignette.webp",
				alt: ""
			}
		}) }}
	</div>
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/formations/referentiel-competences/",
			title: "Référentiel de compétences",
			image: {
				src: "/img/parcours-formation-numeco.webp",
				alt: ""
			}
		}) }}
	</div>
</div>

## Actualités et autres documents

{% set postslist = [] %}
{% for item in collections['Document de référence'] %}
	{% if item.data.layout and 'layouts/post.njk' in item.data.layout %}
		{% set postslist = postslist.concat(item) %}
	{% endif %}
{% endfor %}
{% set postslist = postslist | reverse %}
{% include "postslist.njk" %}
<a href="/actualites/tags/document-de-reference/">Parcourir tous nos documents de référence</a>
