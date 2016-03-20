# ![logo blender](src/blender.png)La 3D avec Blender
[INDEX](readme.md) >> Le plan de travail


## La vue
Par défaut, il n'y a qu'une vue 3D de la scène.

Avec la souris, vous pouvez vous déplacer dedans :
- le <em>scroll</em> permet de zoomer /dézoomer
- en cliquant sur la molette de <em>scroll</em> vous pouvez tourner autour de votre repère ![le repère](src/repere.png)

Avec le clavier:
- ```4``` et ```6``` : faire une rotation vers la gauche ou la droite
- ```8``` et ```2``` : faire une rotation vers le haut ou le bas
- ```0``` : entrer et sortir de la vue caméra
- ```5``` : vue en perspective ou orthographique
- ```7``` : vue de dessus
- ```1``` : vue de face
- ```3``` : vue de cotès
- &uArr; (maj) + ```C``` : recentrer le repère et la vue sur le centre de la scène
- &uArr; (maj) + ```.``` en ayant un objet sélectionné  (ou en ```edit mode``` avec un point, un segment ou une face sélectionné): recentrer le repère et la vue sur l'objet (ou sur l'élément de l'objet sélectionner).


<br />

 ![plusieurs vues 3D](src/vue-3d.gif)

Si vous souhaitez avoir plusieurs vues 3D, faite glisser le coin supérieur droit vers l'intérieur de la vue.

## Les modes d'éditions

![modes](src/edit_mode-object_mode.png)

Vous pouvez modifier les objets selon deux modes, le premier, <em>object mode</em> vous permettra de déplacer, mettre à l'échelle, faire des rotations sur un objet, le deuxième, <em>edit mode</em> vous permettra de faire ces même opérations et d'autres dans l'objet sélectionné. L'<em>edit mode</em> sert principalement à modifier certaines parties ou composantes de l'objet / <em>mesh</em>.

Vous pouvez à tout moment basculer entre ces deux modes avec la touche &rlarr; (tab) de votre clavier.


## Changer l'aspect des solides de la vue 3D


![changer le moteur de rendu](src/aspect-des-solides.png)

Ici vous allez pouvoir changer, l'aspect de vos solides, cela sert uniquement dans la vue 3D.
- *Bounding Box* montre les contours de votre solide sous la forme d'un cube
- *Wireframe* montre le maillage de votre solide ( fil de fer )
- *Solid* le solide entier recouvert avec la / les couleur/s que vous lui avez définis
- *Texture* idem mais recouvert avec la texture qui lui ait attribué
- *Material* idem mais recouvert avec l'aspect la matière qui lui ait attribué
- *Rendered* un aperçu de ce que va donner le rendu final
