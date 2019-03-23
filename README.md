# grand_debat_hackathon

Objectif de la journée : mettre en place une Web App pour donner accès aux contributions de manière large et simple. Ajout couche de Machine Learning 

Organisation du repo: 
Les 4 notebooks remplissent exactement les mêmes fonctions, mais sont dédiés à des bases de question différentes :
- démocratie et citoyenneté [notebook à lire de manière prioritaire car le plus commenté]
- fiscalité et dépenses publiques
- transition écologique
- organisation de l'Etat et des services publics

Rôle des notebooks:
- ouvrir le fichier csv de la base de question
- éclater le fichier en format : user info | question | réponse
- ajouter une couche  simple de machine learning, avec du sentiment analysis (utilisant Textblob-fr), à améliorer
- associer les codes postaux à des villes pour permettre une navigation par ville sur la web app
- préparer les fichiers au format d'ingestion nécessaire à Elastic

