---
title: "How the automatic substitute search works"
lang: en
localization: substitutes-overview
category: substitutes
order: 10
description: "What triggers a substitute search, who gets contacted in what order, and how to follow its progress."
redirect_from:
  - /automatic-substitute-reminder/
---

When a player cannot make a game, League2GO can find a replacement for you. Eligible substitutes are contacted automatically, in waves, and the first one to accept gets the spot. This article explains the sequence so you can trust it, and diagnose it when a game stays short-handed.

To configure the behavior described here, see [substitute search settings](/substitute-search-settings/). To build and maintain your substitute lists, see [managing substitutes](/managing-substitutes/).

## What starts a search

A search starts when **a player declares their own absence** for a game. If your league sets a [target number of players per team](/teams-and-team-settings/), the search only starts when the absence puts the lineup below that target: a team still at or above it needs no replacement, so no one is contacted. If your league's automatic search is **disabled** (search start set to 0 days before games), nothing starts on its own and you [pick substitutes manually](/managing-substitutes/).

A manager can start a search too. When you declare an absence on a player's behalf, the absence alone does **not** trigger anything, so you can record it without sending requests, for example when you already have a replacement lined up. Request the search explicitly when you want League2GO to find someone.

The search does not necessarily begin the moment the absence is declared. Requests start going out a set time before the game, the number of days you choose in your league settings. An absence declared earlier than that simply waits, and the search begins once the game is that many days away.

## Who is contacted, and in what order

League2GO does not blast every substitute at once. Candidates are contacted in successive waves:

1. **Favorites first**, then progressively wider circles of substitutes, with a configurable delay between each level.
2. Within each wave, a substitute is only contacted if they **play the absent player's position**.
3. A substitute's **skill rating must fall within the configured range relative to the absent player's rating**. If your league widens the range gradually, substitutes further from the absent player's rating are contacted later, as the range expands.

The exact tiers, delays and rating ranges are all yours to configure. See [substitute search settings](/substitute-search-settings/) for each option.

The **first substitute to accept gets the spot**: the lineup is updated and everyone involved is notified. Substitutes who accept too late are informed that the spot is already filled.

## Reminders to substitutes who have not answered

Substitutes who received a request but have not responded get an **automatic reminder** closer to the game. For example, if your league sends substitution requests a week before games, you can configure an automatic reminder two days before the start of the game. You never have to chase substitutes manually.

## Following a search in progress

From the game, open the **view substitutes** panel to see who was contacted for each open spot. This is the first place to look when you wonder whether the search is working: it shows exactly which substitutes received a request.

{% include image.html src="help/substitute-search-requests-sent.en.png" caption="The View substitutes panel on a searching spot: every contacted substitute shows a 'Request sent' status with when the request went out." %}

## Why a specific substitute was not contacted

When a substitute you expected to hear from was not contacted, it is usually for one of these reasons. A substitute is skipped, or contacted later, when they:

* **Already declined** the request for this game.
* Have an **unanswered previous request for the same game**: League2GO waits for their answer before sending another.
* Are already playing in an **overlapping game**.
* Would be contacted during your league's **do-not-disturb hours**: the request is held and sent when the period ends, not skipped.
* Have **notifications disabled**.
* **Never completed their registration**: a substitute who has not finished signing up cannot receive requests. See [adding players](/adding-players/) for how registration works.
* Do not yet match the **position or skill-rating range** for the absent player; they may still be contacted later if your league widens the range gradually.

If a substitute says they never got a request, check the view substitutes panel first, then their registration status, then their [notification settings](/notifications/).

Questions? Contact us at [info@league2go.com](mailto:info@league2go.com).
