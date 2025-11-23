# 🐍 Python Tips – Guide personnel

Bienvenue dans **`python_tips`**, mon carnet Python regroupant :

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

### 📘 EDA (Exploratory Data Analysis) — Analyses exploratoires

* EDA using basic functions : `head()`, `info()`, `shape`, `describe()`
* [Annotated follow-along guide — EDA using basic data functions](./Annotated%20follow-along%20guide_EDA%20using%20basic%20data%20functions%20with%20Python.pdf)
  
* Discover what is in your dataset : analyse complète, transformations, visualisations, insights
* [Exemplar — Discover what is in your dataset](./Exemplar_Discover%20what%20is%20in%20your%20dataset.pdf)

### 🕒 Datetime — Manipulation temporelle

* Datetime manipulation : codes `strftime`, parsing, conversions
* [Reference guide — Datetime manipulation](./Reference%20guide_Datetime%20manipulation.pdf)
  
* Date string manipulations : création de colonnes temporelles (week, month, quarter), regroupements, formats 
* [Annotated follow-along guide — Date string manipulations](./Annotated%20follow-along%20guide_Date%20string%20manipulations%20with%20Python.pdf)

### 🧪 Découverte d’un dataset

* *Python functions for dataset discovery* : résumé des fonctions clés (`head`, `info`, `describe`, `shape`)
* [Reference guide — Python functions for the discovery of a dataset](./Reference%20guide_Python%20functions%20for%20the%20discovery%20of%20a%20dataset.pdf)

### 📥 Importation

* *Import datasets with Python* : CSV, URLs, bases de données, BigQuery workflows
* [Reference guide — Import datasets with Python](./Reference%20guide_Import%20datasets%20with%20Python.pdf)

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
