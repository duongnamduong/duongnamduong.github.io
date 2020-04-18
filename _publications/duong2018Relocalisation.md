---
title: "Relocalisation Robuste de Caméra en Temps Réel pour la Réalité Augmentée par une Approche Hybride combinant Réseaux de Neurones et Méthodes Géométriques"
collection: publications
permalink: /publication/duong2018Relocalisation
date: 2018-06-07 01:00:00 +0100
venue: 'RFIAP'
paperurl: 'https://hal.archives-ouvertes.fr/hal-01831786/document'
pubtype: 'conference'
authors: 'Nam-Duong Duong, Amine Kacete, Catherine Soladie, Pierre-Yves Richard, Jérôme Royan'
excerpt_separator: ""
---
La relocalisation des caméras se signale comme une problématique centrale dans le domaine émergent de la réalité augmentée. Les approches les plus courantes pour la traiter, regroupées sous l'appellation générique de méthodes géométriques, ont pour noms SLAM (Simultaneous Localization And Mapping) et SfM (Structure from Motion). Les rapides progrès de l'apprentissage automatique, en particulier ceux de l'apprentissage en profondeur, ont également offert de nouvelles perspectives prometteuses à cette problématique. De premières tentatives ont récemment été faites pour combiner les deux types d'approches. Cependant, la lourdeur des algorithmes utilisés rend difficile leur exploitation dans le contexte temps réel sous-jacent à la réalité augmentée. De plus, les prédictions concernant la pose d'une caméra restent incertaines, n'étant encore assorties d'aucun score de confiance. Dans cet article , nous proposons une méthode hybride mélangeant à la fois les approches de l'apprentissage en profondeur et les approches géométriques pour estimer la pose d'une caméra indépendamment image par image. Nous présentons un réseau de neurones convolutif (CNN) léger, appelé xyzNet pour calculer en temps réel et robustement par régression les coordonnées dans le repère du monde des points réels associés aux pixels d'une image. Ensuite, l'information géométrique sur les correspondances 2D-3D permet l'élimination des prédictions ambiguës et le calcul d'une pose de caméra plus précise. De plus, nous montrons des résultats favorables quant à l'exactitude et la performance de notre méthode sur des ensembles de données différents ainsi que sa capacité à relever les défis concernant la scène dynamique.