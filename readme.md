# Agence IMMBOULLIER

Notre prestataire du jour est une agence immobilière nommé **IMMBOULLIER**.

Cet agence souhaiterait avoir un **site web** pour **lister,ajouter,modifier** ses **annonces** immobilières.

## Cahier des charges

Un ***dashboard*** afin d'administrer les annonces immobilières :

- **Lister** toutes les annonces
- **Ajouter** une annonce
- **Modifer** une annonce
- **Supprimer** une annonce

Deux forumlaires pour **ajouter** et **modifier** une annonce.

La page d’**accueil** du site web devra **lister** tous les biens immobiliers.

L'affichage d'un bien immobilier devra être ainsi dans l'ordre :

- **Titre** de l'annonce , préciser le **type** de bien immobilier (**location/vente**)
- **Image** du bien immobilier
- **Description** du bien immobilier
- **Surface** , **nombre de pièces** du bien immobilier
- **Prix** du bien immobilier
- **Estimation énergétique**
- **Emission de CO2**

La base de donnée se nommera **immoboullier**.

Une table **annonce** devra avoir les champs suivants :

```
id
title
description
image
type
price
surface
room
energy
pollution
created_at
modified_at
```

Détail du formulaire pour ajouter une annonce :

- Le champ **type** devra avoir deux choix **vente** ou **location**
- Le champ **prix** est libre
- Le champ **surface** correspond à la superficie du bien immobilier , il est libre
- Le champ **piéces** correspond aux nombres de pièces du bien immobilier , c'est une liste déroulante avec les choix suivants 1,2,3,4,5 pièces
- Avoir la possibilité de **téléverser** une **image** du bien immobilier
- L'**estimation énergétique** et la **pollution au CO2** sont  un choix multiple : **A,B,C,D,E,F,G**

# GIT

- Créer un **dépôt** sur un service tel que github ou autre pour y héberger votre travail
- Faire des **commits** atomiques
- Travailler sur branche **develop** et abuser des **branches** pour votre travail
- **Partager** votre dépôt en **privée** avec une invitation

# Data

Exporter votre **MCD** (Modèle Conceptuel des Données) c'est à dire votre **schema de base de donnée** avec l'option pour **créer la base de donnée en sql** , que vous mettrez dans un dossier **data**.

Dans le même dossier **data** , mettez des **captures d’écrans** de votre projet afin que je puisse vérifier votre travail.

# Code

- Utiliser l'architecure **MVC** vue ensemble
- Bien avoir un **code** lisible , **bien indenté**
- Ne pas hésiter à ajouter des **commentaires**
- **Aérer** votre code pour qu'il soit agréable à lire pour vous et les autres
- Soyez cohérent , pensez toujours à quelqu'un qui reprend ou lit votre code
- **Personnaliser** votre code afin qu'il soit unique
- Ne laissez **AUCUN code,nom de variable,fonctions** , d'un projet précédent

# Design

- Aucune **feuille de style externe** du type bootstrap,etc... ne devra être utilisés
- Faire votre propre **feuille de style**
- Soigner votre **design**

# Barème de notation

- **Git** /2
- **Base de donnée** /3
- **Frontend HTML/CSS** /4
- **Backend PHP** /10
- **Clean Code** /1
