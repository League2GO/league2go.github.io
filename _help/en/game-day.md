---
title: "Game day: lineups and replacements"
lang: en
localization: game-day
category: managers
order: 60
description: "Manage game lineups and game spots, replace absent players, print the lineup, or export it to CSV."
redirect_from:
  - /improved-game-management/
  - /print-lineups/
  - /export-csv-game-lineup/
  - /team-player-substitution/
  - /manager-substitution-notification/
---

This guide covers what managers do around a single game: reviewing the lineup, managing game spots, replacing absent players, and printing or exporting the lineup. To create or cancel games, see [schedule and calendar](/schedule-and-calendar/#creating-games).

## The game lineup

Open a game to see its lineup: each team's players, their positions, and their status for that game. Regular players are presumed present unless they declare an absence (see [presence confirmation](/presence-confirmation/) for the alternative model where players confirm their presence instead).

{% include image.html src="help/game-day-lineups.en.png" caption="The game page shows both teams' lineups: every spot with its player's name, number and position, and an open spot left by a declared absence right in the lineup." %}

## Game spots

Each place in a lineup is a **game spot**. Every game spot has a menu that groups its actions:

* Replace the player
* Start an automatic substitute search
* Recall substitutes
* Change the position of the spot

{% include image.html src="help/game-day-spot-menu.en.png" caption="The spot menu gathers every action on a player's spot: search for a substitute, select another player, move them to the other team, change their position, and more." %}

Managers can also **add extra game spots** to a game. These spots can be filled automatically by substitutes, which lets incomplete teams play with a full lineup. When there is a free game spot on each team, a substitute can choose which team to join.

You can rearrange a lineup around an absence. For example, if your pitcher is absent, replace him with a fielder by changing that spot's position, then start an automatic substitute search for the now-open fielder spot.

## Replacing a player manually

To replace an absent player yourself instead of using the automatic search, open the game spot menu and choose to replace the player. In the substitution window you can pick:

* a player from the same team,
* a player from **another team** of the league (select the other team first, then the player), or
* one of your league's substitutes (see [managing substitutes](/managing-substitutes/)).

{% include image.html src="help/game-day-replace-player-dialog.en.png" caption="The replace-player window: pick the replacement from the substitute pool, or expand any other team of the league to pull a player from its roster." %}

When you substitute a player manually, you can choose to **automatically notify the player** of the change, so you do not need to contact them yourself.

For how automatic searches work, see the [substitute search overview](/substitutes-overview/) and the [search settings reference](/substitute-search-settings/).

## Simple lineup or lines

The lineup can be displayed in two modes:

* **Simple lineup**: a flat list of players and positions.
* **Lines**: players grouped into forward lines and defence pairings, with the goaltender on their own.

Open the lineup editor with **Edit Lineup** and use the **Lineup type** selector to switch between the two, so leagues that do not organize lines can keep the simple view.

{% include image.html src="help/game-day-lineup-type-toggle.en.png" caption="The Lineup type selector in the lineup editor switches the display between the simple lineup and lines." %}

## Printing the lineup

To print a game lineup, go to the game details and click the **Print Lineup** button. A print-optimized page with the game's information is generated. You can post these pages at the venue, for example to direct players to the right locker room.

{% include image.html src="help/game-day-print-menu.en.png" caption="Print Lineup lives in the game menu (the round button at the top of the game page) and opens a print-optimized lineup sheet in your browser's print dialog." %}

## Exporting the lineup to CSV

To note game statistics on paper or in a spreadsheet, open the game's page and click the **Export Alignment** button. A CSV file downloads with each player's team, jersey number, name, position, and ranking. Open it in a spreadsheet to record the game's information, then enter the results in League2GO. See [results, standings, and statistics](/results-standings-statistics/).

Questions? Contact us at [info@league2go.com](mailto:info@league2go.com).
