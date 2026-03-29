# Give Me Some Credit — Credit Risk Modeling

## 📌 Description

Ce projet s’inscrit dans le cadre de la compétition Kaggle **"Give Me Some Credit"**, dont l’objectif est de prédire la probabilité de défaut de paiement d’un client à partir de données financières et comportementales.

Dans ce travail, les données utilisées ont été **anonymisées**, tout en conservant leur structure et leurs propriétés statistiques, afin de respecter les contraintes de confidentialité.

---

## 🎯 Objectifs

- Prédire le risque de défaut de paiement (classification binaire)
- Explorer et comprendre les données financières
- Mettre en place des modèles de machine learning robustes
- Évaluer les performances des modèles à l’aide de métriques adaptées (AUC, accuracy, etc.)

---


---

## ⚙️ Méthodologie

Le projet suit les étapes classiques d’un pipeline de data science :

### 1. Analyse exploratoire (EDA)
- Étude de la distribution des variables
- Analyse des valeurs manquantes
- Identification des variables importantes

### 2. Prétraitement des données
- Gestion des valeurs manquantes
- Normalisation / standardisation
- Feature engineering

### 3. Modélisation
- Implémentation de modèles de classification (logistique, arbres, etc.)
- Comparaison des performances

### 4. Évaluation
- Utilisation de métriques adaptées au déséquilibre des classes (ROC-AUC)
- Validation des résultats

---

## 📊 Résultats

Les résultats détaillés, ainsi que les visualisations et les performances des modèles, sont disponibles dans le fichier :

👉 `main.py`

Ce fichier contient l’ensemble du pipeline, de l’analyse exploratoire jusqu’à l’évaluation finale.

---

## 🛠️ Technologies utilisées

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🚀 Lancer le projet

1. Cloner le dépôt :
```bash
git clone <repo_url>
cd give-me-some-credit
```
2. Installer les dépendances :
```bash
pip install -r requirements.txt
```