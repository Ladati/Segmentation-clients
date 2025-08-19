# Segmentation-clients

Ce projet consiste à réaliser une segmentation des clients d’un centre commercial à partir du dataset Mall_Customers
disponible sur [Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## Objectif
Créer des groupes de profils clients et de les classer selon leurs caractéristiques (âge, revenu, score d’achat, etc.) en utilisant des techniques de machine learning non supervisé, notamment l’algorithme K-Means.

---

## Contenu du dépôt

- `segmentation.ipynb` : le notebook Jupyter contenant toutes les étapes d’analyse (nettoyage, exploration, visualisations,segmentation, interprétations, conclusion).
- `segmentation.csv` : fichier csv utilisé pour l’analyse et la segmentation
- `README.md` : fichier de présentation.

---

## Méthodologie

L’étude comprend :
- **Analyses exploratoires** des données pour mieux comprendre les caractéristiques des clients
- **visualisations** des variables clés (âge, revenu, score client, genre, etc.).
- **Analyse en Composante Principales (ACP)** linéaire et non linéaire afin de réduire la simensionnalité et mieux visualiser les relations entre variables.
- **Segmentation des clients** à l'aide d'algorithmes de classification (notamment k-Means), avec une **interprétation des groupes obtenus** 

---

## Résultats clés

- **Répartition par genre** : la majorité des clients sont des femmes.
- **Profil d’âge et de revenu** : le centre attire principalement de jeunes adultes avec un âge situé autour de la trentaine dont la plupart ont un revenu modeste.
- Segmentation clients : Trois catégories distincts :
    * Clients occasionnels : d'âge plus avancé, avec un revenu moyen
    * Clients moyennement fidèles : très jeunes disposant d'un revenu faible
    * Clients premium : jeunes adultes, à un revenu élevé et très engagés

---

## Remarques

Ce projet est principalement descriptif et inclut une approche de classification.
Il s’agit de mon deuxième projet personnel dans le domaine de la data science.

Je reste ouverte à toutes suggestions et critiques constructives pour continuer à progresser.

---

## À propos de moi

Étudiante en Master 2 de Statistique Économétrique, passionnée par l’analyse de données et en pleine évolution vers le métier de data scientist.

Ce projet fait partie de mon portfolio personnel que je construis au fil de mon apprentissage.

---

## Prochain projet en cours : `Exploration du machine learning appliqué au domaine agro-alimentaire.`
