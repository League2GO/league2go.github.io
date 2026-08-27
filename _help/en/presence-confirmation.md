---
title: "Presence confirmation"
lang: en
localization: presence-confirmation
category: managers
order: 130
description: "Choose whether players are presumed present and declare absences, or must confirm their presence for each game."
---

League2GO offers two models for knowing who will be at a game.

## Default: players declare absences

By default, regular players are **presumed present** for their games. A player who cannot make a game declares an absence with the green/red button on the game, and a declared absence is what can trigger a [substitute search](/substitutes-overview/).

This model suits most leagues: attendance is the norm, and only exceptions need action from players.

{% include image.html src="help/presence-confirmation-default.en.png" caption="By default a rostered player is presumed present: the game page only offers the red Declare absence action for when they can't make it." %}

## Opt-in: players confirm their presence

Some leagues prefer the opposite: no player is counted on until they have **confirmed** they will be there. In presence-confirmation mode, players are asked to confirm their presence for each game instead of only declaring absences.

Choose this model if your attendance is unpredictable — for example when silence from a player more often means "not coming" than "coming" — and you would rather chase confirmations than discover no-shows at game time.

{% include image.html src="help/presence-confirmation-request.en.png" caption="With presence confirmation enabled, the game page asks the player to confirm as game time approaches: green "I will play" or red "I can't play"." %}

## Enabling confirmation mode

Presence confirmation is **opt-in**. A league administrator enables it with a toggle in the league settings. <!-- TODO: verify exact setting name and location -->

## What players see

* **Default mode**: the player sees the game with the green/red button and only acts to declare (or cancel) an absence.
* **Confirmation mode**: the player is asked to confirm their presence for each game; managers can see who has confirmed and who has not answered yet. <!-- TODO: verify how unanswered confirmations are displayed to managers -->

For the player-side view of absences and games, see the [player guide](/player-guide/).

Questions? Contact us at [info@league2go.com](mailto:info@league2go.com).
