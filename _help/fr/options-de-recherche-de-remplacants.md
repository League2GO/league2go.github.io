---
title: "Options de la recherche de remplaçants"
lang: fr
localization: substitute-search-settings
category: substitutes
order: 20
description: "La référence de chaque option de l'onglet Remplaçants : délais, cibles, plages de force, favoris, plage ne pas déranger et prix."
redirect_from:
  - /fonctionnalites-moins-connues-partie2/
---

Voici la référence de chaque option qui contrôle la [recherche automatique de remplaçants](/recherche-de-remplacants/). Sauf indication contraire, toutes les options se trouvent dans les **paramètres de votre ligue, onglet Remplaçants**. Les listes de remplaçants elles-mêmes se gèrent ailleurs; consultez [gérer les remplaçants](/gerer-les-remplacants/).

{% include image.html src="help/substitute-settings-options.fr.png" caption="Paramètres de la ligue > Remplaçants : le moment où la recherche démarre (jours avant la partie) et la séquence de recherche étape par étape avec ses délais." %}

## Début de la recherche

**Ce que ça fait :** détermine combien de jours avant une partie les demandes de remplacement commencent à être envoyées. Une absence déclarée plus tôt attend l'ouverture de cette fenêtre; une absence déclarée plus tard déclenche la recherche immédiatement.

**Quand l'ajuster :** raccourcissez le délai si vos remplaçants acceptent puis oublient les parties lointaines; allongez-le si vos parties sont difficiles à combler.

**Réglez-le à 0 pour désactiver complètement la recherche automatique.** Aucune demande n'est envoyée et vous [choisissez les remplaçants manuellement](/gerer-les-remplacants/) pour chaque partie.

**Exemple :** avec une recherche qui débute 7 jours avant les parties, une absence déclarée 3 semaines d'avance reste en attente jusqu'à 7 jours avant la partie, puis les demandes partent.

## Rappel automatique aux remplaçants

**Ce que ça fait :** envoie un rappel automatique, un nombre configurable de jours avant la partie, aux remplaçants qui ont reçu une demande sans y répondre.

**Quand l'ajuster :** placez-le assez près de la partie pour créer un sentiment d'urgence, tout en laissant à la recherche le temps de s'étendre à d'autres remplaçants ensuite.

**Exemple :** les demandes partent 7 jours avant la partie; le rappel est réglé à 2 jours avant. Un remplaçant qui a ignoré le premier message reçoit une relance 2 jours avant la partie.

## Nombre de joueurs cible par équipe

**Ce que ça fait :** détermine combien de joueurs vous voulez dans l'alignement de chaque équipe, par position. Une recherche ne démarre que lorsqu'une absence fait descendre l'alignement **sous** la cible. Si vous avez plus de réguliers que la cible, les premières absences ne déclenchent rien.

**Quand l'ajuster :** faites-le correspondre au nombre de joueurs qui jouent réellement dans votre ligue.

**Exemple :** cible de 10 joueurs, équipe de 11 réguliers. La première absence déclarée laisse 10 joueurs disponibles : aucune recherche. La deuxième absence fait descendre l'alignement à 9 et démarre une recherche pour un remplaçant.

## Forces et plages de force

Les forces permettent à la recherche de proposer des remplaçants de calibre comparable au joueur absent.

