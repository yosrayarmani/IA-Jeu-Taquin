# Jeu de Taquin
Jeu de taquin 3x3 en Python permettant de jouer au taquin en utilisantles algorithmes de recherche en largeur, en profondeur et A*:
	nous utiliserons un taquin 3 × 3, dont les cases sont numérotées de 1 à 8 sachant que la case vide est représentée par 0. Le jeu consiste à remettre dans l’ordre ces cases à partir d’une configuration initiale.
 
![image](https://github.com/yosrayarmani/IA-Jeu-Taquin/assets/82341684/63f29740-2b8b-4e31-b479-b2d711b23fef)

# Indications: 
- t : tableau de dimension [3][3] qui représente le taquin.
- etat_depart : indique l’état initial du jeu.
- estEtatFinal : retourne True si l’état passé en paramètre est l’état final.
- transitions : retourne la liste des états voisins pour un état donné. On suppose que le coût de chaque transition est de 1.
- position_case_vide (t) qui renvoie la position de la case vide dans le taquin t sous la forme d’un couple (x,y) : x est le numéro de colonne, y est le numéro de ligne (les numéros débutant à 0).
- numero_dans_Case(t, x, y): retourne la valeur qui existe dans la case de coordonnées (x,y).
- permuter (t, c1, c2): permet de permuter les pièces situées dans les cases de coordonnées c1 et c2. (c1=(x1,y1))
- afficher_taquin (t) : affiche le taquin dans l’état actuelle.

## Ouvrir le Notebook avec Google Colab
Pour exécuter et interagir avec le notebook, vous pouvez l'ouvrir directement avec Google Colab.
Cliquez sur le badge "Open in Colab" pour lancer le notebook dans votre navigateur avec Google Colab :
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yosrayarmani/IA-Jeu-Taquin/blob/main/taquin.ipynb)

Assurez-vous de disposer d'un compte Google pour utiliser Google Colab.
