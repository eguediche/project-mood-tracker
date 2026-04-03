# Mood Tracker

Application web simple de suivi d'humeur, développée en HTML / CSS / JavaScript vanilla.

*A simple mood tracking web app built with vanilla HTML / CSS / JavaScript.*

---

## Aperçu / Overview

Cette application permet de journaliser son humeur quotidienne via un modal. Elle affiche la dernière humeur enregistrée avec une icône correspondante et conserve un historique des 7 dernières humeurs sous forme de cartes colorées.

*Log your daily mood through a clean modal interface. The app shows your last recorded mood with its icon and keeps a visual history of the last 7 moods with colored cards.*

---

## Stack technique / Tech Stack

| Technologie | Rôle / Role |
|---|---|
| HTML5 | Structure de l'interface / UI structure |
| CSS3 | Mise en page & design / Layout & styling |
| JavaScript ES6+ | Logique de l'application / App logic |

---

## Structure du projet / Project Structure
project-mood-tracker-main/
├── index.html          # Point d'entrée / Entry point
├── styles.css          # Feuille de styles / Stylesheet
├── app.js              # Logique JavaScript principale / Main JS logic
└── assets/             # Dossier des icônes et images
├── close.svg
├── very-happy.svg
├── happy.svg
├── neutral.svg
├── sad.svg
└── very-sad.svg
text---

## Installation & lancement / Getting Started

Aucune dépendance ni serveur requis — le projet s'ouvre directement dans le navigateur.

*No dependencies or server needed — open it straight in the browser.*

```bash
# Ouvrir dans le navigateur / Open in the browser
open index.html
Pour un meilleur confort de développement, utilise l'extension Live Server de VS Code.

Fonctionnalités / Features

Modal de saisie : Clique sur "Log Your Mood" pour ouvrir un formulaire avec 5 options d'humeur (Very Happy → Very Sad)
Dernière humeur : Affichage clair de l'humeur la plus récente avec icône et texte
Historique : Liste des humeurs précédentes (maximum 7 cartes visibles)
Design coloré : Chaque humeur a sa propre couleur distinctive
Interface propre : Design moderne et agréable


Améliorations possibles / Future Improvements

Sauvegarde des humeurs avec localStorage (les données disparaissent actuellement au rechargement de la page)
Ajout de la date pour chaque entrée
Statistiques ou graphique des humeurs
Thème sombre / clair
Possibilité de supprimer une humeur


Auteur / Author
Votre Nom — Développeur Web
GitHub · Portfolio

⭐ Ce projet est un excellent exercice pour pratiquer la manipulation du DOM, les événements JavaScript et la création de modals.
⭐ This project is a great exercise for practicing DOM manipulation, JavaScript events, and modal creation in vanilla JavaScript.
