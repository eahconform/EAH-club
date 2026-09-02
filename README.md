# EAH CLUB

Projet de carte de fidélité NFC pour boutique de prêt-à-porter.

## Site internet

Site GitHub Pages :

https://eahconform.github.io/EAH-club/

Dépôt GitHub :

EAH-club


## Google Apps Script

Nom du projet Apps Script :

EAH CLUB - Gestion cartes NFC

Le projet contient actuellement un seul fichier :

Code.gs

Fonctions principales :

- setupEAH() : crée le Google Sheet et les 100 premières cartes
- configurerMonSite() : configure l'adresse GitHub Pages
- updateSiteUrl() : modifie l'URL utilisée par les cartes
- ajouterCartes(nombre) : ajoute de nouvelles cartes
- ajouter50Cartes() : ajoute 50 cartes
- ajouter100Cartes() : ajoute 100 cartes
- doGet() / doPost() : communication entre le site et Google Sheets

IMPORTANT :

Ne pas relancer setupEAH() pour ajouter des cartes.

Pour un réassort de 100 cartes, exécuter :

ajouter100Cartes()


## Google Sheet

Nom :

EAH Boutique - Club NFC https://docs.google.com/spreadsheets/d/1RRmuVex0_BYSAutMA4swNu5-gujgRXufueX72yj6j4Q/edit

Onglets :

- CARTES
- PARAMETRES
- ARTICLES
- OFFRES
- RESERVATIONS


## Fonctionnement NFC

Chaque carte possède un TOKEN unique.

Exemple :

https://eahconform.github.io/EAH-club/?card=TOKEN

Lors de la première utilisation, le client active sa carte avec son prénom et son anniversaire.

Une fois activée, le TOKEN reste associé au client dans Google Sheets.


## Réassort

Pour ajouter 50 nouvelles cartes :

ajouter50Cartes()

Pour ajouter 100 nouvelles cartes :

ajouter100Cartes()

Les anciennes cartes et les anciens clients ne sont pas modifiés.


## Sauvegarde Apps Script

Conserver également une copie du fichier Code.gs dans ce dépôt GitHub.

Nom conseillé :

Code.gs

Ne jamais mettre de mot de passe, clé privée ou information confidentielle dans ce README.


## EAH CLUB

Offre commerciale envisagée :

- 100 cartes NFC personnalisées
- site vitrine
- 10 articles phares
- carte Club nominative
- offre anniversaire
- offres réservées aux membres
- réseaux sociaux
- avis Google
- réservation d'article pendant 24 heures

Maintenance :

19,99 € / mois

1 modification par semaine.
