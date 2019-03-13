# Méthode particulaire
Ce dossier contient les fichiers des classes Robot et Kalman ainsi que le fichier main permettant de lancer le scénario pour n robots.

## Classe robot
Le robot est définit par sa position (x,y), son cap (theta) et la commande (u).
Trois méthodes sont implémentées:
- evolution
- draw
- scenario
- Kalman


Préparation de la compilation : 
    mkdir build
    cd build
    cmake ..

Pour compiler
    make

Pour lancer l'exécutable
    ./Main 