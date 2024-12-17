# Bienvenue sur le dépôt des TP de NoSQL

Bienvenue dans le dépôt des travaux pratiques (TP) de NoSQL ! Ce projet contient une série de TP pour apprendre à utiliser et à comprendre les bases de données NoSQL. Vous y trouverez des exemples pratiques d'utilisation des différentes commandes et concepts liés aux bases de données NoSQL.

---

## Contenu des TP

### TP Redis

- **Prise en main de Redis** :
   - Démarrage de Redis et connexion via le client en ligne de commande.
- **Exemples de CRUD** :
   - Création, lecture, mise à jour et suppression des données.
- **Gestion des structures de données** :
   - Utilisation des listes, ensembles, ensembles ordonnés, et autres structures.
- **Système de Publication/Abonnement (Pub/Sub)** :
   - Envoi et réception de messages entre clients Redis.
- **Gestion des bases de données Redis** :
   - Travail avec plusieurs bases de données dans Redis.

---

### TP MongoDB

- **Prise en main de MongoDB** :
   - Installation, démarrage et connexion via le client MongoDB.
- **Interrogation de la base de données** :
   - Utilisation de `find()` pour afficher des documents selon des critères (par genre, pays, etc.).
   - Application de filtres pour des recherches avancées (par exemple, notes supérieures à un seuil donné).
- **Gestion des structures de données** :
   - Manipulation des tableaux d'objets imbriqués (acteurs, notes des films).
   - Utilisation de `distinct()` pour extraire des valeurs uniques (par exemple, genres ou grades des films).

---

### TP CouchDB - MapReduce

- **Installation de CouchDB avec Docker** :
   - Création d'une image Docker avec CouchDB.
   - Exécution d’un conteneur CouchDB avec persistance des données.

- **Prise en main de CouchDB** :
   - Configuration de l'utilisateur administrateur via le Dockerfile.
   - Exposition du service CouchDB sur le port `5984`.

- **Définition des fonctions MapReduce** :
   - **Fonction Map** : Transformation des documents JSON en paires clé-valeur.
   - **Fonction Reduce** : Agrégation des résultats intermédiaires.

- **Exemples pratiques** :
   - **Calcul du nombre de films par année** :
     - Extraction de l'année de sortie des films (fonction Map).
     - Agrégation pour compter les films par année (fonction Reduce).
   - **Calcul du nombre de films par réalisateur** :
     - Extraction du nom du réalisateur comme clé.
     - Comptage du nombre de films pour chaque réalisateur.
   - **Calcul du nombre de films par acteur** :
     - Parcours des tableaux d'acteurs pour extraire leurs noms.
     - Comptage du nombre de films par acteur.

- **Exercice avancé** :
   - **Représentation d'une matrice sous forme de documents** :
     - Utilisation d'une collection pour stocker des relations pondérées entre pages web.
   - **Calcul de la norme des vecteurs** :
     - Mise en œuvre d'une fonction MapReduce pour calculer la norme.
   - **Produit d'une matrice par un vecteur** :
     - Spécification d’un traitement MapReduce pour multiplier une matrice \( M \) par un vecteur \( W \).

---

## Comment utiliser ce dépôt

1. Clonez le dépôt sur votre machine locale :
   ```bash
   git clone https://github.com/AhmedAbdoulahi/NOSQL.git
