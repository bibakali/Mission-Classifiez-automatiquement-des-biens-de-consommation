# Mission-Classifiez-automatiquement-des-biens-de-consommation
Certification OpenClassrooms - Parcours data scientist - Mission n°6 - Classifiez automatiquement des biens de consommation

## Mission :

Je suis Data Scientist au sein de l’entreprise "Place de marché”, qui souhaite lancer une marketplace e-commerce. Sur cette place de marché anglophone, des vendeurs proposent des articles à des acheteurs en postant une photo et une description. Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs, et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit. Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche. 
Linda, Lead Data Scientist, me demande donc d'étudier la faisabilité d'un moteur de classification des articles en différentes catégories, à partir du texte (en anglais) et de l’image, avec un niveau de précision suffisant.

## Source :

[Les données](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+prétraitement+textes+images.zip)

## Axes d'orientations : 

- Réaliser, dans une première itération, une étude de faisabilité d'un moteur de classification d'articles, basé sur une image et une description, pour l'automatisation de l'attribution de la catégorie de l'article.
- Analyser les descriptions textuelles et les images des produits, au travers : 
    - Un prétraitement des données texte ou image suivant le cas ;
    - Une extraction de features ;
    - Une réduction en 2 dimensions, afin de projeter les produits sur un graphique 2D, sous la forme de points dont la couleur correspondra à la catégorie réelle ;
    - Analyse du graphique afin d’en déduire ou pas, à l’aide des descriptions ou des images, la faisabilité de regrouper automatiquement des produits de même catégorie ;
    - Réalisation d’une mesure pour confirmer ton analyse visuelle, en calculant la similarité entre les catégories réelles et les catégories issues d’une segmentation en clusters.
- Suivant cette approche, démontrer la faisabilité de regrouper automatiquement des produits de même catégorie 
- Extraire les features texte : 
     - Type “bag-of-words”, comptage simple de mots et Tf-idf ;
     - Une approche de type word/sentence embedding classique avec Word2Vec (ou Glove ou FastText) ;
     - Une approche de type word/sentence embedding avec BERT ;
     - Une approche de type word/sentence embedding avec USE (Universal Sentence Encoder). 
     
     
- Extraire les features image, il sera nécessaire de mettre en œuvre :
     - Un algorithme de type SIFT / ORB / SURF ;
     - Un algorithme de type CNN Transfer Learning.


## compétences : 
- Prétraiter des données image pour obtenir un jeu de données exploitable.
- Prétraiter des données texte pour obtenir un jeu de données exploitable.
- NLP, word2vec, doc2vec, BERT, USE
- Représenter graphiquement des données à grandes dimensions.
- Mettre en œuvre des techniques de réduction de dimension.
