# SpringBootMongoCRUD - Restful CRUD API

# Description
SpringBootMongoCRUD est une application de démonstration utilisant Spring Boot pour créer une API RESTful qui effectue des opérations CRUD sur une base de données MongoDB. Ce projet est conçu pour être simple à déployer à l'aide de Docker et Docker Compose, permettant ainsi une installation facile et rapide dans n'importe quel environnement.

#Fonctionnalités
Création (Create) : Ajouter des objets dans la base de données MongoDB.

Lecture (Read) : Lire des objets à partir de la base de données.

Mise à jour (Update) : Mettre à jour les objets existants dans la base de données.

Suppression (Delete) : Supprimer des objets de la base de données.

#Prérequis
Java 11 ou version supérieure

Maven

Docker

Docker Compose

#Installation
Cloner le dépôt
bash
Copier
git clone https://github.com/pMenye/SpringBootMongoCRUD.git
cd SpringBootMongoCRUD
Déploiement via Docker Compose
Créez et démarrez les services avec Docker Compose :

# bash
Copier
docker-compose up --build
Cela démarrera l'application Spring Boot et une instance de MongoDB dans des conteneurs Docker.

Pour arrêter les services, exécutez :
# bash
Copier
docker-compose down
Exécuter l'application localement avec Maven
Si tu souhaites exécuter l'application localement sans Docker, tu peux utiliser Maven :

Assure-toi d'avoir installé Maven sur ta machine.

Lance l'application Spring Boot avec la commande suivante :

bash
Copier
mvn spring-boot:run
L'application sera accessible sur http://localhost:8080.

# Base de données
MongoDB sera automatiquement configuré par le projet. Les données seront stockées dans une base de données appelée crud_db (tu peux la personnaliser dans les fichiers de configuration si nécessaire).

## Run Spring Boot application
```
mvn spring-boot:run
```

# Contributions
Si tu souhaites contribuer à ce projet, tu peux créer une pull request ou ouvrir un issue. Toute contribution est la bienvenue !

# Fork ce projet.

Crée une branche pour ta fonctionnalité ou correction : git checkout -b feature/ma-fonctionnalite.

Fais tes modifications, puis commit-les : git commit -am 'Ajout de ma fonctionnalité'.

Pousse ta branche sur ton dépôt : git push origin feature/ma-fonctionnalite.

Ouvre une pull request pour examiner les changements.
