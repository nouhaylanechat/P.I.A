# Projet P.I.A — Prédiction de la Performance Académique

## 📌 Objectif
Ce projet vise à prédire la **classe de notes** (Grade A, B ou C) des étudiants en fonction de plusieurs variables telles que les heures d’étude, les examens, le travail en groupe, etc.

## 🧠 Modèles utilisés
- **Régression Logistique** (meilleure performance)
- **K-Nearest Neighbors (KNN)**
- **Random Forest**

## 🧪 Méthodologie
- Nettoyage des données (suppression doublons, vérification des valeurs manquantes)
- Analyse exploratoire (graphiques, corrélations)
- Séparation des données (80% entraînement, 20% test)
- Entraînement des modèles et évaluation avec :
  - **Précision**
  - **Recall**
  - **F1-score**
- **Validation croisée à 5 plis**
- **Optimisation des hyperparamètres** avec GridSearchCV

## 🏆 Résultats
- Le modèle **Logistic Regression** a donné les meilleurs résultats globaux, avec un bon équilibre entre précision et rappel.
- KNN et Random Forest ont été testés également mais étaient moins stables.

## 💾 Sauvegarde du modèle
Le modèle final a été sauvegardé avec `joblib` pour une future utilisation.

## 👩‍💻 Réalisé par :
- Nechat Nouhayla
- Fedol Fatimazahra
- Borzal Fatimazahra
