# 🏠 Analyse du Marché Immobilier

## 📋 Description
Ce projet consiste en une analyse approfondie du marché immobilier à partir de données de transactions immobilières. L'analyse inclut le prétraitement des données, des statistiques descriptives, une analyse approfondie des variables clés et des visualisations.

## 🏗️ Structure du Projet
Le projet est divisé en quatre parties principales :

### 1. 🧹 Prétraitement des Données
- Nettoyage et préparation des données
- Gestion des valeurs manquantes
- Correction des incohérences
- Transformation des types de données
- Fusion des tables clients et propriétés
- Résultat : DataFrame de 267 lignes et 19 colonnes

### 2. 📊 Statistiques Descriptives
- Analyse des variables numériques
- Performance par type de bâtiment
- Analyse des ventes par pays et par État
- Utilisation de méthodes comme pandas.cumsum() pour les fréquences cumulées

### 3. 📈 Analyse des Données
Analyse approfondie incluant :
- Segmentation des clients par âge avec les intervalles suivants :
  - (19.0, 25.0]
  - (25.0, 31.0]
  - (31.0, 36.0]
  - (36.0, 42.0]
  - (42.0, 48.0]
  - (48.0, 54.0]
  - (54.0, 59.0]
  - (59.0, 65.0)
  - (65.0, 71.0]
  - (71.0, 76.0]
- Analyse des prix des propriétés (10 segments)
- Étude des corrélations entre l'âge des clients et les prix

### 4. 📉 Visualisation des Données
Création de visualisations pour répondre aux questions suivantes :
- Satisfaction moyenne des transactions par pays et par État
- Chiffre d'affaires mensuel
- Distribution des ventes d'appartements par État
- Répartition démographique des clients
- Ventes annuelles par type de bâtiment

## 💻 Technologies Utilisées
- Python
- Pandas
- Matplotlib/Seaborn (pour les visualisations)

## 🚀 Comment Utiliser
1. **Cloner le dépôt**
   ```bash
   git clone [URL-du-depot]
   cd [nom-du-depot]
   ```

2. **Installer les dépendances requises**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Lancer Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

4. **Ouvrir le notebook**
   - Naviguer jusqu'au fichier `Projet_marche_immobilier.ipynb`
   - Exécuter les cellules dans l'ordre pour reproduire l'analyse

## 📂 Structure des Données
Le projet utilise deux ensembles de données principaux :
- Table des propriétés
- Table des clients
qui sont fusionnés via la colonne `customer_id`

## 📊 Résultats
Les résultats de l'analyse sont disponibles directement dans le notebook et incluent :
- Statistiques descriptives complètes
- Visualisations des tendances clés
- Insights sur le marché immobilier

## 🔧 Prérequis
- Python 3.x
- Jupyter Notebook
- Les bibliothèques listées dans requirements.txt

## 📝 Note
L'ensemble de l'analyse est contenu dans un seul notebook Jupyter (`Projet_marche_immobilier.ipynb`) qui suit une structure séquentielle correspondant aux quatre parties principales du projet.

## 📫 Contact
Pour toute question ou suggestion, n'hésitez pas à ouvrir une issue sur le dépôt.
