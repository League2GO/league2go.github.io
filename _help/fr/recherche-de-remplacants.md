---
title: "Comment fonctionne la recherche automatique de remplaçants"
lang: fr
localization: substitutes-overview
category: substitutes
order: 10
description: "Ce qui déclenche une recherche, qui est contacté et dans quel ordre, et comment suivre son déroulement."
redirect_from:
  - /rappel-automatique-pour-remplacant/
---

Lorsqu'un joueur ne peut pas se présenter à une partie, League2GO peut trouver un remplaçant pour vous. Les remplaçants admissibles sont contactés automatiquement, par vagues, et le premier qui accepte obtient la place. Cet article explique le déroulement pour que vous puissiez vous y fier, et diagnostiquer la situation quand une partie reste incomplète.

Pour configurer le comportement décrit ici, consultez les [options de la recherche de remplaçants](/options-de-recherche-de-remplacants/). Pour bâtir et entretenir vos listes de remplaçants, consultez [gérer les remplaçants](/gerer-les-remplacants/).

## Ce qui déclenche une recherche

Une recherche démarre lorsqu'**un joueur déclare lui-même son absence** pour une partie. Si votre ligue fixe un [nombre cible de joueurs par équipe](/equipes-et-parametres/#nombre-cible-de-joueurs-par-position), la recherche ne démarre que si l'absence fait passer l'alignement sous cette cible : une équipe encore à la cible ou au-dessus n'a pas besoin de remplaçant, donc personne n'est contacté. Si la recherche automatique de votre ligue est **désactivée** (début de la recherche réglé à 0 jour avant les parties), rien ne démarre de soi-même et vous [choisissez les remplaçants manuellement](/gerer-les-remplacants/#choisir-un-remplaçant-manuellement).

Un gestionnaire peut aussi lancer une recherche. Lorsque vous déclarez une absence au nom d'un joueur, l'absence à elle seule ne déclenche **rien** : vous pouvez ainsi la noter sans envoyer de demandes, par exemple quand vous avez déjà un remplaçant en tête. Demandez explicitement la recherche lorsque vous voulez que League2GO trouve quelqu'un.

La recherche ne démarre pas forcément au moment où l'absence est déclarée. Les demandes commencent à partir un certain temps avant la partie, soit le nombre de jours que vous choisissez dans les paramètres de votre ligue. Une absence déclarée plus tôt attend simplement, et la recherche démarre quand la partie est à ce nombre de jours.

## Qui est contacté, et dans quel ordre

League2GO ne contacte pas tous vos remplaçants d'un coup. Les candidats sont contactés par vagues successives :

1. **Les favoris d'abord**, puis des cercles de remplaçants de plus en plus larges, avec un délai configurable entre chaque niveau.
2. Dans chaque vague, un remplaçant n'est contacté que s'il **joue la position du joueur absent**.
3. La **force du remplaçant doit se situer dans la plage configurée par rapport à la force du joueur absent**. Si votre ligue étend la plage progressivement, les remplaçants plus éloignés de la force du joueur absent sont contactés plus tard, à mesure que la plage s'élargit.

Les niveaux, les délais et les plages de force sont tous configurables; consultez les [options de la recherche de remplaçants](/options-de-recherche-de-remplacants/) pour chaque option.

Le **premier remplaçant qui accepte obtient la place** : l'alignement est mis à jour et toutes les personnes concernées sont avisées. Un remplaçant qui accepte trop tard est informé que la place est déjà comblée.

## Rappels aux remplaçants qui n'ont pas répondu

Les remplaçants qui ont reçu une demande sans y répondre reçoivent un **rappel automatique** à l'approche de la partie. Par exemple, si votre ligue envoie les demandes de remplacement une semaine avant les parties, vous pouvez configurer un rappel automatique deux jours avant le début de la partie. Vous n'avez plus à relancer les remplaçants manuellement.

## Suivre une recherche en cours

Depuis la partie, ouvrez le panneau **voir les remplaçants** pour consulter qui a été contacté pour chaque place à combler. C'est le premier endroit à vérifier quand vous vous demandez si la recherche fonctionne : il montre exactement quels remplaçants ont reçu une demande.

{% include image.html src="help/substitute-search-requests-sent.fr.png" caption="Le panneau Voir les remplaçants sur une place en recherche : chaque remplaçant contacté affiche le statut « Demande envoyée » avec le moment de l'envoi." %}

## Pourquoi un remplaçant précis n'a pas été contacté

Lorsqu'un remplaçant que vous attendiez n'a pas été contacté, c'est généralement pour l'une de ces raisons. Un remplaçant est ignoré, ou contacté plus tard, lorsqu'il :

* A **déjà refusé** la demande pour cette partie.
* A une **demande précédente pour la même partie restée sans réponse** : League2GO attend sa réponse avant de lui en envoyer une autre.
* Joue déjà dans une **partie qui chevauche** celle-ci.
* Serait contacté pendant la **plage ne pas déranger** de votre ligue : la demande est retenue puis envoyée à la fin de la plage, jamais annulée.
* A **désactivé ses notifications**.
* **N'a jamais complété son inscription** : un remplaçant qui n'a pas terminé son inscription ne peut pas recevoir de demandes. Consultez [ajouter des joueurs](/ajouter-des-joueurs/) pour le fonctionnement de l'inscription.
* Ne correspond pas encore à la **position ou à la plage de force** du joueur absent; il pourrait être contacté plus tard si votre ligue étend la plage progressivement.

Si un remplaçant dit n'avoir jamais reçu de demande, vérifiez d'abord le panneau voir les remplaçants, puis son statut d'inscription, puis ses [paramètres de notifications](/notifications-et-rappels/#vos-préférences-de-notification).

Des questions ? Écrivez-nous à [info@league2go.com](mailto:info@league2go.com).
