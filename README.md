# Projet : Pipeline d'Acquisition de Données (KDD)

## Objectifs du TP
L'objectif est de construire un pipeline capable d'extraire, de transformer et d'unifier des données depuis plusieurs sources :
- Fichiers locaux (CSV).
- Bases de données relationnelles (MySQL).
- Web Scraping et APIs (Données non structurées et JSON).

## Bibliothèques utilisées
Pour exécuter ce code, vous aurez besoin des bibliothèques suivantes :
- `pandas` : Pour la manipulation et l'analyse des données.
- `sqlalchemy` & `pymysql` : Pour la connexion à la base de données MySQL.
- `requests` : Pour l'appel aux APIs.
- `beautifulsoup4` : Pour le scraping des pages web.

## Description des sources collectées
1. **CSV (Student Performance)** : Données sur les performances des étudiants.
2. **SQL (MySQL)** : Extraction des étudiants ayant une note G3 > 15.
3. **API & Web Scraping** : Collecte de données complémentaires (posts API et titres de livres).