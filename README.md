# French language support for Pathfinder 2e in Foundry VTT / Langue Française pour le système de jeu PF2 dans Foundry VTT
1. Traduction à partir de la version officielle de Black Book Editions puis traduction libre par Rectulo
2. Appuyé par Styx31 & Sasmira

## Nous rejoindre
1. Vous pouvez retrouver toutes les mises à jour en français pour FoundryVTT sur le discord officiel francophone
2. Lien vers [Discord Francophone](https://discord.gg/pPSDNJk)

## Installation

1. Copy this link and use it in Foundry module manager to install the module. Copier ce lien et chargez-le dans le menu modules de Foundry
    > https://gitlab.com/pathfinder-fr/foundryvtt-pathfinder2e-lang-fr/-/raw/master/module/module.json
2. Enable the module in your worlds module settings/Activez le module dans le menu de configuration de votre monde

## Remerciements, vielen danke & Many thanks to :
1. Henry4K : German translation and help to start
2. Hooking : System and english version
3. Noires/Cyriak : amélioration et maintien en passant par i18n-editor

## Modifier le module
Avant de pousser une nouvelle Release, il faut :
1. Modifier le fr.json avec les changements, puis valider : commit changes
2. Puis éditer module.json en changeant à deux endroits les numéros de la version.
3. Puis valider : commit changes

## Pousser une nouvelle Release
En ce qui concerne la nomenclature du numéro de version
1. Mettre le numéro de version avec v collé devant : par ex : v2.5.0
2. Nous suivons la version Anglaise du système en récupérant le numéro de version à la date de la mise à jour, afin que les utilisateurs puissent voir rapidement à quel niveau de traduction nous sommes. 
3. Par exemple si la version anglaise est actuellement en 2.4.0, nous utilisons le même numéro de version soit v2.4.0
4. Si par la suite, d'autres mises à jour sont éditées pour la même version anglaise du système (2.4.0), nous mettrons à la suite une lettre de l'alphabet pour distinguer. Par exemple version anglaise en 2.4.0, la deuxième MAJ française de cette version sera v2.5.0A.
5. Puis éditer module.json en changeant à deux endroits les numéros de la version. 
6. Remplir les renseignements sur les raisons du changement. Si le changement est justifié par les évolutions du projet anglo-saxon, indiquer le numéro de version pris en compte si possible.

Une fois que les changements sont faits, il faut mettre à jour le master afin de créer la nouvelle Release.
1. Aller dans tags/étiquette
2. tag name : mettre le numéro de version avec v collé devant : par ex : v1.8.0A
3. notes de version : détailler les modifications apportées par le changement. Par ex. correction sur tel aspect, ajout de telle fonctionnalité, mise à jour...
4. Créer le tag/étiquette
5. Aller dans Graph/Graphique
6. Pour que la nouvelle release soit valide et ait été prise en compte, il faut que la toute première ligne du graphique soit le "numéro de version de la release" suivi de "master".

## Déclarer sur Foundry les changements
- Pour informer la communauté des changements, il faut les déclarer dans la console admin et demander à rectulo qui dispose des droits.

## Mise à jour du readme.md
- 26/06/2021 par Rectulo.
