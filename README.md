# Portfolio Data Science de Jonathan Derou Bernal



<b>Projet 1 : Estimateur du prix d'une maison<\b><\br>
Il s'agit de créer un pipeline d'analyse qui montrera l'essentiel du travail d'un analyste de donnée necessaire à la création d'un éstimateur du prix d'une maison en fonction de variables structurelles tel que le nombre de pièces, leur surfaces, le nombre d'étages, etc... 

Le jeu de donnée que nous utilisons est appellé [House Sales In King County, USA](https://www.kaggle.com/harlfoxem/housesalesprediction) il est issu de données réelles provenant de la vente de propriétés dans le compté de King, aux Etats Unis.

Les étapes réalisés sont les suivantes:

1. Importer les données depuis une URL
2. Wrangling des données
3. Analyse exploratoire des données E.D.A.
4. Création d'un modèle
5. Identification des meilleurs prédicteurs pour la prédiction du prix
6. Optimisation du modèle

[Lien du projet : estimateur du prix d'une maison](https://eu-gb.dataplatform.cloud.ibm.com/analytics/notebooks/v2/0f94a687-5dc6-4f02-a780-156551a81883/view?access_token=2aa872155574b7a31ac7f25f12949c495788e7b3ec437e38ddf025969b74250e)   

<b>Projet 2 : Sentiment analysis - transfert learning de BERT<\b><\br>
Ici on va ré-entrainer le modèle BERT à reconnaitre 6 émotions labelisée sur le dataset [Smile emotion dataset final](https://figshare.com/articles/dataset/smile_annotations_final_csv/3187909). Ce dataset se compose de 3085 tweet en anglais.

Les étapes réalisés sont les suivantes:

1.E.D.A
2.Création des datasets stratifiés (Train, Val, Test)
3.Encodage des données et Tokenisation
4.Import et Tuning du modèle bert-base-uncased
5.Création d'un chargeur de données
6.Tuning de l'optimiser et du plannificateur
7.Définition des métriques de performance
8.Transfert learning
9.Déploiement/mise en production 

[Lien du notebook : analyse du sentiment par réenforcement de transformers bi-directionels profonds](https://eu-gb.dataplatform.cloud.ibm.com/analytics/notebooks/v2/5fe31780-ee9f-4f7e-9bca-1fbb2c1353c2/view?access_token=d064a0a40784e165d67f53db87a8bce243ee55a33d3fdbdddd97acaba9730197) 
