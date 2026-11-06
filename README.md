# Mon Sans Graya

Smart meal planner pour Abidjan : espace client (programme de repas hebdo/mensuel, commande groupée, synchro Apple/Google Calendar, rappel 1 h avant livraison, modification jusqu'à 09h) et espace restaurateur (commandes et livraisons, carte, stocks, personnel et shifts, gérants avec droits par module, indicateurs multi-restaurants).

- Interface en français, prix en FCFA, paiement à la livraison.
- Hébergement et base de données : [Floot](https://floot.com) (projet `ceeddfd4-9f75-4742-b19e-c039040ac1eb`).

## Ce dépôt

Copie du code source exporté depuis Floot (Get Code → Download as ZIP). Floot reste la source de vérité :
les modifications se font dans Floot, puis on ré-exporte le ZIP ici et on commit.

## Structure

- `pages/` : écrans (`client.*` espace client, `pro.*` espace restaurateur)
- `components/` : composants UI
- `endpoints/` : API (GET/POST + schémas zod)
- `helpers/` : logique partagée (auth, formatage, rappels, accès par module)
- `base.css` : thème (clair/sombre)
