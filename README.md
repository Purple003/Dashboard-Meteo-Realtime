# Dashboard Meteo Realtime

Application de visualisation meteo en temps reel utilisant Node.js, WebSockets et Chart.js. 

## Fonctionnalites

- Serveur WebSocket (Node.js) qui lit un fichier CSV et diffuse les donnees.
- Client Web (HTML/JS) qui recoit les donnees en temps reel.
- Affichage des donnees dans un tableau dynamique.
- Visualisation graphique des temperatures (Min/Max) et precipitations.

## Pre-requis

- Node.js installe sur la machine.

## Installation

1. Ouvrir un terminal dans le dossier du projet.
2. Installer les dependances :

```bash
npm install
```

## Demarrage

1. Lancer le serveur :

```bash
node app2.js
```

Le serveur demarrera sur le port 5002.

2. Ouvrir le fichier `index_tab.html` dans un navigateur web.

## Demo

https://github.com/user-attachments/assets/b3ce6e28-582c-49e9-a1ee-228bacf3772b



## Structure du projet

- app2.js : Serveur WebSocket.
- temp.csv : Donnees sources.
- index_tab.html : Interface utilisateur.

## Auteur
- Nom : Arroche Aya
- Cours : Développement web full-stack avec JavaScript
- Encadre par :Pr.Mohamed LACHGAR



