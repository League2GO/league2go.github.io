---
title: "Nouvelle fonctionnalité - Paiement en ligne pour les joueurs"
lang: fr
localization: player-payments
---
Dès maintenant, les joueurs réguliers peuvent payer leur frais de saison en ligne sur League2GO. Plus besoin de collecter l’argent comptant! L’argent est transférée directement dans votre compte et vous pouvez faire le suivi des paiements de chaque joueur directement par l'interface de gestion de votre ligue. Nous utilisons la technologie de paiement Stripe pour vous assurer une sécurité et une simplicité hors pair.

Pour que le paiement fonctionne, vous devez tout d’abord configurer votre ligue sur le site web. Ensuite, vous pourrez générer des frais de saisons à payer en ligne et les joueurs auront l’option de payer par le site web ou par l’application mobile de League2GO. Dans cet article, nous vous présentons tout d’abord la simplicité du paiement pour ensuite vous montrer comment configurer votre ligue.

### Générer un frais de saison (Gestionnaire de ligue)

Une fois votre ligue configurée pour accepter les paiements en ligne, pour générer un frais de saison, il suffit d’aller dans l’onglet “Facturation” de l’interface de gestion de la ligue, puis de cliquer sur “Enregistrer un frais de saison”

{% include image.html src="2020-08-03-enregistrer-frais-de-saison.png" caption="Enregistrer un frais de saison." %}

Par la suite, il faut entrer le revenu désiré pour la ligue. Le montant chargé à chaque joueur, incluant le 0.30$ + 2.9% collecté par Stripe, sera automatiquement affiché à droite. Au besoin, une date d’échéance et une note peuvent être ajoutées au paiement. Lorsque le tout est configuré, pesez sur “Ajouter”.

{% include image.html src="2020-08-03-enregistrer-frais-de-saison-popup.png" caption="Configurer le frais de saison" %}

C’est tout! Vous pourrez ensuite faire le suivi du paiement de chaque joueur à l’aide de l’onglet “Facturation”. Lorsqu’un joueur effectuera son paiement en ligne, vous le verrez automatiquement comme payé dans cet interface.

<p>{% include image.html src="2020-08-03-frais-de-saison-tracking.png" caption="Suivi des frais de saisons" %}</p>

### Payer en ligne (Joueur)

Les joueurs peuvent payer leur frais de saison directement à partir de leur horaire soit par l’application mobile ou par le site web League2GO. Tout d’abord, le joueur doit cliquer sur le frais en question en haut de l’horaire.

{% include image.html src="2020-08-03-horaire-paiement.png" caption="Horaire" %}

Les détails des frais de la ligue sont ensuite affichés. Il suffit au joueur de peser sur “Payer maintenant”.

{% include image.html src="2020-08-03-effectuer-paiement-détail.png" caption="Détail de paiement" %}

Finalement, le joueur n’a qu’à entrer ses informations de paiement, puis peser sur “Payer”.

{% include image.html src="2020-08-03-paiement.png" caption="Payer en ligne" %}

### Configuration de la ligue

Pour activer le paiement, allez dans les paramètres de votre ligue et cliquez sur l'onglet Paiement. Cliquez ensuite sur Connecter un compte Stripe. Vous devez être sur le site web et non sur l'app mobile.

{% include image.html src="2020-08-03-parametres.png" caption="Configurer le paiement." %}

Sélectionnez «Canada», puis pour «Your website», activez le site web de ligue sur League2GO et copiez-y l’URL. Ensuite, sélectionnez «Other entertainment and recreation» et dans la zone de texte «Business description», vous devez expliquer que vous êtes une ligue sportive qui vend une saison ou des parties de sport. Voici un exemple de message: «I own a sport league that sells hockey games to players and substitutes. I charge customers before the start of the game.».

{% include image.html src="2020-08-03-stripe-signup.png" caption="Entrez la description de votre ligue." %}

Pour «Type of business», choisissez «Individual or sole proprietorship» et entrez votre «Business number (Tax ID)» si vous en avez un. Entrez ensuite votre adresse personnelle dans «Business address». 

Entrez ensuite votre nom et votre date de naissance dans les champs «Legal name» et «Date of birth», puis votre adresse personnelle à nouveau. Pour SIN (Tax ID), vous devez entrer votre numéro d’assurance sociale pour confirmer votre identité.

Saisissez le nom de votre ligue dans le champ «Statement descriptor» et votre numéro de téléphone dans «Phone». Cette information sera affichée sur les relevés de carte de crédit des joueurs.

Sélectionnez «CAD» comme Bank account currency et ensuite saisissez les informations de votre compte de banque. Vous pouvez trouver ces informations sur votre spécimen chèque.

Finalement, entrez votre adresse courriel et votre mot de passe pour créer votre compte Stripe. Vous pourrez utiliser ces données pour vous authentifier sur Stripe et consulter l’information de vos paiements.

Vous pouvez maintenant utiliser gérer les paiements de vos joueurs en ligne par la plateforme League2GO!

{% include image.html src="2020-08-03-parametres-paiement-actif.png" caption="Activer le paiement en ligne." %}

Pour en savoir plus sur le paiement en ligne pour les remplaçants, visitez [cet article!](https://blog.league2go.com/paiements-remplacant/)

Nous attendons vos commentaires au [info@league2go.com](mailto:info@league2go.com).

Par Carl de League2GO.
