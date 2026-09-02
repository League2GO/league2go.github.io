---
title: "Configurer les paiements en ligne"
lang: fr
localization: online-payments-setup
category: payments
order: 10
description: "Connectez le compte Stripe de votre ligue pour collecter les frais de saison et les paiements de remplaçants par carte de crédit."
redirect_from:
  - /paiements-remplacant/
  - /suivi-paiments-remplacants/
  - /paiements-joueur/
---

League2GO permet à vos joueurs et à vos remplaçants de payer par carte de crédit : plus besoin de collecter l'argent comptant, de rendre la monnaie ni de courir après les paiements. Les paiements sont traités par **Stripe** et déposés **directement dans le compte Stripe de votre ligue**.

Trois choses à comprendre avant de commencer :

* **L'argent est le vôtre, pas celui de League2GO.** Les paiements passent par le compte Stripe de votre ligue : League2GO ne détient jamais l'argent.
* **Les remboursements sont émis par vous**, à partir de votre tableau de bord Stripe. Le soutien League2GO ne peut pas rembourser un joueur, puisque League2GO n'a jamais l'argent.
* **Stripe vous enverra des courriels au sujet de votre compte** (vérification d'identité ou d'entreprise). Ces courriels peuvent tomber dans les indésirables, et les ignorer entraîne la suspension de vos versements. Voir la section sur les courriels de conformité Stripe plus bas.

## Connecter votre compte Stripe

Pour activer les paiements, allez dans les paramètres de votre ligue et ouvrez l'onglet **Paiement**, puis cliquez sur **Connecter un compte Stripe**. Vous devez le faire sur le site web, et non sur l'application mobile.

{% include image.html src="help/payment-settings-connect-stripe.fr.png" caption="Paramètres de la ligue > Paiement avant la connexion à Stripe : le bouton Connecter un compte Stripe démarre la configuration du compte." %}

Stripe vous demande ensuite de créer un compte et de vérifier votre identité. La plupart des ligues récréatives ne sont pas des entreprises incorporées, et c'est tout à fait correct. Voici comment répondre aux questions courantes :

* **Type of business** : choisissez **Individual or sole proprietorship**, à moins que votre ligue soit incorporée. Entrez votre numéro d'entreprise (Tax ID) si vous en avez un, et votre adresse personnelle comme adresse d'entreprise.
* **Business name / statement descriptor** : entrez le **nom de votre ligue**. C'est ce qui apparaîtra sur les relevés de carte de crédit de vos joueurs, alors choisissez un nom reconnaissable.
* **Business website** : activez votre [site web de ligue](/site-web-de-ligue/) gratuit sur League2GO et copiez-y son URL.
* **Business description** : expliquez que vous gérez une ligue sportive qui vend des parties ou des saisons. Par exemple : « I own a sports league that sells hockey games to players and substitutes. I charge customers before the start of the game. »
* **Identité** : entrez votre nom légal, votre date de naissance et votre numéro d'assurance sociale; Stripe l'exige pour confirmer votre identité.
* **Compte bancaire** : sélectionnez votre devise et saisissez les informations de votre compte de banque (vous les trouverez sur un spécimen de chèque). C'est là que Stripe dépose vos versements.

Finalement, entrez une adresse courriel et un mot de passe pour votre compte Stripe. Utilisez-les en tout temps sur stripe.com pour consulter vos paiements, vos versements et émettre des remboursements.

{% include image.html src="help/payment-settings-active.fr.png" caption="L'onglet Paiement une fois le compte Stripe connecté : paiements des joueurs et des remplaçants activés, avec le lien vers le tableau de bord Stripe." %}

## Les frais

Pour chaque montant que vous facturez, vous entrez le **revenu désiré pour la ligue**, et les frais de traitement sont ajoutés par-dessus au paiement du joueur : la ligue reçoit le montant complet que vous avez entré.

* **Frais Stripe** : 2,9 % + 0,30 $ par transaction (sur chaque paiement).
* **Frais League2GO** : 1,00 $ par paiement de **remplaçant**. Les paiements des joueurs réguliers (frais de saison) n'ont **aucuns frais League2GO**.

Vous n'avez pas à faire ce calcul : le tableau des prix affiche le montant exact facturé au joueur à côté de chaque prix que vous entrez, et les frais courants sont détaillés juste en dessous.

