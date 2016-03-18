# <img src="src/blender.svg" height="40px"> La 3D avec Blender
<a href="readme.md">Index</a> >> Le plan de travail
___

## Sélection

La prise en main de Blender peut sembler déroutante au début, car dans la scène, le clique droit sert à la selection d'objet et le clique gauche permet de déplacer un repère qui servira à déplacer les objets ou <em>mesh</em>.

## La vue
Par défaut, il n'y a qu'une vue 3D de la scène.

Avec la souris, vous pouvez vous déplacer dedans :
- le <em>scroll</em> permet de zoomer /dézoomer
- en cliquant sur la molette de <em>scroll</em> vous pouvez tourner autour de votre repère

Avec le clavier:
- <code>4</code> et <code>6</code> : faire une rotation vers la gauce ou la droite
- <code>8</code> et <code>2</code> : faire une rotation vers le haut ou le bas
- <code>0</code> : entrer et sortir de la vue caméra
- <code>&uArr;</code> (maj) + <code>C</code> : recentrer le repère et la vue


#### Les modes d'éditions
Vous pouvez modifier les objets selon deux modes, le premier, <em>object mode</em> vous permettra de déplpacer, mettre à l'échelle, faire des rotations sur un objet, le deuxième, <em>edit mode</em> vous permettra de faire ces même opérations et d'autres dans l'objet sélectionné. L'<em>edit mode</em> sert principalement à modifier certaines parties ou composantes de l'objet / <em>mesh</em>.

Vous pouvez à tout moment basculer entre ces deux modes avec la touche &rlarr; (tab) de votre clavier.

#### Les composants des objets
Il existe dans tout les logiciels de 3D la même dénomination pour les composants d'un objet.
- le point /<em> vertice </em>
- le segment /<em> edge </em>
- la face /<em> face </em>

#### Les pricipaux raccourcis
Les commandes les plus courantes ( communes aux <em>object mode</em> & <em> edit mode</em> ):
- <code>g</code> (grab) * : déplacer la sélection
- <code>r</code> (rotate) * : appliquer une rotation à la sélection
- <code>s</code> (scale) * : changer l'échelle de la sélection

Les commandes spécifiques au <em>edit mode</em>
- <code>e (extrude) * : extruder la sélection

*:Vous pouvez, après avoir lancer ces commandes, appuyer sur x, y ou z pour vérouiller la modification sur ces axes.
Vous pouvez aussi, après avoir vérouiller un axe, définir une valeur à l'aide de votre clavier.
- <code>a</code> : tout sélectionner / tout déselectionner
- <code>b</code> : créer un sélection en traçant un rectangle
- <code>c</code> : créer une sélection en déplaçant un cercle ( le zoom / dézoom de la molette de la souris permettra de modifier son rayon)
- <code>x</code> : supprimer la sélection
- <code>&uArr;</code> (maj) + <code>D</code> : duppliquer la sélection

*: objet / face(s) / segement(s) / point(s)
