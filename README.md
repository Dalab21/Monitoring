# Monitoring de modeles Machine Learning avec ARIZE, MLFLOW et SuperWize

Dans ce workshop, je ferai des exemples de monitoring des modèles de machine learning avec MLflow, Arize et SuperWize, ainsi que l'affichage avec ngrok. 
Quelques informations utiles sur ces outils:
1.	MLflow :
MLflow est une plateforme open source de gestion du cycle de vie des modèles machine learning. Elle prend en charge l'expérimentation, le suivi des paramètres, la gestion des modèles et le déploiement.
Pour monitorer les modèles MLflow, il est possible d’utiliser son module de suivi (tracking) qui enregistre les métriques, les paramètres et les artefacts associés à chaque exécution.
2.	Arize :
Arize AI est une plateforme de monitoring de modèle qui permet de suivre la performance des modèles en production. Elle offre des fonctionnalités telles que le suivi des dégradations de performance, la détection des anomalies et l'analyse des contributions de fonctionnalités.
Pour intégrer Arize avec MLflow, il faut généralement ajouter des appels à l'API d'Arize dans le code de votre projet ( MLflow pour enregistrer les métriques et les prédictions).
3.	SuperWize :
SuperWize est une plateforme de gestion de modèle ML qui facilite le déploiement, le suivi et la gestion des modèles en production.
Pour utiliser SuperWize avec MLflow, il faut intégrer les fonctionnalités de SuperWize dans le pipeline de déploiement.
4.	Ngrok :
Ngrok est un outil permettant de créer des tunnels sécurisés vers des applications locales. Il est souvent utilisé pour exposer des services locaux à Internet.
Ngrok est utilisé pour exposer l'interface utilisateur ou les API web d’applications MLflow, Arize, ou SuperWize afin de les rendre accessibles depuis l'extérieur.

Pour intégrer ces outils, il faut consulter la documentation spécifique de chacun d'eux et suivre les instructions fournies. 

