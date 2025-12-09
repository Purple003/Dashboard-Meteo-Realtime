# Dashboard Meteo Realtime

Application de visualisation meteo en temps reel utilisant Node.js, WebSockets et Chart.js. Ce projet a ete realise dans le cadre du TP.

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

[Inserez votre video de demonstration ici]

## Structure du projet

- app2.js : Serveur WebSocket.
- temp.csv : Donnees sources.
- index_tab.html : Interface utilisateur.
