# Space Invaders
Projet Space Invaders M2104

Ce projet consiste à réaliser une copie du jeu Space Invaders grâce au langage java en TDD.

- [Semaine n°1 : du 26 au 30 avril](#semaine1)  
- [Glossaire](#glossaire)

## Semaine n°1 : du 26 au 30 avril <a id="semaine1"></a>

#### Fonctionnalité n°1 : Déplacer un vaisseau dans l'espace de jeu (fini)

- Story n°1 : Créer un espace de jeu  
On crée un espace de jeu aux dimensions voulu, celui-ci est vide.

-  Story n°2 : Positionner un nouveau vaisseau dans l’espace de jeu 
On crée un vaisseau qui est positionné au coordonnées donnée
 Contraintes :
La position que l'on souhaite donnée au vaisseau est modélisé par des coordonnées x et y
La base de notre repère pour les coordonnées est le coin supérieur gauche(le point tout en haut à gauche), il a donc pour coordonnées (0,0)
Pour l'instant, on réduit la taille de notre vaisseau au maximum, c'est à dire un point.


### Fonctionnalité en cours d’implémentation : 
Si les coordonnées d'un vaisseau sont en dehors de l'espace de jeu, alors on lèvra un exception.

### Diagramme de classes 

![Diagrammes de classes de la semaine 1](images/DiagrammeClasses_Semaine1.png)

### Nuage de mots du projet spaceinvaders (séance n°1)  
 
![Nuage de mots de la semaine 1](images/NuageMots_Semaine1.png)


### Difficultés rencontrées 
Pour l'instant aucune difficulté n'a été rencontré.

### Remarques diverses
 Pour pouvoir, mettre en place les tests, il a été nécessaire d’ajouter une fonctionnalité supplémentaire qui permet de représenter l’espace de jeu dans une chaîne ASCII.

-------------

## Glossaire <a id="glossaire"></a>

* **Vaisseau** :  véhicule commandé par le joueur, pouvant se déplacer de droite à gauche et ayant la possibilité de lancer des missiles destinés à détruire le(s) envahisseurs.

* **Envahisseur**  :  ennemi qui apparaît à l'écran, se déplace automatiquement et qui doit être détruit par un missile lancé depuis le vaisseau du joueur.

* **Missile** :  projectile envoyé à la verticale par le vaisseau vers l'envahisseur dans le but de le détruire.

------------- 
