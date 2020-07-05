# French language support for Pathfinder 2e in Foundry VTT / Langue Française pour le système de jeu PF2 dans Foundry VTT
1. Traduction par rectulo à partir de la version officielle de Black Book Editions
2. Appuyé par Styx31

## Nous rejoindre
1. Vous pouvez retrouver toutes les mises à jour en français pour FoundryVTT sur le discord officiel francophone
2. Lien vers [Discord Francophone](https://discord.gg/pPSDNJk)

## Installation

1. Copy this link and use it in Foundrys module manager to install the module. Copier ce lien et chargez-le dans le menu modules de Foundry
    > https://gitlab.com/pathfinder-fr/foundryvtt-pathfinder2e-lang-fr/-/raw/master/module.json
2. Enable the module in your worlds module settings/Activez le module dans le menu de configuration de votre monde

## Remerciements, vielen danke & Many thanks to :
1. Henry4K : German translation and help
2. Hooking : System and english version
3. Noires/Cyriak : improvements with i18n-editor

## Modifier le module
Avant de pousser une nouvelle Release, il faut :
1. Modifier le fr.json avec les changements, puis valider : commit changes
2. Puis éditer module.json en changeant à deux endroits les numéros de la version.
3. Puis valider : commit changes

## Pousser une nouvelle Release
En ce qui concerne la nomenclature du numéro de version
1. Mettre le numéro de version avec v collé devant : par ex : v1.8.0A
2. Nous suivons la version Anglaise du système en numéro de version, afin que les utilisateurs puissent voir rapidement à quel niveau de traduction nous sommes. 
3. Par exemple si la version anglaise est actuellement en 1.8.0, lorsque de la première traduction, le même numéro de version sera v1.8.0
4. Si par la suite, d'autres mises à jour au cours de la même version anglaise (1.8.0), nous mettrons à la suite une lettre de l'alphabet.
5. Par exemple version anglaise en 1.8.0, la deuxième MAJ française de cette version sera v1.8.0A.
6. Puis éditer module.json en changeant à deux endroits les numéros de la version. 
7. Remplir les renseignements sur les raisons du changements. Si le changement est justifié par des modifications du projet anglo-saxon, indiquer le numéro de version pris en compte si possible.

Une fois que vous avez fait tous les changements, il faut mettre à jour le master afin de créer la nouvelle Release.
1. Aller dans tags/étiquette
2. tag name : mettre le numéro de version avec v collé devant : par ex : v1.8.0A
3. notes de version : détailler les modifications apportées par le changement. Par ex. correction sur tel aspect, ajout de telle fonctionnalité, mise à jour...
4. Créer le tag/étiquette
5. Aller dans Graph
6. Pour que votre nouvelle release soit valide, il faut que la toute première ligne du graphique soit le "numéro de version de la release" suivi de "master".


## Déclarer sur Foundry les changements
- Demander à rectulo qui dispose des droits de déclarer sur Foundry la MAJ

## Mise à jour du readme.md
- 05/07/2020 par Sasmira.