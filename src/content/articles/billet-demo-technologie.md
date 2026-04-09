---
title: "Notes sur les modeles de langage et l'emergent"
description: "Quelques observations sur les capacites emergentes des grands modeles de langage"
date: 2026-03-01
lang: "fr"
tags: ["tech", "ia"]
type: "billet"
draft: false
---

On parle beaucoup de capacites "emergentes" dans les grands modeles de langage. L'idee est seduisante : a partir d'une certaine echelle, des comportements apparaissent que personne n'avait explicitement programmes. Un modele entraine a predire le token suivant se met a resoudre des problemes d'arithmetique, a traduire entre des langues peu representees dans ses donnees, ou a produire du code fonctionnel dans un langage qu'il n'a vu que marginalement. Pourtant, comme le montrent [certaines analyses recentes](https://arxiv.org/abs/2304.15004), une partie de ces "emergences" pourrait n'etre qu'un artefact de la metrique choisie. Quand on passe d'une evaluation `exact_match` a une evaluation continue, la courbe d'emergence se lisse en progression graduelle.

Cela ne signifie pas que rien d'interessant ne se passe. La capacite d'un modele a effectuer du `chain-of-thought reasoning` ou a manipuler des structures imbriquees reste remarquable. Mais il faut distinguer ce qui releve d'une veritable rupture qualitative et ce qui releve d'une amelioration quantitative rendue visible par un seuil de mesure. La prudence epistemique, ici comme ailleurs, reste la meilleure boussole.
