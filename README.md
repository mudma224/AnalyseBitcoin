# Bitcoin Time Series Analysis & Forecasting

**Analyse avancée et prévision du prix du Bitcoin à l’aide de modèles de Time Series et de Machine Learning**

---

## 📋 Description du Projet

Ce projet consiste en une **analyse complète et une modélisation de séries temporelles** sur les données historiques du Bitcoin (2014-2025). 

L’objectif est de :
- Explorer et comprendre le comportement du Bitcoin (tendance, volatilité, cycles)
- Tester les concepts fondamentaux des time series (stationnarité, rendements, etc.)
- Comparer des modèles statistiques classiques (**ARIMA**) et des modèles de Deep Learning (**LSTM**)
- Évaluer les performances avec des métriques adaptées aux séries temporelles

Ce notebook est idéal pour une **présentation universitaire**, un **projet personnel** ou une **démo technique** en Machine Learning appliqué aux données financières.

---

## ✨ Fonctionnalités Principales

- **Nettoyage et préparation** des données OHLCV
- **Analyse Exploratoire (EDA)** : évolution du prix, log-returns, volatilité
- **Décomposition STL** et tests de stationnarité (ADF + KPSS)
- **Feature Engineering** : lags, moyennes mobiles, volatilité roulante
- **Modélisation** :
  - Modèle statistique **ARIMA**
  - Modèle Deep Learning **LSTM** (avec fenêtres glissantes)
- **Évaluation** des performances avec métriques adaptées :
  - MAE, RMSE, MAPE
  - Directional Accuracy

---

## 📊 Dataset

- **Source** : Yahoo Finance
- **Période** : 17 septembre 2014 → 20 février 2025
- **Fréquence** : Quotidienne
- **Nombre d’observations** : 3 810 jours
- **Colonnes** : Date, Open, High, Low, Close, Adj Close, Volume

---

## 🛠 Technologies Utilisées

- **Python** 3.12
- **Pandas** & **NumPy** (manipulation et calculs)
- **Matplotlib** & **Seaborn** (visualisations)
- **Statsmodels** (tests de stationnarité + ARIMA)
- **TensorFlow / Keras** (modèle LSTM)
- **Scikit-learn** (métriques d’évaluation)

---

## 📁 Structure du Projet
