# Space Invaders 

*Si vous le souhaitez, vous pouvez introduire le projet space Invaders en quelques mots*

*Si vous le souhaitez, vous pouvez faire un petit sommaire pour atteindre plus facilement une semaine donnée.*  
*Il est à noter que le le glossaire devra être compléter au fil des séances* 
- [Semaine n°4 : du 24 au 28 mai](#semaine4)  
- [Semaine n°3 : du 17 au 21 mai](#semaine3)  
- [Semaine n°2 : du 10 au 15 mai](#semaine2)  
- [Semaine n°1 : du 26 au 30 avril](#semaine1)  
- [Glossaire](#glossaire)

## Semaine n°4 : du 24 au 28 mai <a id="semaine4"></a>

### Sprints et fonctionnalités réalisées 

#### Fonctionnalité n°2 : Déplacer un vaisseau dans l'espace de jeu (fini)

- Story n°4 : Déplacer un vaisseau vers la gauche en tenant compte de sa dimension
Mise en place de la méthode VaisseauAvance_DeplacerVaisseauVersLaGauche.


-------------

## Semaine n°3 : du 17 au 21 mai <a id="semaine3"></a>

### Sprints et fonctionnalités réalisées 

#### Fonctionnalité n°2 : Déplacer un vaisseau dans l'espace de jeu (fini)

- Story n°1 : Positionner un nouveau vaisseau avec une dimension donnée 

Mise en place des dimensions hauteur et longueur du vaisseau

- Story n°2 : Faire en sorte qu'il soit impossible de positionner un nouveau vaisseau qui déborde de l'espace de jeu

Création de la classe DebordementEspaceJeuException
  
- Story n°3 : Déplacer un vaisseau vers la droite en tenant compte de sa dimension  

Mise en place des tests test_VaisseauImmobile_DeplacerVaisseauVersLaDroite

### Diagramme de classes 

![Diagrammes de classes de la semaine 3](images/Diagramme_Semaine2.png)


-------------

## Semaine n°2 : du 10 au 15 mai <a id="semaine2"></a>


### Sprints et fonctionnalités réalisées 

#### Fonctionnalité n°1 : Déplacer un vaisseau dans l'espace de jeu (fini)
 

- Story n°3 : Déplacer le vaisseau vers la droite dans l'espace de jeu  
Le vaisseau se déplace d'un pas vers la droite 
Si le vaisseau se trouve sur la bordure droite de l'espace de jeu, le vaisseau doit rester immobile (aucun déplacement, aucune exception levée : le vaisseau reste juste à sa position actuelle).


- Story n°4 : Déplacer le vaisseau vers la gauche dans l'espace de jeu  
Le vaisseau se déplace d'un pas vers la gauche 
Si le vaisseau se trouve sur la bordure gauche de l'espace de jeu, le vaisseau doit rester immobile (aucun déplacement, aucune exception levée : le vaisseau reste juste à sa position actuelle).

### Fonctionnalité en cours d’implémentation : 
Aucune


### Diagramme de classes 

![Diagrammes de classes de la semaine 1](images/Diagramme_Semaine1.PNG)

### Nuage de mots du projet spaceinvaders (séance n°1)  
(généré à l’aide de Source Code Word Cloud Generator avec la liste JavaBlacklist.txt fournie en annexe)
 
![Nuage de mots de la semaine 1](images/NuageDeMots_Semaine1.PNG)


### Difficultés rencontrées 
Aucune

### Remarques diverses
 Pour pouvoir, mettre en place les tests, il a été nécessaire d’ajouter une fonctionnalité supplémentaire qui permet de représenter l’espace de jeu dans une chaîne ASCII.

-------------

## Semaine n°1 : du 26 au 30 avril <a id="semaine1"></a>


### Sprints et fonctionnalités réalisées 

#### Fonctionnalité n°1 : Déplacer un vaisseau dans l'espace de jeu (fini)

- Story n°1 : Créer un espace de jeu  
Un espace de jeu est créé aux dimensions données (2D) 
Cet espace de jeu est vide

-  Story n°2 : Positionner un nouveau vaisseau dans l’espace de jeu  
Un nouveau vaisseau est créé
Le vaisseau est positionné aux coordonnées transmises
Si un nouveau vaisseau essaye d’être positionné en dehors des limites de l’espace jeu, alors une exception devra être levée.
 Contraintes :
La position souhaitée est transmise par ses coordonnées x et y.
Le coin supérieur gauche de l’espace jeu (point en haut à gauche) a pour coordonnées (0,0)
La taille du vaisseau est réduite pour l'instant à son minimum (1 seul point)  


### Fonctionnalité en cours d’implémentation : 
Aucune


## Glossaire <a id="glossaire"></a>

* **Vaisseau** :  véhicule commandé par le joueur, pouvant se déplacer de droite à gauche et ayant la possibilité de lancer des missiles destinés à détruire le(s) envahisseurs.

* **Envahisseur**  :  ennemi qui apparaît à l'écran, se déplace automatiquement et qui doit être détruit par un missile lancé depuis le vaisseau du joueur.


* **Missile** :  projectile envoyé à la verticale par le vaisseau vers l'envahisseur dans le but de le détruire.

La définition des termes métiers relatifs au projet doit se trouver dans le glossaire 
Ce glossaire doit être compléter au fil des séances...

------------- 

