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
			url: "/publications/referentiel-competences/",
			title: "Référentiel de compétences",
			description: ""
		}) }}
	</div>
	<div class="fr-col-12 fr-col-md-4">
		{% from "components/component.njk" import component with context %}
		{{ component("card", {
			url: "/ressources/lettres-information/",
			title: "Lettres d'information",
			description: "Relire nos lettres d'information"
		}) }}
	</div>
</div>
