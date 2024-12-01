# Rapport Power BI : Consommation mondiale d'énergie

## **APERÇU**

L'objectif principal de ce projet est d'analyser et de visualiser les tendances énergétiques de différents pays sur différentes années en utilisant Power BI. Pour ce faire, un **jeu de données Kaggle** a été importé dans un notebook Jupyter à l'aide de Pandas. Le fichier CSV a été lu dans un DataFrame Pandas pour être traité.  
L'analyse et les visualisations offrent une vue claire des types d'énergie les plus consommés par pays et par année.  
Le rapport Power BI est divisé en **quatre parties** :
1. **Vue d'ensemble** : Génération d'électricité, consommation d'énergie, consommation par habitant et part de chaque source d'énergie dans différents pays et années.  
2. **Tendances des combustibles fossiles** : Analyse des données liées aux énergies fossiles.  
3. **Tendances des énergies renouvelables** : Analyse des énergies renouvelables.  
4. **Comparaison fossiles vs renouvelables** : Visualisation des tendances entre les combustibles fossiles et les énergies renouvelables.  

Cette comparaison met en lumière si les pays adoptent progressivement les énergies renouvelables pour réduire leur dépendance aux énergies fossiles, principales responsables du réchauffement climatique et des catastrophes naturelles.

---

## **NETTOYAGE DES DONNÉES**

Des opérations de nettoyage ont été réalisées, notamment :  
- Suppression des colonnes inutiles,  
- Remplacement des valeurs nulles par des fonctions d'agrégation,  
- Utilisation des méthodes BFILL et FFILL.  

Le jeu de données initial comprenait **17 432 lignes et 122 colonnes**. Il a été réduit en sélectionnant uniquement des pays populaires et les années de **2000 à 2020**, aboutissant à un dataset final de **415 lignes et 44 colonnes**.  

Le dataset a été divisé en cinq parties :  
1. **Informations de base** : Pays, année, population, PIB.  
2. **Production et consommation d'électricité** : Électricité par habitant et part par source d'énergie.  

Dans Power BI, des **transformations de données** ont été appliquées, telles que le dépivotement de colonnes et la création de nouvelles mesures pour les visualisations.

---

## **COMBUSTIBLES FOSSILES**

Dans cette section, seules les données sur les combustibles fossiles ont été analysées. Ces combustibles incluent le charbon, le pétrole, le gaz naturel et l'énergie nucléaire. Bien que l'énergie nucléaire soit recyclable, elle est incluse ici car sa production repose sur la **fission des atomes d'uranium**, un processus nécessitant beaucoup d'énergie fossile (extraction et raffinage du minerai d'uranium).  



## **ÉNERGIES RENOUVELABLES**

Cette section met en lumière les énergies renouvelables telles que le solaire, l'éolien, les biocarburants et l'hydroélectricité.  
Les données analysées incluent :  
- Génération et consommation d'électricité,  
- Part de l'électricité renouvelable par pays,  
- Consommation par habitant.  

Différents graphiques, comme des diagrammes en barres, en secteurs, des colonnes empilées et des cartes, ont été utilisés. Ces visualisations permettent d'identifier si la production et la part des énergies renouvelables augmentent au fil des années.



## **COMBUSTIBLES FOSSILES VS ÉNERGIES RENOUVELABLES**

Cette section compare les données sur les combustibles fossiles et les énergies renouvelables, notamment :  
- Production d'électricité,  
- Consommation,  
- Consommation par habitant,  
- Part des différentes sources d'énergie.  

Cette comparaison offre une **vue d'ensemble des tendances énergétiques mondiales** et permet d'évaluer si les pays effectuent une transition significative des énergies fossiles vers les renouvelables pour un avenir plus durable.

