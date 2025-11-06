# TP Recommandation — Système de Recommandation Intelligent pour l’E-commerce

## Description

Ce projet a pour objectif de concevoir un **système de recommandation intelligent** pour une startup e-commerce spécialisée dans la vente de produits technologiques.  
L’objectif est d’améliorer l’expérience utilisateur tout en augmentant le **chiffre d’affaires** via des recommandations personnalisées et performantes.

Le projet se compose de **5 notebooks Jupyter** constituant un pipeline complet, de la génération des données à l’évaluation finale des modèles.

---

## Architecture du Projet

TP_Recommandation/
│
├── data/
│ ├── generate_data.py
│ ├── interactions.csv
│ ├── products.csv
│ ├── products_features.csv
│ ├── users.csv
│ └── users_features.csv
│
├── notebooks/
│ ├── 00_Guide_Demarrage.ipynb
│ ├── 01_EDA_starter.ipynb
│ ├── 02_Features_starter.ipynb
│ ├── 03_Modeling_starter.ipynb
│ ├── 04_Evaluation_starter.ipynb
│ ├── metadata.json
│ └── README_NOTEBOOKS.txt
│
├──  requirements.py
└── README.md



---

## Objectifs

### Objectifs Business
- **Augmenter le panier moyen de 15 %**
- **Améliorer le taux de conversion de 20 %**
- **Réduire le taux de rebond sur les pages produits**

### Contraintes Techniques
- **Temps réel** : recommandations en moins de 200 ms  
- **Volume** : 100 000 utilisateurs, 10 000 produits  
- **RGPD** : anonymisation et confidentialité respectées  
- **Budget** : infrastructure optimisée (coût / performance)

### Objectifs Pédagogiques
À l’issue du projet, vous serez capable de :
1. Analyser un besoin métier et définir une stratégie data  
2. Concevoir un pipeline ML de bout en bout  
3. Implémenter plusieurs algorithmes de recommandation  
4. Évaluer leurs performances à l’aide de métriques adaptées  
5. Déployer un modèle dans une approche MLOps  
6. Documenter un projet de manière professionnelle  

---

## Description des Notebooks

### **00_Guide_Demarrage.ipynb**
- Installation et configuration de l’environnement  
- Génération de données synthétiques  
- Premiers tests de pipeline  
- Fonctions utilitaires de base  

### **01_EDA_starter.ipynb**
- Analyse exploratoire des données  
- Statistiques descriptives et visualisations  
- Identification des biais et des valeurs manquantes  
- Étude du problème de **cold start**  

### **02_Features_starter.ipynb**
- Feature engineering utilisateurs et produits  
- Création de variables comportementales et temporelles  
- Normalisation, encodage, et gestion des valeurs manquantes  
- Analyse de corrélation entre variables  

### **03_Modeling_starter.ipynb**
- Implémentation de trois approches :
  - **Filtrage Collaboratif (User-Based)**  
  - **Filtrage par Contenu (Content-Based)**  
  - **Modèle Hybride (ML supervisé)**  
- Comparaison préliminaire des performances  

### **04_Evaluation_starter.ipynb**
- Implémentation des métriques : `Precision@K`, `MAP`, `NDCG`  
- Évaluation des trois modèles  
- Comparaison finale et interprétation business  
- Calcul des métriques métiers : couverture, diversité, nouveauté, latence  




