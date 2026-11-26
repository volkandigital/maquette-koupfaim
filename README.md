# Le Koup’Faim — maquette du site

Maquette du site internet du kebab **Le Koup’Faim**, 16 rue du Général de Gaulle, 59400 Cambrai : carte en ligne et commande à emporter ou en livraison dans le Cambrésis.

Réalisée par **NK Digital** — nkdigital.fr

## Contenu

- `index.html` : le site complet (HTML, CSS et JavaScript, sans installation)
- `img/` : photos des plats et photo de couverture (WebP)

## Fonctionnalités

- Présentation façon Uber Eats : bannière, onglets de catégories, fiches produit avec options
- Vraie carte du restaurant avec les prix des flyers (les prix manquants sont affichés « Prix à confirmer »)
- Sauces, suppléments fromage (1,50 €) et viande (prix par viande), tacos à composer, boisson en plus
- Assiettes : 1 sauce pour les frites incluse, sauce en plus 0,70 €
- Commande à emporter ou en livraison (4 zones, 15 km maximum), précommande quand c’est fermé
- Paiement par carte en ligne ou au retrait / à la livraison (espèces ou TPE)
- Frais de service de 1 € par commande en ligne, réduction de 1 € pour un paiement au retrait ou à la livraison
- E-mail de confirmation demandé à la commande, suivi de commande, bouton « Recommander »
- Écran cuisine (`#cuisine`) : colonnes par statut, bip, délais réglables pendant les rushs
- Pages légales : mentions légales, CGV, confidentialité, allergènes et origine des viandes

## Maquette

Les commandes restent dans le navigateur : rien n’est envoyé au restaurant. La version finale enverra les commandes à une base de données (Supabase), le paiement en ligne passera par Stripe et les tickets seront imprimés en cuisine sur l’imprimante Star TSP100.

## À compléter avant la mise en ligne

- Prix manquants (tacos, Tex Mex, frites, glaces, etc.) et frais de livraison réels
- Capital social, allergènes plat par plat, origine des viandes manquantes
- Adhésion au médiateur de la consommation (CM2C)
