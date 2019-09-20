---
title: "Nouvelle fonctionnalité! - Forces de joueur pour le remplacement automatique"
lang: fr
localization: player-ranking
---
Configurez les forces que vous pourrez assigner à vos joueurs ou vos remplaçants en choisissant des lettres ou des nombres à partir de l’onglet Général des paramètres de votre ligue. Les lettres, plus simples, sont «AAA», «AA», «BB», «CC», «A», «B», «C» et «D». Les nombres sont entre 1 et 1000 et vous permettent plus de flexibilité. Vous pouvez aussi utiliser de 1 à 100 si c’est votre besoin. Les forces désignées sont seulement visibles par les capitaines des équipes et les gestionnaires des ligues.

Configurez ensuite les plages de force pour vos remplacements automatiques. 

Si vous voulez spécifier les forces de vos joueurs, mais ne pas les prendre en compte pour le remplacement, étendez au maximum la plage de force (-1000 à 1000). Assurez-vous que l’option «Étendre 
les forces progressivement» est désactivée.

{% include image.html src="2016-11-14-aucun-critere-force.png" caption="Aucun critère" %}

Si vos règles de remplacement sont strictes, configurez la plage de force selon vos besoins et n’activez pas l’option «Étendre les forces progressivement». Les remplaçants devront obligatoirement 
respecter les forces configurées pour jouer.

{% include image.html src="2016-11-14-criteres-forces-stricts.png" caption="Critères stricts" %}

Si vos règles de remplacement sont flexibles, configurez la plage de force initiale puis cochez l’option «Étendre les forces progressivement». Entrez maintenant le nombre d’heures pour atteindre 
progressivement les limites de la deuxième plage de force. Lorsqu’une absence est déclarée, seulement les joueurs qui respectent la plage initiale seront contactés puis celle-ci augmentera selon la durée configurée pour atteindre la plage finale. Cette option vous permet d’augmenter vos possibilités de remplacement si vous favorisez des parties avec un alignement complet.

Par exemple, si un joueur «A» déclare son absence et que la ligue est configurée comme l’image ci-dessous, le remplacement automatique contactera initialement les remplaçants de la ligue avec une force entre «C» et «BB». Après 4 heures, les remplaçants qui ont une force entre «D» et «AA» seront contactés puis, après 8 heures, ceux avec une force en «D» et «AAA». La limite minimale reste «D» car c’est la position la plus faible.

{% include image.html src="2016-11-14-criteres-flexibles-forces.png" caption="Critères flexibles" %}

Dans l’onglet Équipes et Remplaçants de votre ligue, assignez des forces à vos joueurs. Vous devez entrer une force pour chaque position du joueur. La force est affichée en dessous du nom du joueur dans les tableaux d’équipes et remplaçants. Si un joueur n’a pas de force configurée, un point d’exclamation s’affichera dans le tableau à côté du joueur pour vous informer du problème.

Les forces sont maintenant affichées dans les parties vous permettant de sélectionner manuellement des remplaçants avec une force similaire aux joueurs absents. De plus, quand vous ajoutez un emplacement à une partie, spécifier la force le combler automatiquement avec un joueur de la bonne force.

Nous attendons vos commentaires au [info@league2go.com](mailto:info@league2go.com).

Par Simon.