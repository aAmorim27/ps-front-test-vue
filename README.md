# Test PrestaShop Développeur Front
​
Ce test a pour but d'évaluer les compétences techniques des candidats au poste de Développeur Front
​
## Consignes du test
Vous allez devoir réaliser l'intégration de la maquette d'une liste d'agences partenaires PrestaShop en VueJS   
​
### Etapes
1. Récupérer les données depuis l'API 
2. Intégrer la card
3. Intégrer la liste des cards 
4. Utiliser les données de l'API dans les cards

### Bonus
5. Utiliser VueX pour stocker les donneés de l'API
6. Créer une page contenant les données de l'agence cliquée 
​
## Contraintes
​
- Utilisation de VueJS
- Scss/Sass
​
## Setup du projet
​
### Prérequis
NodeJS   
NPM ou YARN
​
### Installer les dépendances
Afin de pouvoir utiliser l'API il faut installer les dépendances du projet avec votre gestionnaire de package préféré   
```
npm install
```
Ou
```
yarn install
```
​
### Démarrer l'API
Cette API utilise JSON Server pour fonctionner, cela permet d'avoir une API fonctionnelle pour du proto avec un simple json (db.json) comme base de données   
Pour la démarrer il suffit d'écrire cette commande dans votre terminal en étant dans le dossier de ce projet.
```
npm run api
```
Ou
```
yarn api
```
Pour plus d'info sur json server je vous invite à regarder sur le repo github suivant https://github.com/typicode/json-server
​
## Routes de l'API 
Cette api fonctionne sur l'adresse http://localhost:3000/
​
### Récupérer toutes les agences (GET)
```
http://localhost:3000/agencies
```
