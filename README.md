# Les Talents Lillois — FIVE
Prototype frontend responsive.

## Ouvrir
Ouvre `index.html` dans un navigateur.

## Architecture cible
Frontend: Next.js/React
Backend: API
Base de données: PostgreSQL
Paiement: prestataire de paiement sécurisé
Fonctions: comptes clients, disponibilités, réservations terrain/bar, paiements, emails, back-office.

Les joueurs célèbres sont représentés ici par des placeholders : les photos réelles devront être utilisées avec les droits/licences appropriés.


## Hero
Le hero est maintenant un line-up de plusieurs joueurs (Doué, Yamal, Messi au second plan, Ronaldo au premier plan), superposés en CSS dans `.lineup` avec des masques dégradés et une légère animation de zoom (désactivée si `prefers-reduced-motion`).

Les images sont dans `assets/players/` : `doue.jpg`, `yamal.jpg`, `messi.jpg`, `ronaldo.jpg`. Pour changer un joueur, remplace simplement le fichier (mêmes noms) ou ajoute une balise `<img class="p ...">` dans `.lineup` de `index.html` puis règle sa position dans `style.css`.

Les trois premiers visuels sont des recadrages de la maquette, agrandis par super-résolution (x4) : ils sont un peu moins nets que Ronaldo. Pour un rendu optimal, les remplacer par des visuels HD (au moins 1400 px de large).

`cristiano-hero.png` n'est plus utilisé (la maquette complète contenait du texte et une interface intégrés) ; il peut être supprimé.

Droits : les photos réelles de joueurs (Ronaldo, Messi, Yamal, Doué) et les maillots/logos de clubs visibles doivent être utilisés avec les droits/licences appropriés avant toute mise en production commerciale.
