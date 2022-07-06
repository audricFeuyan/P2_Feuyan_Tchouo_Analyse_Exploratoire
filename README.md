# Analyse exploratoire univariée/bivariée

Le notebook joint à ce dépôt est celui de l'analyse exploratoire univariée et bivariée d'un jeu de données sur des arbres dans Paris. L'objectif de l'analyse est la préparation des opérations d'entretien des arbres dans la ville. Il sera donc question des découvrir et comprendre les données afin de pouvoir founir des recommandations préliminaires.

## Outils d'analyse

- Jupyter notebook [jupyter](https://jupyter.org/) 
- Python 3 [python](https://www.python.org/)


## Processus d'analyse

- Nettoyage des données
- Analyse univariée
- Analyse bivariée
- Synthèse et recommandations

## Quelques résultats

- Le jeu de données contient 200137 observations suivant 18 caractéristiques;
- On y distingues des variables qualitatives nominales, qualitatives ordinales et quantitatives discrètes;
- Le record de données manquantes est détenu par la variable "numero" avec 100% de données manquantes;
- Le jeu de données contient globalement 18,5% de données manquantes;
- On ne distingue pas à proprement parler de doublons;
- La plus part des arbres sont répartis entre les 12e, 13e, 14e, 15e, 16e, 17e, 18e, 19e et 20e arrondissements;
- Ils sont pour la plus part dans les cimétières, les jardins ou en alignement;
- Certains arbres possèdent des hauteurs et des circonferences de 0; certainement il s'agit de jeune arbres et la dimension étant inférieure à l'unité a été ramenée à 0;
- Les arbres dont la hauteur est supérieure à 30 mètres devraient être d'avantage analysés dans une perspective de données abérrantes, également ceux d'une circonférence supérieure à 1000 cm;
- La plus part des arbres sont soit des espèces x hispanica, japonica, tomentosa ou hippocastanum; soit des genres Platanus, Aesculus, Tilia, Acer ou Sophora;
- La moyenne des hauteurs est de 7.93m et celle des circonférences de 74.80cm;
- La taille 0 et la circonférence 0 représentent le groupe d'arbres avec le plus d'effectif, preuve que la plus part des arbres sont de jeunes arbres;
- 50% des arbres ont moins de 8 mètres de hauteur et moins de 70cm de circonférence;
- Les valeurs des hauteurs présentent un taux de dispersion de 75.50% tandis que les valeurs des circonférences présentent un taux de dispersion de 80.56%;
- La distribution des valeurs des hauteurs et des circonférences sont asymétriques et s'étalent vers la droite;
- Les arbres les plus hauts sont en alignement (domanialité) et répartis entre le 6ème et le 8ème arrondissement, tandis que les plus courts sont dans les cimétières;
- Les arbres les plus gros (circonférence) sont dans les DAC (domanialité) et dans le 8ème arrondissement, tandis que les plus minces sont dans les DASES (domanialité) et en HAUTS-DE-SEINE.


## License
[MIT](https://choosealicense.com/licenses/mit/)
