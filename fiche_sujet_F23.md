# Fiche du Sujet F23 — Spread de crédit Baa et récessions

## 1. Caractéristiques du Sujet
* **Identifiant :** F23
* **Thème :** Spread de crédit Moody's Baa et détection des récessions économiques américaines (NBER).
* **Tâche de Machine Learning :** Classification binaire déséquilibrée.
* **Période d'analyse :** 1990 à 2025 (données mensuelles).
* **Source des données :** FRED (Federal Reserve Bank of St. Louis) / Moody's / NBER.

## 2. Objectifs & Métriques
* **Problématique :** Déterminer dans quelle mesure le niveau et la vitesse de variation du spread Baa permettent d'anticiper les récessions économiques aux États-Unis.
* **Métrique principale :** F1-score et PR-AUC (Area Under the Precision-Recall Curve).
* **Référence naïve :** Prédiction constante de la classe majoritaire (absence de récession).

## 3. Algorithmes Éligibles
* **Algorithme principal retenu :** Random Forest Classifier (Algorithme 14 du support).
* **Algorithmes alternatifs / de comparaison :** Régression Logistique (Algorithme 8), Arbres de Décision (Algorithme 11, 12), AdaBoost / XGBoost (Algorithmes 15, 16).

## 4. Protocole d'Évaluation Sans Fuite
* **Découpage Temporel :** Train (1990–2017) / Test (2018–2025).
* **Standardisation & Imputation :** Réalisées uniquement sur le sous-ensemble d'entraînement.
* **Variables Retardées (*Lags*) :** $t-3$ et $t-6$ construites strictement avec le passé.
