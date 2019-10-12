# integration1

Pour avoir accès au framework il vous faudra télécharger le dossier scss.

Ensuite il faudra le placer dans votre projet.

Par la suite il  faudra creer un fichier css qui sera watch par le fichier sass td8.scss qui se trouve dans le dossier scss.

Pour cela lancer la commande sass --watch chemin/fichier.scss:chemin/fichier.css

Il va falloir aussi intégrer le fichier css dans le fichier HTML avec une balise <link> .

Une fois ces étapes réalisées vous pouvez profiter du framework.

#cacractéristiques des fichier et comment les modifiers:

_button.scss : permet de paramettrer l'apparance des buttons, il est possible de les modifier en changeant les variables qui sont au dessus du fichier.

_color: est un fichier qui permet de d'asssocier une couleur à une "alert". Pour modifier les couleurs des "alerts" il faudra modifier les valeurs dans le fichier _color_alert.scss

_grid: est un fichier qui permet de gerer la grille générer. Vous pouver modifier la taille de grille en changeant les variables dans ce fichier.

_nav : est un fichier qui permet de gerer la barre de navigation, vous pouvez la modifier en changeant les variables en haut du fichier 