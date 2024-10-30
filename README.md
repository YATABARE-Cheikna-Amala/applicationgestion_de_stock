

# PROJET BIG DATA ET CLOUD COMPUTING
# CREATION  D’UNE BASE DE DONNÉES IMMOBILIÈRE POUR LA SOCIETE IMMO LAPLACE 
Projet réalisé par **Fallou NGOM** , **Cheikna Amala YATABARE** , **Cherif Ousseynou DIOP** , **Mamadou Lamine NDAO**, **Papa Abdourahmane CISSE**

## Objectif du Projet  
Le but de ce projet est de créer une base de données immobilière en intégrant des données publiques françaises provenant de plusieurs sources, telles que le fichier des demandes de valeurs foncières, le référentiel géographique des régions, et les données de recensement de l’INSEE. Ces fichiers, accessibles librement sur différents sites gouvernementaux, sont volumineux et comportent de nombreux champs. Un choix précis des données à inclure a été effectué (consultez le dossier « données brutes » pour les fichiers sources et le dictionnaire des données pour la liste des colonnes intégrées dans la base).
Les notes de présentation jointes à ce projet visent à :
-	détailler le processus de création de la base en présentant les données sélectionnées dans le dictionnaire et en illustrant leurs interconnexions et organisation dans le schéma relationnel ;
-	expliquer les outils et techniques utilisés pour l’implémentation, incluant la vérification de la qualité des données, leur formatage et leur importation dans la base ; 
-	exposer les résultats des requêtes SQL et les questions auxquelles elles répondent, tout en rappelant les principes qui ont guidé la création de ces requêtes dans MySQL.
-	
## Structure des dossiers et fichiers
* **Dossiers :**
- **connection à la base de donnée RDS :** méthologie de connection à la base de donnée
  - **donnees :** fichiers sources  (.xlsx)
  - **donnees traitées :** fichiers prêts à être importés dans la base (.csv)
  - **requetes SQL :** scripts SQL pour interroger la base
- **site web de l’entreprise :** site gerer par la base de données.

* **Fichiers :**
	- **creation_table.sql :** script de création de la base, tables et clés
	- **schemas_relationnel_normalise_modifie.mwb :** schéma relationnel MySQL
	- **dictionnaire des _donnees_Laplace_Immo :** dictionnaire des données de la base
	- **resultats_requetes.xlsx :** résultats des requêtes sur la base
    	- **Résultat des Requetes.pdf :** présentation du projet
    	- **Modelisation projet base de donnée.pdf :** description des tables et des resultats des requetes.
        - **Laplace.png :** photo du logo de l'entreprise.
        -  **Schemas_relationnel_normalise_modifie.mwb :** Schemas relationnel normalisé modifié 
     	
## Compétences développées
* Maintenir un catalogue de données
* Concevoir le schéma d’une base de données
* Créer et structurer des tables dans une base de données
* Charger des données dans la base
* Construire des requêtes SQL pour répondre à des besoins métier

## Technologies & Logicielsutilisé
* Excel 
* MySQL / MySQL Workbench / adminer.php
* HTML/ CSS/ JavaScript
