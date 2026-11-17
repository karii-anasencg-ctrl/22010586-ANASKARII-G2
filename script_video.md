# Trame du Script Vidéo Explicative (60 à 90 secondes)

**Durée totale** : 75 secondes  
**Format** : Capture d'écran commentée en français (720p minimum)  

---

### [00s – 15s] Introduction & Problématique
*"Bonjour, je m'appelle [Prénom Nom] du groupe [Groupe]. Dans le cadre du sujet F23, j'ai étudié la prédiction des récessions américaines à partir du spread de crédit Baa de Moody's à l'aide du Machine Learning."*

### [15s – 35s] Jeu de Données & Prétraitement sans Fuite
*"J'ai exploité 432 données mensuelles FRED de 1990 à 2025. Comme il s'agit d'une classification déséquilibrée avec 13% de récessions, j'ai créé des variables retardées à 3 et 6 mois strictly issues du passé pour éviter toute fuite d'information."*

### [35s – 55s] Algorithme & Graphique Clé
*"J'ai retenu le Random Forest Classifier avec rééquilibrage de classes. Comme on le voit sur cette courbe Précision-Rappel, le modèle surpasse très nettement la référence naïve avec un F1-score de 0,81 contre 0,00 pour la baseline."*

### [55s – 75s] Conclusion & Limites
*"En conclusion, le spread de crédit Baa s'avère être un excellent indicateur précurseur à 3-6 mois. La limite principale réside dans le faible nombre historique de récessions observées. Merci de votre attention !"*
