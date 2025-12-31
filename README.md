
# 🏠 Projet Immobilier : Modélisation et Estimation des Prix

## 📋 Présentation du Projet
Ce projet a été conçu pour une agence immobilière souhaitant automatiser et fiabiliser l'estimation des prix de vente de ses biens. L'objectif est de prédire le prix d'une maison en s'appuyant sur ses caractéristiques intrinsèques comme la surface et la localisation.

## 📊 Données et Méthodologie
L'étude repose sur un historique de **10 000 ventes**. Le projet suit un workflow complet de Data Science :
- **Analyse Exploratoire (EDA)** : Visualisation des tendances et corrélations.
- **Prétraitement** : Nettoyage des données et préparation pour les algorithmes.
- **Modélisation** : Comparaison de modèles de régression (Linéaire vs Random Forest).

## 📈 Résultats du Modèle
Le modèle **Random Forest** s'est révélé être le plus performant pour ce jeu de données :
- **Erreur Absolue Moyenne (MAE)** : ~34 178 €.
- **Précision** : Le modèle affiche une marge d'erreur moyenne de seulement **9,6 %**.

---

## 🚀 Comment utiliser ce projet ?

Suivez ces étapes pour reproduire l'analyse ou tester le modèle sur votre propre machine.

### 1. Prérequis
Vous devez avoir **Python 3.8+** installé sur votre système.

### 2. Installation et Configuration
Commencez par cloner le dépôt et installez les bibliothèques nécessaires (Pandas, Scikit-Learn, etc.) :

```bash
# Cloner le projet
git clone [https://github.com/ZINABA-Albert/analyse-marche-immobilier.git](https://github.com/ZINABA-Albert/analyse-marche-immobilier.git)

# Accéder au dossier
cd analyse-marche-immobilier

# Installer les dépendances
pip install -r requirements.txt
