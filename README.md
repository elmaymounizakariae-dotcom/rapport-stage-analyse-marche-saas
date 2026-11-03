
# Analyse Intelligente du Marché SaaS

<p align="center">
  <strong>Projet de Fin d'Études — KIINOV</strong><br>
  Analyse intelligente du marché SaaS : conception d'une plateforme d'analyse et d'aide à la décision basée sur l'IA
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Machine_Learning-FF6F00?style=for-the-badge">
  <img src="https://img.shields.io/badge/Generative_AI-8A2BE2?style=for-the-badge">
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite">
</p>

---

## Présentation du projet

Ce projet de fin d'études, réalisé au sein de **KIINOV**, porte sur la conception et le développement d'une plateforme intelligente dédiée à l'analyse, la classification et la recommandation des solutions SaaS de facturation.

La plateforme combine la Data Science, le Machine Learning, l'Intelligence Artificielle Générative et les méthodes multicritères d'aide à la décision afin de faciliter l'évaluation et la comparaison des solutions SaaS.

**Période :** Avril – Juin 2026

## Objectifs et réalisations

- Conception et développement d'une plateforme intelligente d'analyse et d'aide à la décision.
- Constitution et enrichissement d'un dataset de plus de **1 400 solutions SaaS**, structuré autour de 31 variables fonctionnelles, techniques et économiques.
- Réalisation d'analyses exploratoires (EDA) et préparation des données.
- Augmentation synthétique des données avec CTGAN et SMOTE.
- Développement et évaluation de modèles de Machine Learning.
- Mise en place d'un moteur de recommandation multicritère basé sur WSM et TOPSIS.
- Intégration d'un assistant conversationnel basé sur LLaMA 3.3 70B et RAG.

## Approches et méthodes

| Domaine | Méthodes et techniques |
|---|---|
| Analyse des données | EDA, KPI |
| Classification | Random Forest, SVM, Gradient Boosting, KNN |
| Régression | Régression multiple |
| Clustering | K-Means |
| Augmentation des données | CTGAN, SMOTE |
| Explicabilité | SHAP |
| Aide à la décision | MCDM, WSM, TOPSIS |
| IA générative | LLM, LLaMA 3.3 70B, Groq API, RAG, NLP |

## Technologies et outils

**Langages**
- Python, SQL, JavaScript, HTML5, CSS3.

**Data Science et Machine Learning**
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.

**Intelligence Artificielle Générative**
- LLM, LLaMA 3.3 70B, Groq API, RAG, NLP.

**Machine Learning avancé**
- Random Forest, SVM, Gradient Boosting, CTGAN, SMOTE, SHAP.

**Analyse décisionnelle**
- MCDM, TOPSIS, WSM, EDA, KPI.

**Développement Backend**
- Flask, API REST, JSON.

**Base de données**
- SQLite.

**Évaluation des modèles**
- Accuracy, AUC-ROC, Cross-Validation, MAE, RMSE.

## Architecture générale

```text
Dataset SaaS
     |
     v
Préparation et analyse des données
     |
     v
Machine Learning
     |
     +----------------------+
     |                      |
     v                      v
Classification          Recommandation
et prédiction           WSM / TOPSIS
     |                      |
     +-----------+----------+
                 |
                 v
          Backend Flask
                 |
       +---------+---------+
       |                   |
       v                   v
  Assistant IA         Système RAG
  LLaMA 3.3 70B       Base documentaire
       |                   |
       +---------+---------+
                 |
                 v
        Interface utilisateur
```

## Équipe du projet

**Réalisé par :**
- Zakariae El Maymouni
- Fatima Zahrae El Kostit

**Encadrement académique :**
- Pr. Sara Ahsain
- Pr. Abdellah Azmani

**Établissement :** Faculté des Sciences et Techniques de Tanger  
**Université :** Abdelmalek Essaâdi  
**Formation :** Licence Analytique des Données  
**Année universitaire :** 2025–2026

## Rapport de stage

Le rapport détaillé du projet est disponible dans ce dépôt :

📄 **Rapport_de_Stage.pdf**

---

<p align="center">
  Projet de Fin d'Études · KIINOV · 2026
</p>
