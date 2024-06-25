---
title: Biblio-Drive
publishDate: 2020-03-02 00:00:00
img: /assets/biblio-drive.jpg
img_alt: Logo bibliothèque
description: |
  Réalisation d'un site internet pour une bibliothèque.
tags:
  - Développement Web
  - Cas d'utilisation
  - Cookie
---

## Biblio-Drive

 Suite aux dernières fermetures pour raisons sanitaires, la bibliothèque de la ville de Moulinsart a mis en place un système d’emprunt via une application en ligne. Ce projet, nommé "Biblio-Drive", permet désormais aux utilisateurs de consulter le catalogue de la bibliothèque, de réserver des livres et de gérer leurs emprunts directement depuis chez eux.

##### Modèle relationnel

Après une discussion avec Monsieur Nestor, responsable de la bibliothèque, un modèle relationnel a été élaboré pour structurer les données de l'application. Le modèle relationnel inclut les tables suivantes :

- Livres : Contient les informations sur les livres disponibles (titre, auteur, date d'ajout, etc.).

- Auteurs : Stocke les informations sur les auteurs (nom, prénom, etc.).

- Membres : Gère les informations sur les utilisateurs inscrits (nom, adresse, email, etc.).

- Emprunts : Suivi des livres empruntés (numéro de livre, numéro de membre, date d'emprunt, date de retour, etc.).

##### Diagramme de cas d'utilisation

Le diagramme de cas d'utilisation présente les interactions possibles entre les utilisateurs (visiteurs, membres, administrateurs) et l'application. Il inclut les cas d'utilisation suivants :

- Page d'accueil

- Liste des livres d'un auteur

- Détail d'un livre

- Se connecter

- Voir panier

- Ajouter un livre (administrateur)

- Créer un membre (administrateur)

##### Travail réalisé

Le développement de l'application a inclus le codage des cas d'utilisation mentionnés ci-dessus. Les accès à la base de données ont été réalisés via des requêtes préparées pour garantir la sécurité et l'efficacité des opérations. Les mots de passe des utilisateurs ont été encryptés conformément aux meilleures pratiques.

Pour la gestion des styles, le framework Bootstrap a été utilisé, assurant ainsi une interface utilisateur moderne et réactive. De plus, l'application intègre la conformité au RGPD via le plugin Tarteaucitron, permettant de gérer les consentements aux cookies et les services tiers comme Facebook ou YouTube.
