---
title: "Nouvelle fonctionnalité - Paiement en ligne pour les remplaçants"
lang: fr
localization: substitute-payments
---
Désormais, les remplaçants peuvent payer directement sur la plateforme League2GO, afin de simplifier encore plus la gestion de votre ligue sportive. L'argent est directement transférée dans votre compte. Il n'est plus nécessaire de collecter l'argent, de faire le suivi des paiements, ni de rendre la monnaie aux remplaçants. Utilisez dès maintenant le paiement intégré en suivant ces instructions. Nous utilisons la technologie de paiement Stripe pour vous assurer une sécurité et une simplicité hors pair.

Pour que le paiement fonctionne, vous devez tout d’abord configurer votre ligue sur le site web. Ensuite, vos remplaçants auront l’option de payer par le site web our l'application mobile. Dans cet article, nous vous présentons tout d’abord la simplicité du paiement pour ensuite vous montrer comment configurer votre ligue.

### Paiement par un remplaçant

Il est toujours aussi facile d’accepter un remplacement avec le paiement en ligne. Une fois que le joueur accepte de remplacer, une fenêtre lui demande de confirmer le paiement. La première fois, le joueur doit entrer son information de carte de crédit, mais ce ne sera pas nécessaire pour les prochaines fois.

{% include image.html src="2017-09-10-join-game-fr.png" caption="Accepter un remplacement." %}

{% include image.html src="2017-09-10-credit-card-fr.png" caption="Entrer une carte de crédit." %}

{% include image.html src="2017-09-10-existing-credit-card-fr.png" caption="Payer avec une carte de crédit existante." %}

Si le joueur décide de payer plus tard, il peut réafficher le formulaire de paiement à partir de la page de la partie ou vous payer à la partie.

{% include image.html src="2017-09-10-pay-fr.png" caption="Payer pour jouer." %}

Vous pouvez voir l’argent que vous devez collecter dans la page de la partie.

{% include image.html src="2017-09-10-amount-due-fr.png" caption="Montant impayé." %}

{% include image.html src="2017-09-10-amount-paid-fr.png" caption="Montant payé." %}

### Configuration de la ligue

Pour activer le paiement, allez dans les paramètres de votre ligue et cliquez sur l'onglet Paiement. Cliquez ensuite sur Connecter un compte Stripe. Vous devez être sur le site web et non sur l'app mobile.

{% include image.html src="2017-09-10-configure-payment-fr.png" caption="Configurer le paiement." %}

Sélectionnez Canada et dans la zone de texte «Tell us about your business», vous devez expliquer que vous êtes une ligue sportive qui vend une saison ou des parties de sport. Voici un exemple de message: «I own a sport league that sells hockey games to substitutes. I charge customers before the start of the game.». Ne cochez pas la case à cocher suivante.

{% include image.html src="2017-09-10-configure-payment-product-fr.png" caption="Entrez la description de votre ligue." %}

Pour «Your business type», choisissez «Individual/Sole proprietorship» et entrez votre «Business number (TAX ID)» si vous en avez un. Entrez ensuite votre adresse personnelle dans «Business address». Pour «Your website», activez le site web de ligue sur League2GO et copiez-y l’URL.

Entrez ensuite votre nom et votre date de naissance dans les champs «Legal name» et «Date of birth». Pour SIN (Tax ID), vous devez entrer votre numéro d’assurance social pour confirmer votre identifiée.

Saisissez le nom de votre ligue dans le champ «Business Name» et votre numéro de téléphone dans «Phone». Cette information sera affichée sur les relevés de carte de crédit des joueurs.

Sélectionnez «CAD» comme Bank account currency et ensuite saisissez les informations de votre compte de banque. Vous pouvez trouver ces informations sur votre spécimen chèque.

Finalement, entrez votre adresse courriel et votre mot de passe pour créer votre compte Stripe. Vous pourrez utiliser ces données pour vous authentifier sur Stripe et consulter l’information de vos paiements.

Ensuite configurez le prix pour les remplaçants. League2GO collecte 1.00$ par transaction et Stripe collecte 0.30$ + 2.9%.

{% include image.html src="2018-03-02-configure-price-fr.png" caption="Configurer le prix pour les remplaçants." %}

Nous attendons vos commentaires au [info@league2go.com](mailto:info@league2go.com).

Par Simon.
