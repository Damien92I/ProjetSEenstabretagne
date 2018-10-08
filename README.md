# ProjetSEenstabretagne



## Contextes du projet :

- Réserve naturelle => animal blessé (objet à identifier)
- Catasrophe/ accident -brèche/blessé
- Engin explosif à detecter 



## Objectif :

- Explorer & Cartographier la zone
- Identifier obstacle & objectifs
- (Récuperer l'objectif => envoi du buggy vers l'objectif)



## Ressources nécessaires :

- 2 Buggies
- Radar (fourni par auto-cruise)
- Interface Radar
    a) PC
    b) Pi
    c) PiCAN2
 - Raspberry Pi
 - Lidar => Identification du modèle ADU
 
 
 

## PRINCIPE : EXPLORATION-RECUPERATION
 
 
## I- EXPLORATION (Dans un premier temps avec un système fixe puis fixation sur buggy radio commandé)
 
 a) Utilisation du système Lidar => Cartographier la zone (+ ou - proche selon le modèle Lidar) + Relais du Radar selon les conditions (intempéries: brouillard...)
 
 b) Utilisation du système Radar => Detection d'obstacles : fixes dans un 1er temps et mobiles ensuite 
 
 c) Utilisation d'une caméra (potentiellement la caméra de la RaspberryPi) => Photographier les obstacles, identifier à l'aide d'une image numérique (détection de contours ect...)
 
 
 ## Lien entre I et II :
 
 - Traitement des informations reçues à partir de l'activité I
 - Détermination d'un chemin le plus court (avec évitement d'obstacles)
 - Affichage des informations sur une app mobile => distribution sur une IHM
 
 
 ## II- RECUPERATION (buggy autonome) 
 
 Emprunt du chemin le plus court vers objectif (déterminé ultérieurement) 
 
