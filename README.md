# TPS ARCHITECTURE N-TIERS

Bienvenue dans le projet **TPS Architecture N-Tiers** ! Ce dépôt contient plusieurs exercices et projets pratiques pour explorer les concepts d'architecture N-tiers, de communication réseau, et de gestion des signaux en Node.js. 🖥️🌐

---

## 📂 Structure du Projet

Voici un aperçu des différents dossiers et leur contenu :

### **MyIRC**
Un serveur IRC (Internet Relay Chat) simple permettant aux utilisateurs de se connecter, discuter, et envoyer des messages privés.

- `server.js` : Implémentation du serveur IRC.
- `README.md` : Documentation associée.

### **MyIRC -S**
Une version améliorée du serveur IRC avec des fonctionnalités supplémentaires.

- `server.js` : Serveur avec gestion des commandes comme `/list` et `/whisper`.

### **TP-RPC**
Un projet basé sur gRPC pour gérer des tâches, récupérer des jeux via une API tierce, et manipuler des produits dans une base de données MongoDB.

- `server.js` : Serveur gRPC avec plusieurs services (tâches, jeux, produits).
- `client.js` : Client gRPC pour interagir avec le serveur.
- `todo.proto` : Définition des services et messages gRPC.
- `README.md` : Documentation détaillée.
- `Exercice 1 Appel d’une API tierce` : Exemple d'utilisation de gRPC pour interagir avec une API externe.

### **TP-Signaux**
Un projet pour explorer la gestion des signaux système (comme `SIGINT`) dans Node.js.

- `index.js` : Exemple de gestion des signaux avec des fonctionnalités avancées.
- `README.md` : Documentation associée.

### **TP-Sockets**
Un projet basé sur les sockets TCP pour implémenter un serveur et un client simples.

- `server.js` : Serveur TCP capable de répondre à des requêtes JSON.
- `client.js` : Client TCP pour envoyer des requêtes au serveur.
- `package.json` : Fichier de configuration du projet.

---

## 🛠️ Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (version 14 ou supérieure)
- [npm](https://www.npmjs.com/) (inclus avec Node.js)
- [Docker](https://www.docker.com/) (pour TP-RPC)

---