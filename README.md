# P6 Optimisez la gestion des données d'une boutique avec Python

## Contexte

BottleNeck est un marchand de vin. Ses données sont réparties entre plusieurs outils (ERP, site web, table de liaison) dont les références ne correspondent pas.
Ma mission était de rassembler ces données, de repérer les erreurs et d'analyser les ventes et les stocks du mois d'octobre pour le comité de direction.

## Objectifs

- Rapprocher les exports de l'ERP et du site web grâce à la table de liaison
- Identifier les erreurs dans les données et proposer des corrections
- Analyser le chiffre d'affaires, les meilleures ventes et les stocks
- Détecter les valeurs aberrantes dans les prix
- Étudier les liens entre les données quantitatives

## Réalisations

- Nettoyage et jointure des trois fichiers
- Repérage des erreurs (saisie, type, calcul, jointure, doublons)
- Chiffre d'affaires par produit et total
- Analyse des meilleures ventes avec la règle des 20/80
- Détection des prix aberrants avec le Z-score, l'écart interquartile et un boxplot
- Analyse des taux de marge, de la rotation et du nombre de mois de stock
- Matrice de corrélation entre prix, ventes, stock et marge
- Recommandations pour fiabiliser les données

## Outils

Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn

## Compétences

- Rapprocher et nettoyer plusieurs sources de données
- Contrôler la qualité et la cohérence des données
- Détecter des valeurs aberrantes
- Calculer et interpréter des indicateurs de vente et de stock

## Fichiers

- `analyse_bottleneck.ipynb` notebook de l'analyse
