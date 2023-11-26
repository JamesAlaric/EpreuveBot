# EpreuveBot
API to provide Cameroonian students with past baccalaureate exam papers. This API is used by the Telegram bot @EpreuveBot.
# Objectives
The main objective of this API is to facilitate Cameroonian students' access to previous baccalaureate exams. 

Specific objectives include:
Create a robust and secure API to manage requests for past exam papers.
Store and organize past exam papers in a database.
Implement efficient search mechanisms to enable students to quickly find the exams they need.
Integrate the API with the Telegram bot @EpreuveBot to provide a user-friendly interface.
# Dependencies
The following dependencies are required to run the project:

Python 3.7 or later
Flask 2.0.1
SQLAlchemy 1.4.22
PostgreSQL (or another database compatible with SQLAlchemy)
# Runtime instructions
  1- Clone this repository on your local machine :
git clone https://github.com/votre-utilisateur/Projet-API-Baccalaureat-Camerounais.git
```

  2- Go to the project directory :
cd Projet-API-Baccalaureat-Camerounais
```

  3- Install the required dependencies:
pip install -r requirements.txt
```

  4- Configure the database:
Create an empty PostgreSQL database.
Modify the config.py file with your database connection information.

  5- Run the database migrations:
python manage.py db upgrade
```

  6- Run the API :
python app.py
```

  7- The API will now be accessible at http://localhost:5000. You can send HTTP requests to this address to interact with the API.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
# EpreuveBot
API pour fournir aux étudiants camerounais les épreuves d'examens de baccalauréats passés . Cette API est utilisée par le bot Telegram @EpreuveBot.
# Objectifs
L'objectif principal de cette API est de faciliter l'accès des étudiants camerounais aux epreuves des examens antérieurs du baccalauréat. 

Les objectifs spécifiques comprennent :
Créer une API robuste et sécurisée pour gérer les demandes de copies d'examens antérieurs.
Stocker et organiser les copies d'examens antérieurs dans une base de données.
Mettre en place des mécanismes de recherche efficaces pour permettre aux étudiants de trouver rapidement les examens dont ils ont besoin.
Intégrer l'API avec le bot Telegram @EpreuveBot pour fournir une interface conviviale aux utilisateurs.
# Dépendances
Les dépendances suivantes sont nécessaires pour exécuter le projet :

Python 3.7 ou version ultérieure
Flask 2.0.1
SQLAlchemy 1.4.22
PostgreSQL (ou une autre base de données compatible avec SQLAlchemy)
# Instructions d'exécution
  1- Clonez ce dépôt sur votre machine locale :
git clone https://github.com/votre-utilisateur/Projet-API-Baccalaureat-Camerounais.git
```

  2- Accédez au répertoire du projet :
cd Projet-API-Baccalaureat-Camerounais
```

  3- Installez les dépendances requises :
pip install -r requirements.txt
```

  4- Configurez la base de données :
Créez une base de données PostgreSQL vide.
Modifiez le fichier config.py avec les informations de connexion à votre base de données.

  5- Exécutez les migrations de la base de données :
python manage.py db upgrade
```

  6- Lancez l'API :
python app.py
```

  7- L'API sera maintenant accessible à l'adresse http://localhost:5000. Vous pouvez envoyer des requêtes HTTP à cette adresse pour interagir avec l'API.
