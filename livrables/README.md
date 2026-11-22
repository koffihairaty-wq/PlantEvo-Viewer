
# PlantEvo Viewer 🌿

## Présentation du projet

PlantEvo Viewer est un projet pédagogique réalisé dans le cadre de notre formation à la Digital Farming School (DFS).

À travers ce projet, nous cherchons à mieux comprendre l'évolution du monde végétal et les innovations qui ont permis aux plantes de s'adapter à différents milieux.

Notre travail associe des observations sur le terrain, des recherches botaniques, la cartographie et la création d'un site web.

## Objectifs

- Découvrir six groupes végétaux et leurs caractéristiques.
- Comprendre les principales innovations évolutives.
- Identifier les appareils végétatifs et reproducteurs.
- Collecter des observations et des coordonnées GPS.
- Représenter les observations sur une carte SIG.
- Présenter les résultats dans un site web pédagogique.

## Les six groupes végétaux

Les groupes étudiés sont :

1. Les algues
2. Les mousses
3. Les fougères
4. Les gymnospermes
5. Les graminées
6. Les dicotylédones

Pour chaque groupe, nous nous intéressons à son organisation, sa reproduction et ses adaptations.

## Collecte des données

Les observations ont été réalisées à l'INP-HB de Yamoussoukro.

Nous avons utilisé KoboCollect pour enregistrer les informations sur les végétaux observés, notamment :

- Le groupe végétal
- Le nom renseigné
- Le milieu d'observation
- Les photographies
- Les coordonnées GPS

Six observations ont été enregistrées le 21 novembre 2026.

Les données ont ensuite été consultées dans KoboToolbox et exploitées pour les fiches agronomiques et la carte SIG.

## Réalisation de la carte SIG

Nous avons utilisé QGIS pour représenter les positions géographiques des six groupes végétaux.

Les principales étapes étaient :

1. Préparer les données dans un fichier CSV.
2. Importer les coordonnées GPS dans QGIS.
3. Ajouter le fond de carte OpenStreetMap.
4. Attribuer une couleur à chaque groupe végétal.
5. Afficher les noms des groupes sur la carte.
6. Ajouter un titre, une légende, une échelle et le nord.
7. Exporter la carte au format PNG.
8. Intégrer la carte dans le site web.

Le projet QGIS et la carte exportée sont conservés dans les dossiers du projet.

## Développement du site web

Le site PlantEvo Viewer est développé avec :

- HTML pour organiser les contenus.
- CSS pour la présentation visuelle.
- Visual Studio Code pour écrire et modifier le code.

Nous n'avons pas utilisé JavaScript.

Le site comprend une page d'accueil, une page présentant les collections végétales, des pages consacrées aux six groupes, une carte SIG et une page À propos.

Les pages d'accueil, de collections, des algues et de la carte SIG ont été travaillées. Les autres pages restent à compléter.

## Maquettes Figma

Nous avons utilisé Figma pour préparer la présentation visuelle du projet.

Les maquettes permettent de visualiser l'organisation des pages et leur navigation.

**Lien du prototype :**

[Consulter les maquettes PlantEvo Viewer sur Figma](https://www.figma.com/proto/HgxHjDiNsZUZ9tOQDnCIdf/Sans-titre?node-id=10-2&p=f&viewport=-220%2C220%2C0.25&t=VxomEBjXtkl9dFbQ-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=10%3A2&page-id=0%3A1)

## Organisation des fichiers

```text
PlantEvo Viewer/
|
|-- css/
|   |-- style.css
|
|-- images/
|   |-- illustrations/
|   |-- logos/
|   |-- terrain/
|   |-- Carte-PlantEvo.png
|   |-- fond-accueil.jpeg
|
|-- sig/
|   |-- PlantEvo-SIG.qgz
|
|-- livrables/
|   |-- Rapports et fiches agronomiques
|
|-- index.html
|-- collections.html
|-- algues.html
|-- mousses.html
|-- fougeres.html
|-- gymnospermes.html
|-- graminees.html
|-- dicotyledones.html
|-- carte-sig.html
|-- a-propos.html
|-- README.md
```

## Livrables

Les documents du projet sont regroupés dans le dossier `livrables`.

Ils comprennent, selon leur état de finalisation :

- Le rapport SIG.
- Les six fiches agronomiques.
- La documentation technique.
- Les autres documents demandés dans le brief.

Les maquettes sont accessibles à partir du lien Figma indiqué plus haut.

## Sources des images

Nous avons utilisé deux types d'images :

**Photographies de terrain :** observations réalisées à l'INP-HB de Yamoussoukro.

**Illustrations scientifiques :** images issues notamment de Wikimedia Commons, utilisées pour expliquer les structures végétales, les modes de reproduction et les innovations évolutives.

Les références des illustrations, leurs auteurs et leurs licences sont renseignés dans les fiches agronomiques.

Fond cartographique : © OpenStreetMap contributors.

## Difficultés rencontrées

Ce projet nous a permis de découvrir plusieurs outils que nous ne maîtrisions pas encore entièrement.

Les principales difficultés ont concerné :

- L'organisation des fichiers et des images.
- La correspondance entre les chemins des fichiers HTML et CSS.
- La préparation et l'importation des coordonnées GPS dans QGIS.
- La création de la légende et de la mise en page cartographique.
- L'intégration de la carte dans le site web.

Nous avons corrigé ces difficultés progressivement, en testant les résultats à chaque étape.

## Ce que nous avons appris

Grâce à ce projet, nous avons appris à :

- Structurer des pages en HTML.
- Utiliser le CSS pour construire une interface.
- Organiser les fichiers d'un projet web.
- Collecter et exploiter des données de terrain.
- Réaliser une carte à partir de coordonnées GPS.
- Utiliser Git pour suivre les modifications du projet.

## État du projet

PlantEvo Viewer est encore en cours de finalisation.

Les éléments réalisés sont conservés dans ce dépôt GitHub. Les pages et documents restants seront complétés progressivement.

## Remerciements

Nous remercions les coachs de la Digital Farming School pour leur accompagnement dans la réalisation de ce projet.

---

**PlantEvo Viewer — Digital Farming School**

*Observer, comprendre et découvrir l'évolution du monde végétal.*
