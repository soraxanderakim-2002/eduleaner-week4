# eduleaner-week4
Semaine 4 : Intégration Cloud &amp; Construction Finale  Défi : Créez une application d’IA en utilisant AWS Bedrock, AWS Lambda et API Gateway, puis hébergez-la sur AWS Amplify + S3.


Bienvenue dans ce projet réalisé dans le cadre du Défi Semaine 4 : Intégration Cloud & Construction Finale.

L’objectif était de concevoir une application web capable de générer automatiquement des haïkus en utilisant l’IA Claude 3 Haiku via AWS Bedrock, avec un backend Lambda + API Gateway, et de déployer l’ensemble sur le cloud avec AWS Amplify + S3.

⚡ Fonctionnalités

Interface web simple avec un champ de saisie pour écrire un prompt.

Backend Lambda qui interroge le modèle Claude 3 Haiku.

Réponses renvoyées au front-end et affichées en temps réel.

Déploiement complet sur AWS pour un accès public.

🔧 Difficultés rencontrées

Configuration CORS pour que le front-end communique correctement avec l’API.

Permissions IAM pour permettre à Lambda d’invoquer Bedrock.

Déploiement sur Amplify + S3 et gestion des buckets/public access.

Erreurs 404 ou retour de haïkus par défaut dans certains cas.

💭 Malgré ces challenges, l’application fonctionne partiellement et reste un bon apprentissage de l’intégration Cloud + IA.

🌐 Lien de l’application

    https://main.dszmzvnenun7e.amplifyapp.com/
