# TechHorizon Groupe 1 - Projet 2 S5

## Objectif du projet
Landing page e-commerce responsive développée en HTML et CSS pour présenter une collection produit et proposer une expérience mobile/desktop fluide.

## Structure du projet
- `index.html` : page d'accueil principale
- `catalogue/catalogue.html` : page catalogue produit
- `contact/contact.html` : page contact
- `fiche-produit/fiche-produit.html` : page détail produit
- `global.css` : variables CSS et styles globaux partagés
- `layout.css` : styles de mise en page communs
- `catalogue/catalogue.css` : styles spécifiques à la page catalogue
- `images/` : dossier des images utilisées par le site

## Comment travailler sur ce projet
1. Ouvrir le dossier du projet dans l’éditeur.
2. Vérifier la branche active avec `git branch --show-current`.
3. Travailler sur une nouvelle branche si besoin :
   - `feat/catalogue-page`
   - `feat/contact-page`
   - `fix/header-layout`
4. Toujours ajouter `global.css` dans les fichiers HTML qui en ont besoin.
   - `index.html` : `./global.css`
   - pages dans des sous-dossiers : `../global.css`

## Bonnes pratiques CSS
- Mettre les variables de design dans `global.css` sous `:root`.
- Garder les styles spécifiques de page dans leur fichier dédié.
- Placer `global.css` avant les autres feuilles de style dans `<head>`.
- Préférer les classes descriptives et éviter les sélecteurs trop génériques.

## Liens de styles actuels
- `index.html` importe `./global.css` puis `./layout.css`
- `catalogue/catalogue.html` importe `../global.css` puis `catalogue.css`
- `contact/contact.html` importe `../global.css` puis `../layout.css`
- `fiche-produit/fiche-produit.html` importe `../global.css` puis `../layout.css`

## Validation rapide
- Tester en local en ouvrant les fichiers HTML dans un navigateur.
- Vérifier la responsivité via les outils de développement (mobile / desktop).

## Remarques
- Le projet est statique, il n’y a pas de build ou serveur nécessaire.
- Garder les noms de branche clairs et liés à la fonctionnalité.
- Commit message recommandé : `feat(catalogue): ajouter la page catalogue responsive`.
# TechHorizon_Group1_Projet2_S5

 Landing page e-commerce responsive développée dans le cadre de la Semaine 5 d'Akieni Academy.


## À propos

Ce projet consiste à concevoir une landing page moderne destinée à promouvoir une boutique en ligne. L'objectif est de proposer une interface élégante, responsive et intuitive offrant une expérience utilisateur agréable sur ordinateur, tablette et smartphone.


##  Objectifs

- Concevoir une interface moderne.
- Mettre en pratique HTML et CSS.
- Développer une page responsive.
- Améliorer l'expérience utilisateur.
- Respecter les bonnes pratiques du développement web.

## Fonctionnalités

- Hero Section
- Catalogue de produits
- Fiches produits
- Bouton d'appel à l'action (CTA)
- Formulaire de contact
- Navigation responsive
- Design moderne

## Technologies utilisées

- HTML
- CSS
- Git
- GitHub

## Structure du projet

```text
TechHorizon_Group1_Projet2_S5/
│
├── index.html
├── style.css
├── layout.css
├── README.md
│
├── catalogue/
├── fiche-produit/
└── contact/
```

## Responsive Design

Le projet est optimisé pour :

- Smartphones
- Tablettes
- Ordinateurs

## Installation

1. Cloner le dépôt Git.
2. Ouvrir le dossier du projet.
3. Lancer le fichier `index.html` dans un navigateur.

## Charte graphique

Le design met l'accent sur :

- une interface moderne ;
- une navigation simple ;
- une hiérarchie visuelle claire ;
- une bonne lisibilité ;
- une palette de couleurs cohérente.

## Équipe

Projet réalisé par le groupe **TechHorizon** dans le cadre de la **Semaine 5 d'Akieni Academy**.


## Licence

Projet réalisé à des fins pédagogiques.
## auteurs 
•Chislain mouyockolo

•Jude koye

•Jonathan ESAÏE 

•Luc Nkodia

•Marlond