**Choisir l'échelle :** dans l'onglet **Général** des paramètres de votre ligue, choisissez des lettres (« AAA », « AA », « BB », « CC », « A », « B », « C », « D ») ou des nombres (de 1 à 1000; utilisez de 1 à 100 si c'est votre besoin) comme échelle de force. Les forces sont visibles seulement par les capitaines des équipes et les gestionnaires de la ligue. Vous assignez ensuite une force à chaque joueur et remplaçant, pour chacune de ses positions; consultez [gérer les remplaçants](/gerer-les-remplacants/).

**La plage est toujours relative au joueur absent.** Lorsqu'un joueur est absent, seuls les remplaçants dont la force se situe dans la plage configurée autour de la force de ce joueur sont contactés. Trois façons de la configurer :

* **Aucun critère de force :** vous voulez noter les forces pour votre propre référence, mais n'importe quel remplaçant peut remplacer n'importe qui. Étendez la plage au maximum (-1000 à 1000) et assurez-vous que l'option « Étendre les forces progressivement » est **désactivée**.
* **Stricte :** configurez la plage requise et n'activez pas « Étendre les forces progressivement ». Les remplaçants hors de la plage ne sont jamais contactés pour cette absence.
* **Flexible :** configurez une **plage initiale**, activez « Étendre les forces progressivement », configurez la **plage finale**, puis entrez le nombre d'heures pour élargir la plage progressivement. La recherche commence par les remplaçants les plus proches, puis accepte graduellement des remplaçants plus éloignés de la force du joueur absent, utile si un alignement complet compte plus qu'une correspondance parfaite.

{% include image.html src="help/substitute-settings-rating-range.fr.png" caption="La section des plages de force : la plage initiale, l'option Étendre les forces progressivement activée, le nombre de minutes pour atteindre la plage finale, et la plage finale." %}

**Exemple (flexible) :** un joueur de force « A » déclare son absence. La plage initiale contacte les remplaçants de force « C » à « BB ». Après 4 heures, la plage s'élargit de « D » à « AA », puis après 8 heures de « D » à « AAA ». La limite inférieure s'arrête à « D » parce que c'est la force la plus faible de l'échelle.

## Favoris et ordre de contact

**Ce que ça fait :** la recherche contacte les remplaçants par niveaux, les favoris d'abord : **favoris de l'équipe, puis remplaçants de l'équipe, puis favoris de la ligue, puis remplaçants de la ligue**. Vous configurez le délai entre chaque niveau; le niveau suivant n'est contacté qu'après ce délai, si la place est toujours libre. Les favoris sont marqués avec l'étoile à droite de chaque remplaçant; consultez [gérer les remplaçants](/gerer-les-remplacants/).

**Quand l'ajuster :** utilisez des délais courts si combler la place rapidement compte plus que l'identité du remplaçant; utilisez des délais plus longs pour donner une vraie longueur d'avance à vos remplaçants les plus fiables.

**Exemple :** avec un délai de 4 heures entre les niveaux, les favoris de l'équipe reçoivent la demande en premier; 4 heures plus tard, les autres remplaçants de l'équipe s'ajoutent, puis les favoris de la ligue, puis le reste de la liste de la ligue.

## Période où un joueur ne peut plus déclarer son absence

**Ce que ça fait :** détermine un nombre d'heures avant la partie durant lesquelles les joueurs ne peuvent plus déclarer eux-mêmes une absence. Cela évite les déclarations de dernière minute que la recherche n'a pas le temps de combler; le joueur doit alors vous contacter, et c'est vous qui décidez de la suite.

**Quand l'ajuster :** réglez-la environ au préavis minimal dont vos remplaçants ont besoin pour se présenter.

**Exemple :** avec une période de 6 heures, un joueur ne peut pas déclarer une absence à 17 h pour une partie à 20 h.

## Plage ne pas déranger

**Ce que ça fait :** définit une plage de temps durant laquelle aucun message automatisé n'est envoyé à vos joueurs. Les demandes qui tomberaient dans la plage sont retenues puis envoyées lorsqu'elle se termine, jamais annulées. Les délais configurés entre les remplaçants favoris et les autres remplaçants sont respectés.

**Quand l'ajuster :** activez-la pour qu'une absence déclarée à minuit ne réveille pas votre liste de remplaçants.

**Exemple :** plage ne pas déranger de 22 h à 8 h. Une absence déclarée à 23 h envoie ses premières demandes à 8 h le lendemain matin.

## Prix dans les demandes de remplacement

**Ce que ça fait :** lorsque vous cochez **Inclure les prix dans les demandes de remplacement**, le montant que le remplaçant paie pour jouer est inclus dans chaque demande, ainsi que dans le message envoyé à un remplaçant que vous assignez manuellement. Vous entrez un montant par position, et les positions peuvent différer : par exemple 20 $ pour un défenseur ou un attaquant, mais gratuit pour un gardien de but.

**Quand l'ajuster :** activez l'option pour que les remplaçants se présentent en sachant ce qu'ils doivent. Pour percevoir le montant en ligne plutôt qu'en argent comptant, consultez [les paiements en ligne](/configurer-les-paiements-en-ligne/).

{% include image.html src="help/substitute-settings-prices.fr.png" caption="Inclure les prix dans les demandes de remplacement : une fois l'option cochée, chaque position a son propre champ de prix." %}

## Correspondance des positions

La correspondance des positions est toujours active : un remplaçant n'est contacté que pour remplacer un joueur dont il joue la position. Les positions proviennent de la configuration de votre ligue, et vous cochez les positions que chaque remplaçant peut jouer dans son profil. Cochez toutes celles qu'il peut couvrir pour qu'il soit contacté le plus souvent possible. Consultez [gérer les remplaçants](/gerer-les-remplacants/).

Des questions ? Écrivez-nous à [info@league2go.com](mailto:info@league2go.com).
