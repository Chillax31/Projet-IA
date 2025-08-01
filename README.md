# 📡 Traffic Classification with Supervised Machine Learning

Projet de classification automatique de trafic réseau à l’aide d’algorithmes d’apprentissage supervisé.

---

## 📋 Description

Ce projet s’inscrit dans le cadre d’une démarche pédagogique visant à :
- Appliquer des techniques de **Machine Learning supervisé**
- Sur un **jeu de données réseau massif** (jusqu’à 1 million d’échantillons)
- En vue de **classifier les flux** selon leur type (YouTube, VoIP, Browsing, Attack, etc.)

Le projet a été réalisé avec **Python 3**, dans un environnement **VS Code + JupyterLab**, et utilise principalement la bibliothèque **scikit-learn** pour la modélisation.

---

## 🎯 Objectifs

- Explorer, nettoyer et préparer un grand volume de données réseau
- Implémenter et comparer trois modèles de classification :
  - K-Nearest Neighbors (KNN)
  - Arbre de Décision
  - Forêt Aléatoire (Random Forest)
- Évaluer les modèles à l’aide de métriques standards (accuracy, F1-score, matrice de confusion)
- Visualiser les performances de manière pédagogique
- Proposer des axes d’amélioration

---

## 🗂 Structure du dépôt

```bash
.
├── Projet-IA/
   └── datas.csv                                                                                  # (à ajouter manuellement - non inclus)
   └── TP_Classification_Trafic_Ndiaya_GUEYE_&_LOUNGOU_BIYENDOLO_Quentin_Evrard_VCC_M1.ipynb      # Exploration et prétraitement, Entraînement des modèles, Visualisations et analyse comparative
   └── README.md                                                                                  # Présentation du projet
   └── requirements.txt                                                                           # Bibliothèques Python requises

📌 Auteurs & encadrement
Étudiants : Ndiaya_GUEYE_&_LOUNGOU_BIYENDOLO_Quentin_Evrard_VCC_M1

Encadrant pédagogique : M. SY

Projet réalisé dans le cadre du cours :  Classification automatique du trafic réseau par apprentissage supervisé
