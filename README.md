# QuickChange  - Projet 2 : Création de l'API REST Backend

##  Présentation du Projet
Dans cette deuxième phase appelée **Le Système Nerveux**, l'application migre vers une architecture découplée. La logique de calcul quitte le navigateur pour être centralisée sur un serveur backend. Ce projet implémente une API REST respectant strictement les standards de nommage.

##  Technologies Utilisées
* **Node.js** & **Express** : Création du serveur HTTP et gestion des routes.
* **CORS** : Middleware de sécurité pour autoriser les requêtes provenant du frontend.
* **JavaScript (Vanilla)** : Utilisation de l'API `fetch` asynchrone (`async/await`) côté client.

##  Conformité RESTful (Anatomy of Action)
Conformément aux directives de conception, les points d'accès (endpoints) utilisent des ressources nommées (noms au pluriel) plutôt que des verbes :
* `POST /api/conversions` : Reçoit le montant et les devises, valide les données, effectue le calcul mathématique centralisé et renvoie un JSON.

##  Comment Lancer le Projet
1. Installez les dépendances nécessaires :
   ```bash
   npm install
