# Projet 10 Détection de faux billets 

Notre disposition six données géométriques pour chaque billet. 
L’algorithme devra donc être capable de prendre en entrée un fichier contenant les dimensions de plusieurs billets,
et de déterminer le type de chacun d’entre eux, à partir des seules dimensions. Nous fournissons à ce sujet le format type de nos fichiers de
billets avec lequel l’algorithme sera censé fonctionner, au sein d’un fichier nommé billets_production.csv.


Nous aimerions pouvoir mettre en concurrence deux méthodes de prédiction :
● une régression logistique classique ;
● un k-means, duquel seront utilisés les centroïdes pour réaliser la prédiction.
Cet algorithme se devra d’être naturellement le plus performant possible pour identifier un maximum de faux billets au sein de la masse de billets
analysés chaque jour.