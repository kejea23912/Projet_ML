# Analyse et Prédiction du Salaire Net Médian des Diplômés de Master en France

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13%2B-blue?style=flat-square&logo=python" alt="Python 3.13+"/>
  <img src="https://img.shields.io/badge/Source-data.gouv.fr-red?style=flat-square&logo=france" alt="data.gouv.fr"/>
  <img src="https://img.shields.io/badge/Package_Manager-uv-purple?style=flat-square" alt="uv"/>
  <img src="https://img.shields.io/badge/ML-scikit--learn-orange?style=flat-square&logo=scikit-learn" alt="scikit-learn"/>
  <img src="https://img.shields.io/badge/Status-Projet_en_cours-brightgreen?style=flat-square" alt="Status"/>
</p>


--- 

**Problématique:**

Dans quelle mesure le domaine académique et la localisation géographique d'une université permettent-ils d'expliquer et de prédire le salaire net médian des diplômés de Master ? 

## Présentation des Données

Les données utilisées sont issues de l'enquête nationale sur l'**[« Insertion professionnelle des diplômés de Master en universités et établissements assimilés »](https://www.data.gouv.fr/datasets/insertion-professionnelle-des-diplomes-de-master-en-universites-et-etablissements-assimil-0)**, produite par le Ministère de l'Enseignement Supérieur et de la Recherche (MESR) et mise à disposition sur la plateforme publique **data.gouv.fr**.

### Caractéristiques du dataset :
- **Source :** API Tabulaire Data.gouv.fr 
- **Unité d'observation :** Une promo de Master par établissement, domaine et discipline.
- **Variable Cible ($y$) :** `salaire_net_mensuel_median_des_emplois_a_temps_plein` (€/mois).
- **Variables Explicatives Principales ($X$) :**
  - `domaine` : Grand domaine de formation (Sciences, Droit-Économie, SHS, Lettres, etc.)
  - `discipline` : Spécialité détaillée du Master
  - `academie` / `region` : Implantation géographique de l'établissement
  - `taux_dinsertion` : Pourcentage de diplômés en emploi
  - `taux_demplois_cadre_ou_professions_intermediaires` : Qualité de l'insertion

## Présentation du Projet & État d'Avancement

Ce projet vise à analyser les facteurs déterminant l'insertion professionnelle et la rémunération des diplômés de Master en France, en s'appuyant sur les données ouvertes du ministère de l'Enseignement supérieur et de la Recherche.

Actuellement, nous avons réalisé la première phase majeure du projet : **l'Exploration et l'Analyse de la Qualité des Données (EDA)**. La phase de modélisation prédictive (Machine Learning) constitue la prochaine étape.


##  Stack Technique & Bibliothèques Utilisées

* **Manipulation de données :** `pandas`, `numpy`
* **Visualisation :** `matplotlib`, `seaborn`, `pypalettes`


---

##  Avancement des Travaux (Notebook `base.ipynb`)

 1. Nettoyage et Préparation des Données

 2. Principaux Constats de l'Analyse Exploratoire (EDA)

    * Analyse de la Qualité des Données & NaNs
 d'imputation ciblée pour éliminer les biais.




## Auteurs
* **Kenny Jean-elie**
* **Ndèye Fatou DIOP**
* **Grace Adjamagni**
