Hyrule Castle 🏰
Un jeu textuel basé sur l'univers de The Legend of Zelda, développé en Typescript. Ce projet est conçu pour fonctionner de manière simple en local ou en environnement conteneurisé grâce à Docker.

Fonctionnalités principales
Exploration du château et de ses environnements mystérieux.
Système de combat contre des ennemis dynamiques.
Gestion des personnages et de leurs statistiques.
🛠️ Structure du projet
Voici les principaux fichiers et scripts du projet :

launcher.sh : Le script principal pour lancer le jeu.
modifier.sh : envoi les nouvelles données dans le jeu.
build.sh : Création de contener pour chaques instructions du Dockerfile.
Dockerfile : Fichier de configuration pour exécuter le jeu dans un conteneur Docker.


⚙️ Installation
1. Pré-requis
Assurez-vous que les outils suivants sont installés sur votre machine :

Node.js : Version 16 ou plus récente.
TypeScript : Version 5 ou plus récente.

🚀 Comment démarrer ?
Clonez le dépôt :
git clone https://github.com/Mael2612/HYRULE-CASTLE.git
cd HYRULE-CASTLE

Installez les dépendances :
  npm install
🚀 Lancement

1. Lancer le projet
  npm start
🛠️ Fonctionnalités
Gestion des salles et des interactions via des classes spécifiques (Room, Character).
Modifications dynamiques de gameplay grâce aux mods (easy, intermediate, hard).
Utilisation d'ESLint pour un code propre et maintenable.
Évolutivité facilitée grâce à une architecture modulaire.
🌟 Ressources Utilisées
TypeScript
Node.js
ts-node
eslint
🏰 Plongez dans l'aventure et prouvez que vous êtes digne de Hyrule Castle ! ⚔️
