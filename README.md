# Implémentez un modèle de scoring
Mettre en œuvre un outil de “scoring crédit” pour calculer la probabilité qu’un client rembourse son crédit, puis classifie la demande en crédit accordé ou refusé
# Dashboard 
# [Web App from Heroku & Sharing Streamlit](https://dshboard-streamlit.herokuapp.com/)
L'application contient les fonctionnalités suivantes :  
 1-Permettre de visualiser le score et l’interprétation de ce score pour chaque client pour une personne non experte en data science.  
 2-Permettre de visualiser des informations descriptives relatives à un client (via un système de filtre).  
 3-Permettre de comparer les informations descriptives relatives à un client à l’ensemble des clients ou à un groupe de clients similaires.   
 
# Les données :  
Voici [les données](https://www.kaggle.com/c/home-credit-default-risk/data) dont vous aurez besoin pour réaliser le dashboard.  
Pour plus de simplicité, vous pouvez les télécharger à [cette adresse](https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Impl%C3%A9menter+un+mod%C3%A8le+de+scoring/Projet+Mise+en+prod+-+home-credit-default-risk.zip).

# Livrables 
Le dashboard interactif répondant aux spécifications ci-dessus et l’API de prédiction du score.  
Le dépôt contient :  
  -Le code de la modélisation (du prétraitement à la prédiction).   
  -Le code générant le dashboard.  
  -Le code permettant de déployer le modèle sous forme d'API.  
  -Une note méthodologique décrivant :  
  -La méthodologie d'entraînement du modèle.  
  -La fonction coût métier, l'algorithme d'optimisation et la métrique d'évaluation.  
  -L’interprétabilité globale et locale du modèle.  
  -Un support de présentation détaillant le travail réalisé.  

# Compétences évaluées :  
* Présenter son travail de modélisation à l'oral
* Déployer un modèle via une API dans le Web
* Utiliser un logiciel de version de code pour assurer l’intégration du modèle
* Rédiger une note méthodologique afin de communiquer sa démarche de modélisation
* Réaliser un dashboard pour présenter son travail de modélisation  

# Heroku Git  
Installation de Heroku Command Line Interface (CLI) [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) 

# Mise à jour des modifications  
    $ git add .  
    $ git commit -am "make it better"  
    $ git push heroku master  

# Références :  
[How to Deploy Data Science Web App to Heroku | Streamlit](https://www.youtube.com/watch?v=zK4Ch6e1zq8)  
[Streamlit cheat sheet](https://share.streamlit.io/daniellewisdl/streamlit-cheat-sheet/app.py)  
[Gérez du code avec Git et GitHub](https://openclassrooms.com/fr/courses/7162856-gerez-du-code-avec-git-et-github)  
[Le kernel LightGBM with Simple Features](https://www.kaggle.com/jsaguiar/lightgbm-with-simple-features)



    

  
