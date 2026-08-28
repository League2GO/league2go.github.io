---
title: "Gérer les joueurs : numéros, positions, forces et notes"
lang: fr
localization: managing-players
category: managers
order: 30
description: "Attribuez numéros de chandail, positions et forces, et conservez des notes privées sur vos joueurs."
redirect_from:
  - /numeros-de-chandail/
  - /forces-de-joueur/
---
Une fois vos joueurs [ajoutés à votre ligue](/ajouter-des-joueurs/), vous pouvez enrichir leur profil avec un numéro de chandail, des positions, une force et des notes privées. Ce guide couvre chacun de ces éléments.

## Numéros de chandail

Pour attribuer un numéro de chandail, modifiez le joueur à partir de l'onglet **Équipes** et saisissez le numéro. Les numéros de chandail sont affichés à côté du nom des joueurs, ce qui rend les alignements et le [jour de partie](/jour-de-partie/) plus faciles à suivre.

{% include image.html src="help/player-edit-jersey-number.fr.png" caption="Le formulaire de modification d'un joueur avec le numéro de chandail rempli." %}

Vous pouvez aussi changer le numéro d'un joueur **pour une seule partie** à partir des menus d'actions dans le détail de la partie, pratique quand un joueur emprunte un chandail. Ces menus permettent aussi de saisir le numéro des remplaçants.

{% include image.html src="help/game-set-jersey-menu.fr.png" caption="Le menu d'actions d'un joueur sur la page d'une partie, avec l'action assigner un numéro de chandail pour cette partie." %}

## Positions

Chaque joueur et remplaçant a une ou plusieurs positions, choisies parmi la configuration de positions de votre ligue (définie par le sport dans les [paramètres de votre ligue](/creer-votre-ligue/)). Les positions comptent pour deux raisons :

* Elles structurent vos alignements de partie.
* La [recherche automatique de remplaçants](/recherche-de-remplacants/) contacte les remplaçants pouvant jouer la position du joueur absent. Cochez toutes les positions qu'un remplaçant peut jouer pour qu'il soit contacté le plus souvent possible.

## Forces des joueurs

Les forces vous aident à garder vos équipes balancées et à trouver des remplaçants du bon niveau.

### Activer et configurer les forces

Activez les forces de joueur dans l'onglet **Général** des paramètres de votre ligue. Choisissez l'échelle qui convient à votre ligue :

* **Lettres** : « AAA », « AA », « BB », « CC », « A », « B », « C » et « D ».
* **Nombres** : de 1 à 1000 (ou simplement de 1 à 100) pour plus de flexibilité.

{% include image.html src="help/player-skill-settings.fr.png" caption="Paramètres > Général avec les forces des joueurs activées et le choix entre l'échelle en lettres ou en nombres." %}

### Assigner des forces aux joueurs

Dans les onglets **Équipes** et **Remplaçants**, assignez une force à chaque joueur. Vous devez entrer une force pour chaque position du joueur. La force est affichée sous le nom du joueur dans les tableaux d'équipes et de remplaçants. Si un joueur n'a pas de force configurée, un point d'exclamation s'affiche à côté de lui dans le tableau pour signaler le problème.

{% include image.html src="help/player-skill-ratings.fr.png" caption="L'alignement avec la force de chaque joueur à côté de son nom, et l'avertissement sur un joueur dont la force est manquante." %}

Les forces sont visibles seulement par les gestionnaires de la ligue et les capitaines d'équipe : les joueurs ne voient pas comment vous les avez évalués. <!-- TODO: verify -->

### À quoi servent les forces

* **Recherche automatique de remplaçants** : quand un joueur déclare une absence, League2GO contacte les remplaçants dont la force se situe dans une plage relative à celle du joueur absent. Vous contrôlez à quel point cette plage est stricte ou flexible; voir les [options de recherche de remplaçants](/options-de-recherche-de-remplacants/).
* **Sélection manuelle** : les forces sont affichées dans le détail des parties, ce qui vous permet de choisir vous-même un remplaçant d'un niveau similaire. Quand vous ajoutez un emplacement à une partie, vous pouvez aussi spécifier la force requise pour le combler automatiquement avec un joueur du bon niveau.

## Notes privées sur les joueurs

Vous pouvez rédiger des notes au sujet de chaque joueur ou remplaçant de votre ligue : par exemple des rappels de paiement, des disponibilités particulières ou toute information utile à votre gestion. Les notes sont visibles seulement par les gestionnaires de la ligue et les capitaines de l'équipe du joueur ; les joueurs ne les voient jamais.

{% include image.html src="help/player-notes-field.fr.png" caption="Le champ notes du formulaire de modification d'un joueur; les notes ne sont visibles que par les gestionnaires et les capitaines." %}

Des questions ? Écrivez-nous à [info@league2go.com](mailto:info@league2go.com).
