Instructions pour exécuter le projet: Pour faire fonctionner ce projet Flask, veuillez suivre les étapes suivantes :
1. Créer un environnement virtuel
Exécutez la commande suivante pour créer un environnement virtuel Python : python -m venv monenvapp3
2. Activer l'environnement virtuel
Une fois l'environnement créé, activez-le avec la commande suivante : .monenvapp3\Scripts\activate
3. Installer les bibliothèques nécessaires
Installez les dépendances du projet en exécutant les commandes suivantes :
  pip install Flask
  pip install flask_migrate
  pip install passlib
  pip install pyyaml
  pip install jinja2
  pip install flask-bootstrap
  pip install bcrypt
Remarque :
-Si l'une des bibliothèques rencontre un problème d'installation, essayez d'abord de la désinstaller puis de la réinstaller :
  pip uninstall monenvapp3
  python -m venv monenvapp3
-Si vous rencontrez une erreur de permission lors de l'installation de la bibliothèque "  pip install flask-bootstrap
", suivez les étapes ci-dessous :
1. Purgez le cache de pip avec la commande : pip cache purge
2. Ensuite, réinstallez la bibliothèque en spécifiant le répertoire du cache :
pip install Flask-Bootstrap --cache-dir <chemin_vers_votre_répertoire_de_cache-flask_bootstrap>


