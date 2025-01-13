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
			description: ""
		}) }}
	</div>
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/publications/guide-pratique-achats-numeriques-responsables/",
			title: "Guide pratique pour des achats numériques responsables",
			description: ""
		}) }}
	</div>
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/publications/bonnes-pratiques/",
			title: "Guide de bonnes pratiques numérique responsable pour les organisations",
			description: ""
		}) }}
	</div>
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/publications/referentiel-competences/",
			title: "Référentiel de compétences",
			description: ""
		}) }}
	</div>
</div>
