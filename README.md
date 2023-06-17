# project-big-data-apache-beam

## Partie A :  Implémentation de k-means séquentiel (Python)

## Partie B : Implémentation d’une version streaming de k-means

**Algorithme :**

- Si la taille de X est T : enlever le plus vieux batch de X
- Ajouter B⁰ à X
- Initialiser les centroïdes C avec la partition P
- Obtenir les centroïdes C et la partition P avec l’algorithme k-means pondéré :
- les points des batches sont pondérés par rt où t est le numéro du batch ordonné par ordre décroissant : 0 est le batch le plus récent, 1 est le batch précédent, etc.


## Partie C : Implémentation de k-means distribué

## Partie D : Implémentation de k-means séquentiel distribué (Apache Beam)

## Partie E : Implémentation d'une version streaming et distribuée de K-means (Apache Beam)
