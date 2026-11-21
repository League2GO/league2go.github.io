---
title: "Substitute search settings"
lang: en
localization: substitute-search-settings
category: substitutes
order: 20
description: "Reference for every option in league settings > Substitutes: search timing, targets, rating ranges, favorites, blackout and prices."
redirect_from:
  - /less-known-features-part2/
---

This is the reference for every option that controls the [automatic substitute search](/substitutes-overview/). Unless noted otherwise, all options live in your **league settings, Substitutes tab**. Your substitute lists themselves are managed elsewhere. See [managing substitutes](/managing-substitutes/).

{% include image.html src="help/substitute-settings-options.en.png" caption="League settings > Substitutes: an Automatic or Manual search, the absence cutoff, when the search starts (days before the game) and the step-by-step search sequence with its wait times." %}

## When the search starts

**What it does:** sets how many days before a game substitution requests start going out. An absence declared earlier waits until this window opens; an absence declared later triggers the search immediately.

**When to change it:** shorten it if substitutes accept then forget about far-away games; lengthen it if your games are hard to fill.

**Choose Manual at the top of the tab to turn off the automatic search.** No requests are sent automatically and you [pick substitutes manually](/managing-substitutes/#picking-a-substitute-manually) for each game. A request you send by hand then stays open until the game.

**Example:** with the search set to start 7 days before games, an absence declared 3 weeks ahead sits quietly until 7 days before the game, then requests go out.

## Automatic reminder for substitutes

**What it does:** if no one has accepted once every step of the search is done, sends one reminder, a set number of hours before the game, to the substitutes who received a request but have not answered.

**When to change it:** place it close enough to the game to create urgency, but leave the search time to reach other substitutes first.

**Example:** requests go out 7 days before the game; the reminder is set to 48 hours before. If the spot is still open by then, a substitute who ignored the first message gets one nudge 2 days out.

## Target players per team

**What it does:** sets how many players you want in each team's lineup, per position. A search only starts when an absence drops the lineup **below** the target; if you carry more regulars than the target, the first absences trigger nothing.

**When to change it:** match it to how many players actually take the field (or ice, or court) for your league.

**Example:** target of 10 players, team roster of 11 regulars. The first declared absence leaves 10 available: no search. The second absence drops the lineup to 9 and starts a search for one substitute.

**Pick-up leagues:** the target is still per team. A pick-up game holds both teams, so the search starts when the game falls below twice the target: with a target of 10, a search starts when fewer than 20 players remain. See [target number of players per position](/teams-and-team-settings/#target-number-of-players-per-position).

## Skill ratings and rating ranges

Ratings let the search propose substitutes of comparable caliber to the absent player.

**Choosing the scale:** in the **General tab** of your league settings, choose letters ("AAA", "AA", "BB", "CC", "A", "B", "C", "D") or numbers (1 to 1000; use 1 to 100 if that suits your needs) as your rating scale. Ratings are visible only to team captains and league managers. You then assign a rating to each player and substitute, per position. See [managing substitutes](/managing-substitutes/).

**The range is always relative to the absent player.** When a player is absent, only substitutes whose rating falls within the configured range around that player's rating are contacted. The **Substitute ranking** section shows the range as a cone: the starting range on the left, the final range on the right, and the minutes it takes to widen under it. Above the cone, the rankings it reaches are shown for an example absent player. Three ways to configure it:

* **No rating criteria:** you want ratings for your own reference, but any substitute may replace anyone. Set the starting range to its maximum (1000 points below and above) and click **Don't widen**.
* **Strict:** set the starting range you require and click **Don't widen**. Substitutes outside the range are never contacted for that absence.
* **Flexible:** set the **starting range**, click **Widen over time**, set the **final range** at the right end of the cone, and enter the number of minutes over which the range widens. The minutes count from the start of the search, excluding the do-not-disturb hours. The search starts with close matches and gradually accepts substitutes further from the absent player's rating, useful when a full lineup matters more than a perfect match. The final range cannot be narrower than the starting range.

{% include image.html src="help/substitute-settings-rating-range.en.png" caption="The Substitute ranking section: the starting range on the left of the cone, the final range on the right, the minutes to widen under it, and the rankings it reaches for an example absent player." %}

**Example (flexible):** a player rated "A" declares an absence. The initial range contacts substitutes rated "BB" to "C". After 4 hours the range widens to "AA" through "D", and after 8 hours to "AAA" through "D". The lower bound stops at "D" because it is the lowest rating on the scale.

**More players absent than spots to fill:** on a number scale, in leagues that set a [target number of players per position](/teams-and-team-settings/#target-number-of-players-per-position), the sentence "When more players at one position are absent than spots to fill, replace first the one whose ranking is" decides which absent player gets replaced: "the highest number" or "the lowest number". It only matters when more players are absent than there are spots to fill. The search then fills only the chosen player's spot, looking for substitutes around that player's rating; the other absent players' spots stay open. For example, two defensemen rated 600 and 400 are absent and only one spot needs filling: with "the highest number", the search contacts substitutes around 600, and the spot of the player rated 400 stays open. On a letter scale the setting does not appear: the search always replaces the highest-rated absent player.

{% include image.html src="help/substitute-settings-replace-first.en.png" caption="On a number scale, under the cone: which absent player to replace first, here the one with the highest number." %}

## Favorites and contact order

**What it does:** the search contacts substitutes in tiers, favorites first: **team favorites, then team substitutes, then league favorites, then league substitutes**. You configure the delay between each level; the next tier is only contacted after that delay if the spot is still open. Favorites are marked with the star beside each substitute. See [managing substitutes](/managing-substitutes/).

**When to change it:** use short delays if filling the spot fast matters more than who fills it; use longer delays to give your most reliable substitutes a real head start.

**Example:** with a 4-hour delay between levels, team favorites get the request first; 4 hours later the other team substitutes are added, then league favorites, then the rest of the league list.

## Absence blackout period

**What it does:** sets a number of hours before the game during which players can no longer declare their own absence. This prevents last-minute declarations the search has no time to fill; the player has to contact you instead, and you decide how to handle it.

**When to change it:** set it to roughly the minimum notice your substitutes need to actually show up.

**Example:** with a 6-hour blackout, a player cannot declare an absence at 5 pm for an 8 pm game.

## Do-not-disturb hours

**What it does:** defines a period during which no automated messages are sent to your players. Requests that would fall in the period are held and sent when it ends, never skipped. The configured delays between favorite and regular substitutes are still respected.

**When to change it:** turn it on so an absence declared at midnight does not wake up your substitute list.

**Example:** do-not-disturb from 10 pm to 8 am. An absence declared at 11 pm sends its first requests at 8 am the next morning.

## Prices in substitution requests

**What it does:** when you turn on **Include the price in substitution requests**, the amount a substitute pays to play is included in every request, and in the message sent to a substitute you assign manually. You enter an amount per position, and positions can differ: for example $20 for a defender or a forward, but free for a goalkeeper. Leave a position blank if it has no price.

**When to change it:** turn it on so substitutes show up knowing what they owe. To collect the amount online rather than in cash, see [online payments](/online-payments-setup/#charging-substitutes-per-game).

{% include image.html src="help/substitute-settings-prices.en.png" caption="Include the price in substitution requests: when it is on, each position gets its own price field." %}

## Position matching

Position matching is always on: a substitute is only contacted to replace a player whose position they play. The positions themselves come from your league configuration, and you check the positions each substitute can play in their profile; check every position they can cover so they are contacted as often as possible. See [managing substitutes](/managing-substitutes/).

Questions? Contact us at [info@league2go.com](mailto:info@league2go.com).
