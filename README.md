# Auto-serf-python
Ce projet est une application Python utilisant Selenium et Tkinter pour automatiser la recherche de mots-clés sur Google, cliquer sur des liens spécifiques, naviguer sur des pages web et interagir avec des menus. L'interface graphique permet d'entrer des mots-clés, des URLs cibles et d'autres paramètres pour personnaliser l'automatisation.


Automatisation de recherche et navigation avec Selenium

Ce projet est une application Python utilisant Selenium et Tkinter pour automatiser la recherche de mots-clés sur Google, cliquer sur des liens spécifiques, naviguer sur des pages web et interagir avec des menus. L'interface graphique permet d'entrer des mots-clés, des URLs cibles et d'autres paramètres pour personnaliser l'automatisation.

Fonctionnalités

Recherche de mots-clés sur Google

Clic sur les liens correspondant aux sites cibles

Gestion des pop-ups et cookies

Défilement automatique sur les pages visitées

Interaction avec les menus spécifiés

Interface graphique pour personnaliser les paramètres

Prérequis

Avant d'exécuter le script, assurez-vous d'avoir installé les modules nécessaires.

Modules requis

Installez les dépendances avec la commande suivante :

pip install selenium webdriver-manager tkinter

Installation de Google Chrome et ChromeDriver

Le script utilise Google Chrome et ChromeDriver. Assurez-vous d'avoir Google Chrome installé sur votre système. ChromeDriver sera automatiquement géré par webdriver-manager.

Utilisation

Clonez ce dépôt Git :

git clone https://github.com/votre-utilisateur/nom-du-repo.git
cd nom-du-repo

Installez les dépendances :

pip install -r requirements.txt

Exécutez le script :

python script.py

Structure du projet

/nom-du-repo
│── script.py           # Script principal
│── README.md           # Documentation du projet
│── requirements.txt    # Liste des dépendances

Configuration et personnalisation

Mots-clés : Jusqu'à 10 mots-clés peuvent être entrés dans l'interface.

URLs cibles : Jusqu'à 5 URLs pour cibler les résultats de recherche.

Nombre d'opérations : Définit combien de fois l'automatisation doit s'exécuter.

Durée du défilement : Temps aléatoire de défilement sur les pages visitées.

Menus à cliquer : Jusqu'à 15 menus peuvent être spécifiés.

Remarque

L'utilisation de Selenium pour l'automatisation de la navigation sur le web peut être détectée par certains sites. Assurez-vous d'utiliser cette application en respectant les conditions d'utilisation des sites visités.

Contributions

Les contributions sont les bienvenues ! N'hésitez pas à soumettre une pull request ou à ouvrir une issue pour proposer des améliorations.

Licence

Ce projet est sous licence MIT. Vous êtes libre de le modifier et de le redistribuer avec attribution.
