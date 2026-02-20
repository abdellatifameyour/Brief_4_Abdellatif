# Projet Dashboard Ventes – Analyse & Visualisation des Données

##  Structure des données

Les fichiers sources contiennent :
* Date de vente
* Produit
* Région
* Chiffre d’affaires
* Quantité vendue
* Panier moyen
* Source de trafic
* Délai de livraison
* Retour produit
* Taux de satisfaction


##  Étapes de réalisation

###  Vérification & préparation

* Harmonisation des noms de colonnes
* Uniformisation des formats (date, texte, nombres)
* Correction des incohérences

###  Consolidation avec Power Query

* Importation de tous les fichiers
* Vérification des types de données
* Fusion en une table unique
* Nettoyage :
  * suppression des doublons
  * gestion des valeurs nulles
* Chargement dans la feuille **Données**

###  Création des TCD

TCD créés pour analyser :

* Évolution du CA
* Ventes par produit
* Ventes par région
* Nombre de ventes
* Livraison à temps
* Retours produits
* Satisfaction client
* Sources de trafic
* Panier moyen

Bonnes pratiques :

* Vérification des totaux
* Format monétaire pour le CA
* Formats numériques harmonisés

###  Graphiques interactifs

Graphiques réalisés :

* Évolution des ventes dans le temps
* CA par produit
* Ventes par région
* Délai moyen de livraison
* Taux de retour & livraison
* Satisfaction client
* Sources de trafic
* KPI principaux

###  Construction du dashboard

* Organisation des graphiques par zones
* Hiérarchie visuelle claire
* Ajout d’icônes et éléments visuels
* Cohérence des couleurs et typographie

###  Indicateurs clés (KPI)

**Chiffre d’affaires total**
**Panier moyen**
**Meilleur produit**
**Nombre d’unités vendues**

###  Segments & filtres dynamiques

Segments ajoutés :

* Année
* Produit
* Région
* Source de trafic

Fonctionnalités :

* filtres multi-sélection
* connexions à tous les TCD

###  Gestion des erreurs

* Correction du meilleur produit ≠ “Total général”
* Utilisation de `SIERREUR()`
* Vérification du bon calcul des MAX()

###  Actualisation des données

* Ajouter un nouveau fichier dans le dossier source
* Actualiser les requêtes et TCD
* Vérifier la mise à jour automatique du dashboard
