### POWER BI
- Power BI est une plateforme d'analyse commerciale et de visualisation de données développée par ***Microsoft***. Elle permet de se connecter à différentes sources de données, de transformer les données brutes en informations exploitables, et de les présenter sous forme de rapports et tableaux de bord interactifs.

### Le work-flow de POWER BI
![image](https://github.com/user-attachments/assets/6531971d-7063-4101-be71-61ad92bc01ca)

### 1- POWER QUERY 
- Collecte des données : Importation de données de différentes sources (bases de données, fichiers Excel/CSV, services en ligne, API)
- Transformation des données : nettoyage et restructuration des données en mettant en avant la création de nouvelles colonnes (Feature engineering) en utilisant le ***langage M*** (Préparation de données ETL (Extract, Transform et Load)), ainsi que le filtrage pour assurer la qualité des données

### 2- Modélisation
- Cette étape repose sur la création de relations entre les tables (modèle en étoile ou en flocon) et élaboration de mesures et colonnes calculées avec le ***langage DAX*** (Data Analysis Expressions (effectuer des calculs statistiques sur les données ))
  
### 3- Analyse 
- Application d'analyses statistiques et mathématiques avancées pour tirer des descriptions précises du dataset et identification des tendances et corrélations significatives
  
### 4- Visualisation
- Conception de tableaux de bord interactifs avec différents types de graphiques pour faciliter la transformation des données brutes en informations exploitables pour les clients finaux. Ces visualisations permettent de communiquer efficacement les insights et d'aider à extraire des décisions rigoureuses.

### Le langage M 
![image](https://https://github.com/user-attachments/assets/9b2a97e3-e248-4bee-bf71-361bdaa7d694)


- Cette image illustre la création d'une nouvelle colonne en combinant Units Sold et Sale Price, ceci est très utile pour l'enrichissement de dataset *Montant vente = Sheet1[Units Sold]Sheet1[Sale Price]

### Le langage DAX
- ***Mesure 1 = MAX(Sheet1[Montant vente])*** cette requête nous retourne la valeur maximale de la colonne Montant vente
