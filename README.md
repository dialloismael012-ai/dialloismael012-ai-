# Ismael DIALLO - Data Analyst / Engineer

Actuellement **Data Analyst en alternance au sein du Groupe Madrigall**, je consolide mon expertise métier et analytique avant d'entamer un **Mastère en Intelligence Artificielle & Big Data**. Passionné par la donnée sous toutes ses formes, j'aime concevoir des architectures robustes et transformer des données brutes en informations stratégiques.

**Me contacter :** www.linkedin.com/in/ismael-diallo-b35a2b27a | dialloismael012@gmail.com

---
Parcours & Ambition

**Data Analyst en alternance chez Groupe Madrigall**
  *  * Analyse de données, automatisation de reportings et accompagnement des prises de décision métier.
    
**À venir : Mastère Big Data & IA - Sup de Vinci**
  *  * Objectif : Développer une expertise pointue en ingénierie des données, Machine Learning et déploiement d'architectures Big Data.

## Ma Stack Technologique

*   **Langages :** Python, SQL, R, Excel, BI
*   **Bases de données :** PostgreSQL
*   **Orchestration & Traitement :** Apache Airflow, Pandas, numpy, Sqlalchemy
*   *(Note: AWS, Docker, Git, etc.)*

---

## Projets Data

### 1. Pipeline ETL Automatisé : Du CSV au Tableau de Bord (Club Med)

L'objectif : Automatiser le flux de traitement quotidien des données touristiques brutes pour alimenter un tableau de bord d'aide à la décision.

L'architecture :
![Architecture du Pipeline ETL](https://github.com/user-attachments/assets/dea5b37a-2ba6-4d8a-bce0-3f0b6cb23a02)

Outils utilisés : Apache Airflow, Python (Pandas), PostgreSQL, Excel.

Mon rôle et mes réalisations :
*   **Orchestration :** Configuration d'**Airflow** pour planifier et déclencher automatiquement le pipeline tous les jours à 17h50.
*   **Extraction & Transformation :** Récupération du fichier source `N_BASE_tourisme.csv` et script de nettoyage en **Python/Pandas**.
*   **Chargement :** Modélisation et insertion des données propres dans une base **PostgreSQL** (base `club_med`, table `club_med_club`).
*   **Visualisation :** Connexion de la base de données à **Excel** pour automatiser la mise à jour du tableau de bord final.

Le défi technique surmonté :
Le traitement des données brutes issues d'exports SAP. L'export initial nécessitait une standardisation rigoureuse avant intégration. J'ai utilisé Pandas pour automatiser le nettoyage des chaînes de caractères (suppression des espaces superflus avec `strip()`, harmonisation de la casse en minuscules) et fiabiliser l'encodage (UTF-8), garantissant ainsi un chargement sans erreur dans PostgreSQL.

**🔗 Voir le code :** [Lien vers ton dépôt contenant les scripts]

---
*Portfolio mis à jour en 2026*
