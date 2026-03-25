# QSL-Mailer

Application web minimale pour envoyer par e-mail une QSL générée à partir d’un template image, en utilisant les données de QSO récupérées via l’API de Wavelog.

## Objectif V0

Cette première version permet de :

- gérer des utilisateurs locaux avec rôles `admin` et `user`
- associer un compte Wavelog à un utilisateur
- associer un SMTP à un utilisateur
- définir un compte QRZ global
- créer des templates QSL à partir d’une image de fond
- récupérer des QSOs depuis Wavelog
- générer une QSL image
- envoyer cette QSL par e-mail
- conserver un historique simple des envois

## Périmètre V0

Inclus :

- authentification locale
- 1 compte Wavelog par utilisateur
- 1 SMTP par utilisateur
- 1 compte QRZ global
- plusieurs templates par utilisateur
- prévisualisation avant envoi
- historique simple

Exclus pour le moment :

- Google SSO
- file de jobs asynchrone
- Redis
- règles avancées de sélection de template
- journal admin détaillé
- multi-Wavelog par utilisateur

## Stack technique prévue

- Python
- Flask
- PostgreSQL
- Pillow
- Docker Compose

## Arborescence

Le projet sera construit progressivement, fichier par fichier.

## Statut

Projet en cours d’initialisation.
