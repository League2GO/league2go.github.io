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

Lorsqu'un joueur ne peut pas se présenter à une partie, League2GO peut trouver un remplaçant pour vous. Les remplaçants admissibles sont contactés automatiquement, par vagues, et le premier qui accepte obtient la place. Cet article explique le déroulement pour que vous puissiez vous y fier — et diagnostiquer la situation quand une partie reste incomplète.

Pour configurer le comportement décrit ici, consultez les [options de la recherche de remplaçants](/options-de-recherche-de-remplacants/). Pour bâtir et entretenir vos listes de remplaçants, consultez [gérer les remplaçants](/gerer-les-remplacants/).

## Ce qui déclenche une recherche

Une recherche démarre lorsque :

* **Un joueur déclare lui-même son absence** pour une partie (depuis l'application ou le site web).
* **Un gestionnaire déclare une absence au nom d'un joueur et demande explicitement une recherche.** Une absence déclarée par un gestionnaire ne déclenche **pas** de recherche à elle seule — vous pouvez ainsi noter une absence sans envoyer de demandes, par exemple quand vous avez déjà un remplaçant en tête.

Une recherche ne démarre **pas** lorsque :

* L'alignement de l'équipe est encore au **nombre de joueurs cible** configuré pour votre ligue, ou au-dessus — aucun remplacement n'est nécessaire, donc personne n'est contacté.
* La recherche automatique de votre ligue est **désactivée** (début de la recherche réglé à 0 jour avant les parties). Dans ce cas, vous [choisissez les remplaçants manuellement](/gerer-les-remplacants/).

Les demandes sont envoyées à l'intérieur de la fenêtre configurée dans les paramètres de votre ligue (un nombre de jours avant la partie). Si une absence est déclarée plus tôt, la recherche attend l'ouverture de cette fenêtre.

## Qui est contacté, et dans quel ordre

League2GO ne contacte pas tous vos remplaçants d'un coup. Les candidats sont contactés par vagues successives :

1. **Les favoris d'abord**, puis des cercles de remplaçants de plus en plus larges, avec un délai configurable entre chaque niveau.
2. Dans chaque vague, un remplaçant n'est contacté que s'il **joue la position du joueur absent**.
3. La **force du remplaçant doit se situer dans la plage configurée par rapport à la force du joueur absent**. Si votre ligue étend la plage progressivement, les remplaçants plus éloignés de la force du joueur absent sont contactés plus tard, à mesure que la plage s'élargit.

Les niveaux, les délais et les plages de force sont tous configurables — consultez les [options de la recherche de remplaçants](/options-de-recherche-de-remplacants/) pour chaque option.

Le **premier remplaçant qui accepte obtient la place** : l'alignement est mis à jour et toutes les personnes concernées sont avisées. Un remplaçant qui accepte trop tard est informé que la place est déjà comblée.

## Rappels aux remplaçants qui n'ont pas répondu

Les remplaçants qui ont reçu une demande sans y répondre reçoivent un **rappel automatique** à l'approche de la partie. Par exemple, si votre ligue envoie les demandes de remplacement une semaine avant les parties, vous pouvez configurer un rappel automatique deux jours avant le début de la partie. Vous n'avez plus à relancer les remplaçants manuellement.

## Suivre une recherche en cours

Depuis la partie, ouvrez le panneau **voir les remplaçants** pour consulter qui a été contacté pour chaque place à combler. C'est le premier endroit à vérifier quand vous vous demandez si la recherche fonctionne : il montre exactement quels remplaçants ont reçu une demande.

{% include screenshot.html description="Page de détails d'une partie avec le panneau voir les remplaçants ouvert, montrant la liste des remplaçants contactés pour une place à combler, avec le statut contacté mis en évidence" %}

## Pourquoi un remplaçant précis n'a pas été contacté

Presque toutes les situations « la recherche ne fonctionne pas » se résument à l'un de ces cas. Un remplaçant est ignoré, ou contacté plus tard, lorsqu'il :

* A **déjà refusé** la demande pour cette partie.
* A une **demande précédente restée sans réponse** — League2GO attend sa réponse avant de lui en envoyer une autre.
* Joue déjà dans une **partie qui chevauche** celle-ci.
* Serait contacté pendant la **plage ne pas déranger** de votre ligue — la demande est retenue puis envoyée à la fin de la plage, jamais annulée.
* A **désactivé ses notifications**.
* **N'a jamais complété son inscription** — un remplaçant qui n'a pas terminé son inscription ne peut pas recevoir de demandes. Consultez [ajouter des joueurs](/ajouter-des-joueurs/) pour le fonctionnement de l'inscription.
* Ne correspond pas encore à la **position ou à la plage de force** du joueur absent — il pourrait être contacté plus tard si votre ligue étend la plage progressivement.

Si un remplaçant affirme n'avoir jamais reçu de demande, vérifiez d'abord le panneau voir les remplaçants, puis son statut d'inscription, puis ses [paramètres de notifications](/notifications-et-rappels/).

Des questions ? Écrivez-nous à [info@league2go.com](mailto:info@league2go.com).
