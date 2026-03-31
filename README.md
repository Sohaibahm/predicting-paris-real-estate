# 🏠 Prévision des prix immobiliers à Paris

## 📌 Présentation du projet

Ce projet a pour objectif d’analyser et de prédire l’évolution des prix immobiliers à Paris à l’aide de modèles de séries temporelles.

À partir des données publiques DVF (Demandes de Valeurs Foncières), nous construisons une série temporelle mensuelle du prix au mètre carré afin d’étudier les dynamiques du marché et proposer des modèles de prévision.

---

## Objectifs

* Analyser les transactions immobilières à Paris
* Construire une série temporelle fiable du prix au m²
* Identifier les tendances et la saisonnalité
* Appliquer des modèles statistiques (ARIMA, SARIMA, SARIMAX)
* Évaluer les performances des modèles

---

## Données

* Source : DVF (Demandes de Valeurs Foncières)
* Zone : Paris
* Volume : plus de 120 000 transactions
* Variables utilisées :

  * Prix de transaction
  * Surface du bien
  * Date de vente

---

## Préparation des données

* Nettoyage des données (valeurs aberrantes, incohérences)
* Calcul du prix au mètre carré
* Agrégation mensuelle
* Filtrage des observations pertinentes

---

## Analyse exploratoire

* Étude de la distribution des prix
* Détection des outliers
* Analyse des tendances
* Visualisation de la saisonnalité
* Moyenne mobile sur 12 mois

---

## Analyse statistique

* Test de normalité (Shapiro-Wilk)
* Test de stationnarité (ADF)
* Analyse des autocorrélations (ACF / PACF)

---

## Modélisation

* **ARIMA (0,1,1)** → meilleur modèle retenu
* SARIMA → prise en compte de la saisonnalité
* SARIMAX → test avec variables exogènes


---

## Résultats clés

* Le marché immobilier parisien est fortement inertiel
* Les prix passés influencent fortement les prix futurs
* La saisonnalité est présente mais modérée
* Les modèles simples (ARIMA) sont les plus performants

---

## Limites

* Agrégation des données (perte d’information géographique)
* Période d’étude relativement courte (~5 ans)
* Variables exogènes limitées
* Absence d’analyse par arrondissement

---

## Améliorations possibles

* Analyse par arrondissement ou type de bien
* Intégration de variables macroéconomiques (taux d’intérêt, inflation)
* Validation croisée temporelle
* Utilisation de modèles de machine learning (XGBoost, Prophet, LSTM)

---

## Technologies utilisées

* Python
* Pandas / NumPy
* Matplotlib / Seaborn
* Statsmodels

---

##  Auteur : HASSIB Sohaib

Projet de data science centré sur l’analyse de séries temporelles et le marché immobilier.

---
