# Grand Oral : Architecture du véhicule 
### Problématique : 
## Plan :
- Introduction
- Théorie
- Application
## Introduction :
Bonjour, je vais vous parler pour mon sujet de Grand Oral de l'aérodynamique. Tout d'abord, pourquoi ce sujet ? Dans le cadre d'un projet de SI qui s'intitule "course en cours", j'ai dû avec mon équipe, créer une voiture miniature et élaborer un stand, des tenues,... On s'était donc réparti les rôles et je me chargeais de l'architecture et du design du projet. Cette partie était utile pour le coté visuel mais aussi pour 
Pour travailler sur l'aérodynamique, il faut étudier la force de trainée, c'est à dire la force appliquée sur le véhicule par le fluide dans lequel il se déplace. Il faut tout d'abord établir l'équation de la trainée qui se definit par la trainée est égale a la moitié du coefficient de trainée fois la masse volumique fois le carré de la vitesse fois la surface de référence. on va donc étudier les variables afin de minimiser la force de trainée :
## Théorie :
### Coefficient de Trainée :
On commence par le coefficient de trainée, tout d'abord, qu'est ce que c'est que ce coefficient ? C'est une classification appliquée pour la resistance aérodynamique d'un voiture par exemple, qui est définie par la forme de la surface avant de la voiture (en tres grande partie). Ce qui veut dire q'une surface plane n'aura pas le même coefficient de trainée, la même resistance aérodynamique qu'une surface sphèrique. De plus, cette valeur doit être la plus petite possible afin d'avoir une trainée moins élevée. Pour donner un ordre d'idée, une forme de cuve arrondie a le coefficient le plus élevé avec 2.30, ça commence à devenir intéressant avec une surface pyramidale qui a un coefficient de 0.50, et enfin la forme la plus intéressante, c'est une forme de goutte allongée, qui a un coefficient de 0.04. Cependant pour une voiture, la forme avec le meilleur coefficient, cest la même forme de goutte mais coupée en deux dans le sens de la longueur, ce qui donne un coef de 0.09. On essaie donc d'atteindre un coefficient de trainée proche de 0.1.
### Surface de Référence :
### Supplément : L'aileron
## Application :
### Modélisation :
### Tests :
