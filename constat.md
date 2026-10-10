5 constats :

- Impossible de savoir sur quel composant on se trouve avec la navigation clavier
- Impossible de sélectionner un film (va directement sur le favoris) avec la navigation clavier
- Obliger d'utiliser Tab pour se déplacer sur le site (donc tout le temps en avant) au lieu de pouvoir utiliser les flècherôles directionnel, utiles pour revenir en arrière
- Pas d'explications sur le  de l'étoile jaune (favoris ?)
- Pastille verte / rouge, impossible de savoir ce que ça représente

3 éléments marquants corrigés : 

Elem 1 : Rendre les éléments sélectionnables avec la tabulation, ajout de tabIndex sur les dives et retrait de outline: none sur les boutons, inputs et autres en focus
Impact avant après : On passe d'un site où on ne sait pas où on se dirige avec le clavier à des icônes simple à identifier quand on les sélectionne

Elem 2 : Ajout d'un bouton avec du texte pour que l'utilisateur comprennes qu'il peut appuyer dessus pour voir les séances au lieu de cliquer sur le bouton directement
Impact avant après : Facile de comprendre que les cartes sont sélectionnables pour voir les séances alors qu'avant il fallait toucher à tout.

Elem 3 : Retrait de la pastille rouge/verte en faveur d'un texte qui indique lorsqu'une séance n'a plus de places disponibles
Impact avant après : permet de directement comprendre l'information donnée, sans passer par un code couleur, ce qui aide également pour les personnes qui ont des difficultés a distinguer les couleurs.

Privilégier html natif
Pas de tabindex positif
ARIA que si html insuffisant
Conserver l'apparence générale