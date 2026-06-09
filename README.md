# 🚀 [Ismael DIALLO] - Data Analyst / Engineer

Passionné par la construction de pipelines de données robustes, l'automatisation et l'optimisation des flux de données. Je transforme des données brutes en informations exploitables pour la prise de décision.

📫 **Me contacter :** [www.linkedin.com/in/ismael-diallo-b35a2b27a] | [dialloismael012@gmail.com]

---

## 🛠️ Ma Stack Technologique

*   **Langages :** Python, SQL
*   **Bases de données :** PostgreSQL
*   **Orchestration & Traitement :** Apache Airflow, Pandas
*   *(Note: ajoute ici d'autres outils que tu connais comme AWS, Docker, Git, etc.)*

---

## 📂 Projets Data

### 1. Pipeline ETL Automatisé : Du CSV au Tableau de Bord (Club Med)

**🎯 L'objectif :** Automatiser le flux de traitement quotidien des données touristiques brutes pour alimenter un tableau de bord d'aide à la décision.

**🏗️ L'architecture :**
![<img width="1200" height="560" alt="pipeline_dark" src="https://github.com/user-attachments/assets/b9b7a90e-a1aa-4718-affb-32712a8d2bfc" />
](pipeline_dark.png)

**🔧 Outils utilisés :** Apache Airflow, Python (Pandas), PostgreSQL, Excel.

**👨‍💻 Mon rôle et mes réalisations :**
*   **Orchestration :** Configuration d'**Airflow** pour planifier et déclencher automatiquement le pipeline tous les jours à 17h50.
*   **Extraction & Transformation :** Récupération du fichier source `N_BASE_tourisme.csv` et script de nettoyage en **Python/Pandas**.
*   **Chargement :** Modélisation et insertion des données propres dans une base **PostgreSQL** (base `club_med`, table `club_med_club`).
*   **Visualisation :** Connexion de la base de données à **Excel** pour automatiser la mise à jour du tableau de bord final.

**🚧 Le défi technique surmonté :**
Le traitement des données brutes issues d'exports SAP. L'export initial nécessitait une standardisation rigoureuse avant intégration. J'ai utilisé Pandas pour automatiser le nettoyage des chaînes de caractères (suppression des espaces superflus avec `strip()`, harmonisation de la casse en minuscules) et fiabiliser l'encodage (UTF-8), garantissant ainsi un chargement sans erreur dans PostgreSQL.

**🔗 Voir le code :** [Lien vers ton dépôt contenant les scripts]

---
⭐️ *Portfolio mis à jour en 2026*
