# Tableau Périodique Interactif avec Visualisation 3D des Atomes

Ce projet est une application web interactive qui permet d'explorer le tableau périodique des éléments et de visualiser la structure de chaque atome en 3D. L'application est entièrement contenue dans un seul fichier HTML et utilise la bibliothèque Three.js pour le rendu 3D.

## 🚀 Démo Live

*[Lien vers votre page GitHub Pages une fois déployée]*

## ✨ Fonctionnalités

* **Tableau Périodique Complet** : Affiche les 118 éléments connus, positionnés dynamiquement en fonction de leur structure électronique.
* **Code Couleur CPK** : Chaque case du tableau est colorée selon la convention de couleurs standardisée (Corey-Pauling-Koltun) pour une identification visuelle rapide.
* **Visualisation 3D Interactive** : Cliquez sur un élément pour afficher son modèle atomique en 3D. La vue est entièrement navigable (rotation, zoom, déplacement).
* **Deux Modèles de Visualisation** :
    * **Modèle de Bohr** : Une représentation classique avec des électrons orbitant sur des couches circulaires.
    * **Modèle Quantique** : Une visualisation plus moderne où les électrons apparaissent sous forme de points dans leur nuage de probabilité (orbitales `s` et `p`).
* **Fréquence d'Observation Réglable** : En mode quantique, un curseur permet de contrôler la fréquence des "sauts" de l'électron, de 1 à 50 fois par seconde.
* **Calculs Procéduraux** : La configuration électronique et la position dans la grille de chaque atome sont calculées à la volée, rendant le code modulaire et facile à maintenir.

## 🛠️ Technologies Utilisées

* **HTML5**
* **CSS3**
* **JavaScript (ES Modules)**
* **Three.js** : Pour le rendu 3D WebGL.

## ⚙️ Comment l'utiliser

Comme ce projet est un simple fichier `index.html` sans dépendances externes (au-delà de Three.js importé via un CDN), il n'y a pas de processus de build.

1.  Clonez ou téléchargez ce dépôt.
2.  Ouvrez le fichier `index.html` dans votre navigateur web.
