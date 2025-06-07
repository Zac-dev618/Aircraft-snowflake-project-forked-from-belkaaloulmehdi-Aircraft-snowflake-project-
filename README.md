# Projet Aircraft DB - Analyse SQL avec Snowflake

---

## Contexte

Ce projet a été réalisé dans le cadre de ma formation Data Analyst au bootcamp Jedha.  
Il consiste à analyser une base de données aéronautique via Snowflake, une plateforme cloud SQL performante et scalable.  

Le dataset est chargé via un script SQL complet qui crée les tables et insère les données.  
Mon travail est d’écrire des requêtes SQL pour répondre à plusieurs questions métier et extraire des insights pertinents.

---

## Énoncé du projet

À partir du script SQL fourni, qui crée la base de données `AIRCRAFT_DB` et ses tables principales (`aircraft`, `airlines`, `airports`, `flight_summary_data`, `individual_flights`), il s'agit de :

- Calculer le nombre de vols par modèle d’avion  
- Déterminer le nombre total de passagers par aéroport  
- Identifier l’année de meilleure performance en RPM par compagnie  
- Identifier l’année de meilleure performance en ASM par compagnie  
- Bonus : Trouver le top 5 des compagnies en RPM total  

---

## Contenu du repo

- `create_and_load_tables.sql` : Script complet pour créer toutes les tables et insérer les données  
- `analysis_queries.sql` : Toutes mes requêtes SQL, question par question, avec commentaires et explications  
- `/screenshots` : Captures d’écran des résultats obtenus dans Snowflake, illustrant chaque question traitée  
- `/results` : Exports CSV des résultats des requêtes pour chaque question, permettant une analyse approfondie

---

## Comment utiliser ce projet

1. **Créer la base et les tables**  
   Exécuter le script `create_and_load_tables.sql` dans Snowflake pour préparer la base de données.  

2. **Exécuter les requêtes d’analyse**  
   Copier-coller les requêtes du fichier `analysis_queries.sql` dans Snowflake pour obtenir les réponses aux questions du projet.  

3. **Consulter les résultats**  
   - Les fichiers CSV dans `/results` contiennent les données brutes exportées depuis Snowflake pour chaque question.  
   - Les captures d’écran dans `/screenshots` montrent les résultats directement dans l’interface Snowflake, attestant du bon fonctionnement des requêtes.

---

## Remarques

- Toutes les données sont chargées via le script SQL, il n’y a pas de fichiers CSV sources externes.  
- Le projet met en avant la capacité à manipuler de grandes bases de données dans un environnement cloud SQL (Snowflake), à écrire des requêtes complexes et à extraire des insights pertinents.  
- Le repo est organisé pour faciliter la compréhension, la reproduction et la validation du travail.

---

## Contact

N’hésitez pas à me contacter pour toute question ou collaboration !

---

*Fin du README*
