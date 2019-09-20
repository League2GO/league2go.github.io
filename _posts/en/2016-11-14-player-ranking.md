---
title: "New feature! - Player skills for automatic substitution"
lang: en
localization: player-ranking
---
Configure the skills that you can assign to your players or substitutes by choosing letters or numbers from the General tab of the settings in your league. The letters are "AAA", "AA", "BB", "CC", "A", "B", "C" and "D". The numbers are between 1 and 1000 and allow you more flexibility. You can also use numbers from 1 to 100 if that suites your needs. Designated skills are only visible to team captains and league managers.

Next you can configure your skill ranges for automatic substitutions.

If you want to specify the skill of your players, but do not want to consider them for substitutions, expand the skill range to its maximum (-1000 to 1000). Make sure the option "Extend skill range gradually" is off.

{% include image.html src="2016-11-14-no-skill-criteria.png" caption="No criteria" %}

If your substitution rules are strict, set the skill range according to your needs and do not enable the option "Extend skill range gradually". Substitutes will have to comply with the required skills.

{% include image.html src="2016-11-14-strict-skill-criteria.png" caption="Strict criteria" %}

If your substitution rules are flexible, configure the initial skill range and check the "Extend skill range gradually" option. Now enter the number of hours to gradually reach the limits of the second skill range. When an absence is declared, only the players who respect the initial range will be contacted then it will increase according to the configured time to reach the final range. This option allows you to increase your substitution options if you favor games with a full alignment.

For example, if a player "A" declares their absence and the league is configured as the image below, the automatic substitution will initially contact the league substitutes with a skill between "BB" and "C". After 4 hours, substitutes that have a skill between "AA" and "D" will be contacted and then, after 8 hours, those with a "AAA" and "D" skill. The minimum skill remains "D" because it is the lowest position.

{% include image.html src="2016-11-14-flexible-skill-criteria.png" caption="Flexible criteria" %}

In the Teams and Substitutes tab of your league, assign skills to your players. You must enter a skill for each player position. The skill is displayed below the player's name in the team and substitute tables. If a player does not have a configured skill, an exclamation point will appear in the table next to the player to inform you of the problem.

The skills are now displayed in the game details allowing you to manually select substitutes with a similar skill to replace the absent players. Also, when you add a spot to a game, specify the skill to automatically find a player that matches your skill requirements.

If you have any questions or comments please contact us at [info@league2go.com](mailto:info@league2go.com).

By Simon.
