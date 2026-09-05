---
title: "Jour de partie : alignements et remplacements"
lang: fr
localization: game-day
category: managers
order: 60
description: "Gérez l'alignement et les emplacements d'une partie, remplacez les joueurs absents, imprimez ou exportez l'alignement."
redirect_from:
  - /gestion-amelioree-parties/
  - /imprimer-alignements/
  - /exporter-alignement-partie-csv/
  - /remplacement-joueur-equipe/
  - /notifcation-remplacement-gestionnaire/
---

Ce guide couvre ce que les gestionnaires font autour d'une partie : consulter l'alignement, gérer les emplacements, remplacer les joueurs absents, imprimer ou exporter l'alignement. Pour créer ou annuler des parties, consultez [calendrier et parties](/calendrier-et-parties/#créer-des-parties).

## L'alignement d'une partie

Ouvrez une partie pour voir son alignement : les joueurs de chaque équipe, leur position et leur statut pour cette partie. Les joueurs réguliers sont présumés présents à moins de déclarer une absence (voir [confirmation de présence](/confirmation-de-presence/) pour le mode où les joueurs confirment plutôt leur présence).

{% include image.html src="help/game-day-lineups.fr.png" caption="La page de la partie montre l'alignement des deux équipes : chaque emplacement avec le nom, le numéro et la position du joueur, et un emplacement laissé libre par une absence déclarée directement dans l'alignement." %}

## Les emplacements

Chaque place dans un alignement est un **emplacement**. Chaque emplacement possède un menu qui regroupe ses actions :

* Remplacer le joueur
* Démarrer une recherche automatique de remplaçants
* Rappeler les remplaçants
* Changer la position de l'emplacement

{% include image.html src="help/game-day-spot-menu.fr.png" caption="Le menu d'un emplacement regroupe toutes les actions sur un joueur : chercher un remplaçant, sélectionner un autre joueur, le changer d'équipe, changer sa position, et plus encore." %}

Les gestionnaires peuvent aussi **ajouter des emplacements supplémentaires** à une partie. Ces emplacements peuvent être comblés automatiquement par des remplaçants, ce qui permet aux équipes incomplètes de jouer avec un alignement complet. Lorsqu'il y a un emplacement libre dans chacune des deux équipes, le remplaçant peut choisir son équipe.

Vous pouvez réorganiser un alignement autour d'une absence. Par exemple, si votre lanceur est absent, remplacez-le par un voltigeur en changeant la position de l'emplacement, puis démarrez la recherche automatique de remplaçant pour l'emplacement de voltigeur devenu libre.

## Remplacer un joueur manuellement

Pour remplacer vous-même un joueur absent au lieu d'utiliser la recherche automatique, ouvrez le menu de l'emplacement et choisissez de remplacer le joueur. Dans la fenêtre de remplacement, vous pouvez sélectionner :

* un joueur de la même équipe,
* un joueur d'**une autre équipe** de la ligue : sélectionnez d'abord l'autre équipe, puis le joueur, ou
* un des remplaçants de votre ligue (voir [gérer les remplaçants](/gerer-les-remplacants/)).

{% include image.html src="help/game-day-replace-player-dialog.fr.png" caption="La fenêtre de remplacement : choisissez le remplaçant dans la banque de remplaçants, ou déployez n'importe quelle autre équipe de la ligue pour prendre un joueur dans son effectif." %}

Lorsque vous remplacez un joueur manuellement, vous pouvez choisir d'**envoyer automatiquement un message au joueur** pour l'avertir du changement, sans avoir à le contacter vous-même.

Pour le fonctionnement des recherches automatiques, consultez la [recherche de remplaçants](/recherche-de-remplacants/) et les [options de recherche de remplaçants](/options-de-recherche-de-remplacants/).

## Alignement simple ou trios

L'alignement peut être affiché de deux façons :

* **Alignement simple** : une liste de joueurs et de positions.
* **Trios** : les joueurs regroupés en trios d'attaque et en paires.

Une option permet de basculer entre les deux modes, pour que les ligues qui n'organisent pas de trios conservent l'affichage simple. <!-- TODO: vérifier le libellé exact et l'emplacement de l'option -->

{% include image.html src="help/game-day-lineup-type-toggle.fr.png" caption="Le sélecteur Type d'alignement dans l'éditeur d'alignement bascule l'affichage entre l'alignement simple et les trios d'attaque." %}

## Imprimer l'alignement

Pour imprimer l'alignement d'une partie, allez dans le détail de la partie et cliquez sur le bouton **« Imprimer l'alignement »**. Une page optimisée contenant l'information de la partie est générée. Vous pouvez afficher ces pages à l'aréna pour, par exemple, orienter les joueurs vers le bon vestiaire.

{% include image.html src="help/game-day-print-menu.fr.png" caption="Imprimer l'alignement se trouve dans le menu de la partie (le bouton rond en haut de la page de la partie) et ouvre une feuille d'alignement optimisée pour l'impression dans la boîte d'impression de votre navigateur." %}

## Exporter l'alignement en CSV

Pour noter les statistiques d'une partie sur papier ou dans un tableur, ouvrez la page de la partie et cliquez sur le bouton **« Exporter l'alignement »**. Un fichier CSV est téléchargé avec, pour chaque joueur, l'équipe, le numéro de chandail, le nom, la position et le classement. Ouvrez-le dans un tableur pour noter l'information de la partie, puis saisissez les résultats dans League2GO; voir [résultats, classement et statistiques](/resultats-classement-statistiques/).

Des questions ? Écrivez-nous à [info@league2go.com](mailto:info@league2go.com).
