---
title: "Confirmation de présence"
lang: fr
localization: presence-confirmation
category: managers
order: 130
description: "Choisissez si les joueurs sont présumés présents et déclarent leurs absences, ou s'ils doivent confirmer leur présence à chaque partie."
---

League2GO offre deux modèles pour savoir qui sera présent à une partie.

## Par défaut : les joueurs déclarent leurs absences

Par défaut, les joueurs réguliers sont **présumés présents** à leurs parties. Un joueur qui ne peut pas se présenter déclare une absence avec le bouton vert/rouge de la partie, et c'est une absence déclarée qui peut déclencher une [recherche de remplaçants](/recherche-de-remplacants/).

Ce modèle convient à la plupart des ligues : la présence est la norme, et seules les exceptions demandent une action des joueurs.

{% include screenshot.html description="Vue joueur d'une partie à venir montrant le bouton de présence vert/rouge, le joueur étant présumé présent par défaut" %}

## En option : les joueurs confirment leur présence

Certaines ligues préfèrent l'inverse : ne compter sur aucun joueur tant qu'il n'a pas **confirmé** sa présence. En mode confirmation de présence, les joueurs sont invités à confirmer leur présence à chaque partie au lieu de seulement déclarer leurs absences.

Choisissez ce modèle si vos présences sont imprévisibles — par exemple lorsque le silence d'un joueur signifie plus souvent « je ne viens pas » que « je viens » — et que vous préférez relancer des confirmations plutôt que de découvrir des absences au moment de la partie.

{% include screenshot.html description="Vue joueur d'une partie à venir en mode confirmation de présence, montrant la demande de confirmer sa présence pour la partie" %}

## Activer le mode confirmation

La confirmation de présence est **optionnelle**. Un administrateur de la ligue l'active avec une option dans les paramètres de la ligue. <!-- TODO: vérifier le nom exact et l'emplacement du paramètre -->

## Ce que les joueurs voient

* **Mode par défaut** : le joueur voit la partie avec le bouton vert/rouge et n'agit que pour déclarer (ou annuler) une absence.
* **Mode confirmation** : le joueur est invité à confirmer sa présence à chaque partie ; les gestionnaires peuvent voir qui a confirmé et qui n'a pas encore répondu. <!-- TODO: vérifier comment les confirmations sans réponse sont affichées aux gestionnaires -->

Pour le côté joueur des absences et des parties, consultez le [guide du joueur](/guide-du-joueur/).

Des questions ? Écrivez-nous à [info@league2go.com](mailto:info@league2go.com).