## Facturer les remplaçants par partie

Dans les paramètres de paiement, configurez le prix que les remplaçants paient pour jouer. <!-- TODO: verify exact location/label of the substitute price setting -->

{% include image.html src="help/payment-settings-substitute-prices.fr.png" caption="La configuration du prix pour les remplaçants : le revenu voulu par position, avec le montant chargé au remplaçant (frais inclus) calculé à côté de chaque champ." %}

Lorsqu'un remplaçant accepte un remplacement, une fenêtre lui demande de confirmer le paiement. La première fois, il entre sa carte de crédit; par la suite, la carte enregistrée rend le paiement instantané. S'il choisit de payer plus tard, il peut réafficher le formulaire de paiement à partir de la page de la partie, ou vous payer comptant à la partie.

Vous voyez les montants payés et impayés sur la page de chaque partie. Dans la vue **Facturation**, un remplacement impayé apparaît comme un frais en rouge; une fois payé, la balance revient à zéro et le montant devient vert. Rien à suivre à la main.

{% include image.html src="help/payment-billing-substitutes.fr.png" caption="La vue Facturation des remplaçants : les montants impayés de chaque remplaçant en rouge, avec le total perçu en vert." %}

Pour le point de vue du remplaçant, voyez [payer en ligne comme joueur](/payer-en-ligne/).

## Facturer des frais de saison aux joueurs réguliers

Une fois votre compte Stripe connecté, allez dans l'onglet **Facturation** de l'interface de gestion de votre ligue et cliquez sur **Enregistrer un frais de saison**.

{% include image.html src="help/payment-billing-season-fee-button.fr.png" caption="L'onglet Facturation avec le bouton Enregistrer un frais de saison dans l'en-tête de la section de facturation des équipes." %}

Entrez le revenu désiré pour la ligue; le montant chargé à chaque joueur, frais Stripe inclus, s'affiche à côté. Vous pouvez aussi ajouter une date d'échéance et une note. Cliquez sur **Ajouter**.

{% include image.html src="help/payment-season-fee-dialog.fr.png" caption="La fenêtre Enregistrer un frais de saison : entrez le revenu désiré pour la ligue, voyez le montant chargé à chaque joueur qui en résulte, et ajoutez au besoin une date d'échéance et une note." %}

Chaque joueur voit ensuite le frais en haut de son horaire, sur le site web et dans l'application mobile, et le paie par carte de crédit. Au fur et à mesure des paiements, l'onglet **Facturation** montre le statut de chaque joueur, mis à jour automatiquement.

{% include image.html src="help/payment-billing-season-fee-tracking.fr.png" caption="La liste de suivi des frais de saison : les joueurs notés comme payés portent le crochet vert avec la date, les joueurs impayés affichent encore leur frais en attente en rouge." %}

## Les remboursements

Les remboursements s'émettent à partir de **votre tableau de bord Stripe** (connectez-vous sur stripe.com avec le compte créé plus haut). Trouvez le paiement et remboursez-le là.

Le soutien League2GO ne peut pas émettre de remboursement : l'argent est allé directement dans votre compte Stripe et League2GO ne l'a jamais détenu. Si un joueur demande un remboursement à League2GO, il sera redirigé vers vous; voyez [qui contacter](/qui-contacter/).

## Les courriels de conformité Stripe : ne les ignorez pas

Stripe demande périodiquement des informations d'entreprise ou d'identité à jour pour garder votre compte conforme. Ces demandes arrivent **par courriel et peuvent tomber dans vos indésirables**.

Si vous n'y donnez pas suite, **Stripe suspend vos versements** : les joueurs semblent payer, mais l'argent cesse d'arriver dans votre compte bancaire. Si les paiements semblent bloqués :

* Vérifiez votre boîte de réception **et vos indésirables** pour des courriels de Stripe.
* Connectez-vous à votre tableau de bord Stripe et complétez toute vérification demandée.

## Articles reliés

* [Payer en ligne comme joueur](/payer-en-ligne/)
* [Facturation et crédits de partie](/facturation/)
* [Site web de ligue](/site-web-de-ligue/)
* [Gérer les remplaçants](/gerer-les-remplacants/)

Des questions ? Écrivez-nous à [info@league2go.com](mailto:info@league2go.com).
