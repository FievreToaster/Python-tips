# 🐍 Python Tips – Guide d’apprentissage personnel

Bienvenue dans **`python_tips`**, mon carnet d’apprentissage Python regroupant :

* mes notes de formation (Google Data Analytics & Advanced Data Analytics),
* mes exercices,
* mes astuces pratiques,
* et mes mini-projets Data.

Ce dépôt est un **aide-mémoire structuré**, un **laboratoire personnel**, et une **boîte à outils** pour progresser en Python.

---

# 📚 Table des matières

1. [Les bases de Python](#1️⃣-les-bases-de-python)
2. [Les types de données](#2️⃣-les-types-de-données)
3. [Les fonctions utiles](#3️⃣-les-fonctions-utiles)
4. [Programmation orientée objet (POO)](#4️⃣-programmation-orientée-objet-poo)
5. [Python pour la Data Analytics](#5️⃣-python-pour-la-data-analytics)
6. [Exemples pratiques](#6️⃣-exemples-pratiques)
7. [Ressources utiles](#7️⃣-ressources-utiles)

---

# 1️⃣ Les bases de Python

📄 **[01_bases_python.md](01_bases_python.md)**

* Syntaxe de base
* Variables, opérateurs, indentation
* Commentaires & conventions (PEP 8)
* Entrées / sorties (`input`, `print`)
* Expressions & assignations

---

# 2️⃣ Les types de données

📄 **[02_types_de_donnees.md](02_types_de_donnees.md)**

* Types natifs : `int`, `float`, `str`, `bool`
* Collections : `list`, `tuple`, `set`, `dict`
* Conversion entre types (`int()`, `str()`, ...)
* Mutabilité & immutabilité
* Fonctions utiles : `type()`, `isinstance()`

---

# 3️⃣ Les fonctions utiles

📄 **[03_fonctions_utiles.md](03_fonctions_utiles.md)**

* Fonctions fondamentales : `print()`, `len()`, `sum()`
* Fonctions logiques : `any()`, `all()`
* Fonctions d’itération : `range()`, `enumerate()`, `zip()`, `map()`
* Fonctions de conversion : `int()`, `float()`, `list()`
* Fonctions système : `dir()`, `help()`

---

# 4️⃣ Programmation orientée objet (POO)

📄 **[04_la_poo.md](04_la_poo.md)**

* Définir une classe
* Constructeur `__init__`
* Méthodes & attributs
* Encapsulation
* Héritage & polymorphisme
* Méthodes spéciales : `__str__`, `__repr__`
* Exemple complet : `Voiture`, `CompteBancaire`

---

# 5️⃣ Python pour la Data Analytics

📄 **[05_python_pour_la_data_analytics.md](05_python_pour_la_data_analytics.md)**

* Manipulation de données avec **Pandas**
* Importation : CSV, Excel, JSON, API
* Nettoyage & préparation (wrangling)
* Analyse statistique de base
* Visualisation : **Matplotlib**, **Seaborn**
* GroupBy, merge, pivot tables
* Cas pratiques :

  * Analyse de churn
  * Analyse financière
  * Séries temporelles simples

---

# 6️⃣ Exemples pratiques

📄 **[06_exemples_pratiques.md](06_exemples_pratiques.md)**

* Mini-projets Python :

  * Nettoyage d’un dataset "sale"
  * Création d’un dashboard Matplotlib
  * Simulation portefeuille financier
  * Classification simple
  * Régression linéaire & évaluation

---

# 7️⃣ Ressources utiles

📄 **[07_ressources_utiles.md](07_ressources_utiles.md)**

### 📘 Documentation officielle

* Python : [https://docs.python.org/3/](https://docs.python.org/3/)
* Pandas : [https://pandas.pydata.org/docs/](https://pandas.pydata.org/docs/)

### 🧠 Sites d’exercices

* HackerRank (Python)
* LeetCode (algos & data)

### 🎓 Cours recommandés

* Google (Data Analytics & Advanced Analytics)
* University of Michigan (Python Specialization)
* Andrew Ng (ML)

### 🛠️ Outils pratiques

* PEP 8 style guide
* Jupyter Notebook
* VSCode + extensions Python

---

# 🎯 Objectif du dépôt

> Construire une base solide pour progresser en **Python**, **Data Analytics**, et **Machine Learning**, tout en documentant chaque étape de mon apprentissage.

Si tu veux contribuer, proposer une amélioration ou discuter de Python → **Pull Request ou issue bienvenue !** 🚀

---

## 🗂️ Documentation PDF (Version Professionnelle)

Cette section regroupe l’ensemble des guides PDF présents dans le dépôt, organisés comme une documentation technique de référence.

### 📁 Structure

* **EDA (Exploratory Data Analysis)**
* **Datetime & Manipulation temporelle**
* **Exploration d’un dataset**
* **Importation de données**

### 📘 EDA — Analyses exploratoires

* *Annotated follow-along guide: EDA using basic data functions with Python* — Guide commenté pas-à-pas pour découvrir un dataset, utiliser `head()`, `info()`, `shape`, faire des regroupements et graphiques.
* *Exemplar: Discover what is in your dataset* — Exemple complet d’analyse sur un dataset Unicorns : exploration, transformation, visualisation, insights business.

### 🕒 Datetime — Manipulation des dates

* *Reference guide: Datetime manipulation* — Tableau complet des codes `strftime`, conversions, parsing, `timestamp`, propriétés Pandas (`dt.year`, `dt.month`, etc.).
* *Annotated follow-along: Date string manipulations with Python* — Création automatique de colonnes temporelles, regroupements hebdomadaires, trimestriels, graphiques et formats custom.

### 🧪 Découverte de dataset

* *Python functions for the discovery of a dataset* — Synthèse claire des fonctions EDA essentielles : `head()`, `info()`, `describe()`, `shape`.

### 📥 Importation & BigQuery

* *Reference guide: Import datasets with Python* — Importation CSV (`open()`, `read()`, `pd.read_csv()`), URLs, connexions base de données, workflows BigQuery (SQL, Jupyter dans BigQuery, extraction de tables publiques).

---

## 📑 Tableau récapitulatif des PDF

| Catégorie             | PDF                                    | Contenu principal                                                  |
| --------------------- | -------------------------------------- | ------------------------------------------------------------------ |
| **EDA**               | EDA using basic data functions         | Exploration initiale du dataset, opérations Pandas, visualisations |
| **EDA**               | Discover what is in your dataset       | Analyse complète Unicorns, insights, graphiques avancés            |
| **Datetime**          | Datetime manipulation                  | Codes datetime, conversions, parsing                               |
| **Datetime**          | Date string manipulations              | Colonnes temporelles, regroupements, formats, visualisation        |
| **Dataset discovery** | Python functions for dataset discovery | Fonctions EDA clés (`head`, `info`, `describe`, `shape`)           |
| **Importation**       | Import datasets with Python            | CSV, URL, BigQuery, connexions BD                                  |

---

## 🧭 Objectif de cette section

Créer une véritable **documentation interne** pour faciliter :

* la révision rapide,
* la maîtrise des bonnes pratiques Pandas,
* l’analyse plus efficace de tout nouveau dataset.

Toutes ces ressources s’intègrent parfaitement dans le workflow d’un Data Analyst professionnel.
