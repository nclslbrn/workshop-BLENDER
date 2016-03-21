# ![logo blender](src/blender.png)La 3D avec Blender
[INDEX](readme.md) >> Les matériaux
## Cycle
![changer le moteur de rendu](src/switch-render-engine.png) Ici nous traiterons les matériaux avec le moteur de rendu *Cycle*, pour continuer vous devez changer le moteur de rendu en haut de la vue 3D.
### Pourquoi utiliser *Cycle* et pas le moteur de rendu par défaut, *Blender render* :  
>*Cycle* permet d'avoir plus facilement un rendu photo-réaliste, on peut aussi prévisualiser le matériel et la texture sans faire de rendu. Il a un aspect plus granulaire que le moteur de rendu par défaut.

## Les *shaders*

Le matériel est définit par les réglages que l'on donne aux shaders.
Voici les principaux shaders :
- *Transparent BSDF* : un shader transparent utile pour certain liquide u pour des matériaux plus aériens
- *Glossy BSDF* : pratique pour les métaux
- *Glass* : pour le verre et le plexiglasse
- *Diffuse* : pour les matières opaques qui absorbe la lumière
- *Emission* : utile pour des éléments lumineux
- *Anistropic BSDF* : utile pour un le métal et les matériaux réflechissant

Vous pouvez aussi mixer les *shaders* avec *Add shader* ou *Mix shader*.


Parmis les réglages des shaders, on trouvera :
- Rougness : un réglage de la dureté du matériel
- Normal : la méthode de déploiement du matériel sur le solide


Si vous voulez en savoir plus sr les shader, je vous recommande [cet article]( http://www.blenderguru.com/articles/cycles-shader-encyclopedia/) qui explique à peu près tout sur le sujet.

## Installer une collection de matériaux

![une collection de matériaux par http://addictedtocg.com/ ](http://i0.wp.com/addictedtocg.com/wp-content/uploads/2015/05/4K-materials-render.png?w=3248)   
<small>Source image : [http://addictedtocg.com/](http://addictedtocg.com/)</small>

Vous pourrez télécharger une collection de matériaux [ici](http://www.mediafire.com/download/ayvtjk3soa5a69a/Blender_Materials.7z).
Pour l'utiliser, dans la barre de menu en haut, aller dans ```File``` puis dans ```Append```, aller à l'emplacement du fichier et sélectionner le matériel que vous souhaiter.

![panneau des matériaux](src/material-panel.png)

Si on va dans les réglages des matériaux, on trouvera désormais le matériel que vous venez d'importer. Si vous avez sélectionné un solide, vous pourrez lui appliquer ce matériel.
