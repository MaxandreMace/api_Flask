#  API  Flask
## Fonctionnalité:
- Intégration d'API : Flask API s'intègre parfaitement à la création d'API, vous permettant de profiter de fonctionnalités puissantes pour construire vos applications web.
- Développement Rapide : Flask API propose une interface simple et intuitive, ce qui vous permet de développer rapidement et de prototyper vos applications web.
- Gestion des Routes : Définissez des routes d'URL et mappez-les à des fonctions ou des vues spécifiques dans votre application.
- Moteur de Templates : Flask API dispose d'un moteur de templates flexible et facile à utiliser, vous permettant de créer des pages web dynamiques et interactives.
- Gestion des Requêtes : Gérez facilement les requêtes HTTP entrantes et accédez aux paramètres et aux données de la requête.
- Gestion des Sessions : Flask API propose une gestion intégrée des sessions, vous permettant de stocker et de récupérer des données spécifiques à l'utilisateur entre les requêtes.
- Intégration de Base de Données : Intégrez Flask API avec votre système de base de données préféré pour stocker et récupérer des données pour votre application.
- Sécurité : Flask API inclut des fonctionnalités pour gérer l'authentification, l'autorisation et se protéger contre les vulnérabilités Web courantes.
- Extensions : Étendez les fonctionnalités de Flask API avec une large gamme d'extensions développées par la communauté.
## Avantages et inconvéninets de l'api Flask:
| avantages | inconvéninets |
|-----:|---------------|
|Facile à apprendre et à utiliser|manquer de certaines fonctionnalités avancées.   |
|Grande communauté de développeurs|dispose pas de certaines fonctionnalités d'organisation des fichiers et des dossiers            |
|Flexibilité pour construire des API|Nécessité de gérer manuellement la sécurité           |
 ## Installation:
Pour installer Flask API, suivez ces étapes :

1) assurez-vous d'avoir Python 3.x installé sur votre système.
2) Créez un environnement virtuel pour votre projet (optionnel mais recommandé).
3) Activez l'environnement virtuel.
3) Exécutez la commande suivante pour installer l'API Flask :
```
pip install flask-api
```
## Exemple de fonctionnement de l'api
1) /: teste de l'api avec hello word
2) /val : retourne une valeur aléatoire  entre 0 et 100:
    - avant installer la bibliothèque random
    ```
    pip install random
    ```
    - utilise la méthode get et post:
    
      a) GET :est une méthode HTTP utilisée pour récupérer des données à partir d'un serveur. Lorsqu'un utilisateur accède à l'URL /val avec une requête GET, la fonction val() sera exécutée, et elle renverra une réponse contenant un nombre entier aléatoire entre 0 et 100.
      
      b) POST :est une méthode HTTP utilisée pour envoyer des données au serveur. Si un utilisateur envoie une requête POST à l'URL /val, la fonction val() sera également exécutée et renverra une réponse contenant un nombre entier aléatoire entre 0 et 100.
 3)/val?nb=n: retourne du code json contenant un tableau de nvaleurs entières aléatoires comprises en -1000 et +1000
  - librairie nécessaire : json
  ``` pip install jsonlib ```
  - module à importer de flask est: jsonify ``` from flask import jsonify ```
  4) /calc/add?n1=n&n2=m et /calc/prod?n1=n&n2  : permet de faire des addition et multiplication
  5) /img?num=3 : retourne une image
   - module nécesaire de flask send_file : ``` from flask import send_file ```
   - librairie nécesaire à installer et importer:
      - Image: ``` pip install Pillow``` ET importer image : ``` from PIL import Image```
      - IO : ```from io import BytesIO```

 
