# 🛒 Analyse E-commerce Brésilien — Olist

## 📌 Objectif
Analyser les données de ventes d'une plateforme e-commerce brésilienne (Olist) pour identifier les tendances de revenus, les catégories produits les plus performantes et la qualité des livraisons.

## 📦 Dataset
- Source : [Kaggle — Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- 99 441 commandes réelles entre 2016 et 2018
- 9 fichiers CSV reliés par order_id / product_id

## 🔧 Stack technique
- Python 3.11
- Pandas
- Matplotlib
- Jupyter Notebook

## 📊 Analyses réalisées
- Répartition des statuts de commandes (96.9% livrées)
- Chiffre d'affaires par statut
- Top 10 catégories produits par revenus
- Évolution des ventes mensuelles (2016 → 2018)
- Analyse des délais de livraison (93.4% à temps)

## ⚠️ Corrections appliquées
- Agrégation des paiements avant merge pour éviter la duplication des revenus
- Filtrage des dates de livraison manquantes (NaN) avant l'analyse des délais
- Exploration systématique des valeurs manquantes avant et après les merges

## 👤 Auteur
**Islem** — Data Analytics Portfolio
