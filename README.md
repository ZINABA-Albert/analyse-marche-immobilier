#  Projet Immobilier : Estimation du prix des maisons

##  Présentation du Projet
Ce projet a été réalisé pour répondre aux besoins d'une agence immobilière souhaitant automatiser l'estimation des prix de vente de ses biens. L'objectif principal est de construire un modèle de Machine Learning capable de prédire avec précision le prix d'une maison en fonction de ses caractéristiques (surface, quartier, etc.).

##  Les Données
Le modèle s'appuie sur un historique de **10 000 ventes immobilières**. Chaque observation comprend des variables clés telles que :
- La surface habitable.
- La localisation (quartier).
- Les caractéristiques intrinsèques du bien (nombre de chambres, salles de bain, etc.).

##  Méthodologie
Le projet suit une démarche rigoureuse de Data Science structurée en plusieurs étapes :
1. **Chargement et Inspection** : Analyse de la structure et de la qualité des données.
2. **Visualisation (EDA)** : Exploration graphique pour comprendre les corrélations.
3. **Prétraitement** : Nettoyage et préparation des données pour les algorithmes.
4. **Modélisation** : Entraînement de modèles de régression (Linéaire et Random Forest).
5. **Évaluation** : Mesure de la performance via des métriques comme la MAE (Erreur Absolue Moyenne).

##  Résultats et Performances
Le modèle final utilisant l'algorithme **Random Forest** a montré d'excellents résultats :
- **MAE (Erreur Absolue Moyenne)** : ~34 178 €.
- **Précision** : Le modèle affiche une marge d'erreur moyenne de seulement **9,6 %** par rapport au prix réel.

---

##  Guide d'Installation et d'Utilisation

Suivez ces étapes pour configurer le projet et reproduire l'analyse sur votre machine.

### 1. Prérequis
Assurez-vous d'avoir installé **Python 3.8** ou une version supérieure.

### 2. Configuration de l'environnement
Clonez le dépôt sur votre ordinateur et installez les bibliothèques nécessaires :

```bash
# Cloner le projet
git clone [https://github.com/ZINABA-Albert/analyse-marche-immobilier.git](https://github.com/ZINABA-Albert/analyse-marche-immobilier.git)

# Entrer dans le dossier du projet
cd analyse-marche-immobilier

# Installer les dépendances (pandas, scikit-learn, seaborn, etc.)
pip install -r requirements.txt
