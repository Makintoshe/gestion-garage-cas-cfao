## ABOUT GESTION DE GARAGE - CAS DE CFAO
Le projet gestion de garage de réparation pour automobile est un travail pratique qui s'inscrit dans le cadre du cours de conception des systèmes d'informations, réalisé par Ketsia Mulapi Tita & Laurel Muswamba Biakunyenga.

### Architecture 
    .
    ├── entites                # Représentation de la BD.
    │   ├── AutomobileE.java     # Le schema de la table Automobile ds la bd.
    │   ├── etcE.java             # Autres schema    │
    ├── service                # Les services relatifs à chaque Modèle.
    │   ├── AutomobileS.java   # Ensemble des services appliqués à un Autombile.
    │   ├── etcS.java                 │
    ├── Présentations Controlleurs           # Les services relatifs à chaque collection.
    │   ├── GUIReparationControlleur.java         # Ensemble des controlleurs GUI~SERVICE dédié à la réparation
    │   ├── GUIetcControlleur.java            
    ├── DAO                    # Couche D'accès aux données via des objets.
    │   ├── AutomobilesDAO.java  # Ce sont des fonctions de traitement de données pour les uatomobiles Entités~Services.
    │   ├── etcDAO.java
    ├── Présentation.GUI       # Ensemble des composants graphiques
    │   └── GUIPiece.java      # IHM pour la gestion des pièces 
    │   ├── GUIetc.java
    └── Autres présentations   # Autres package de présentations dédiés à des ressources images.

NOTA :
*	La base de données : ```GestionGarage/bdgaragerep.sql```  ou ```GestionGarage/bdgarage.sql.zip``` selon la convenance
*	Le chemin vers la BD : ```http://jdbc:mysql://localhost:3306/bdgaragerep```
*	Pour accéder au contenu de l'application entrer les informations de username et mot de passe respectivement : ```username : patrick, password:bashizi``` ou ```username:root,password: ``` le deuxième password est vide!!!

### TODO LIST

0. Mettre la base de données dans un serveur de données comme mysql~wamp
1. Ouvrir le projet à partir de Netbeans ou IntelliJ, etc.
2. Les librairies jar doivent être présentes