# Simulateur de vol plané

## Concept

Ce projet vise à créer un simulateur de vol plané en réalité virtuelle.
Pour cela, nous développons à l'aide du logiciel Unity3D et d'un casque de réalité virtuelle.

L'objectif principal de ce projet est de pouvoir se déplacer au-dessus d'un paysage donné et de pouvoir regarder depuis le point de vue d'un oiseau ce même paysage.

L'objectif secondaire serait d'utiliser non pas une manette pour se déplacer, mais des mouvements plus naturels à l'aide des bras.

## Équipement

Pour l'instant, on utilise une structure composée de plusieurs éléments :
 - Un casque de réalité virtuelle (Oculus Rift ou HTC Vive)
 - Des contrôles aux mains (Wiimote ou simple manette pour les tests)
 - Un objet gonflable afin de mettre la personne en position horizontale et garder l'immersion dans l'univers virtuel

## Théorie

Sachant que l'on garde le repère de Unity3D, on a :
 - Vecteur x : mouvement horizontal de la tête
 - Vecteur y : mouvement vertical de la tête
 - Vecteur z : mouvement de profondeur

Les mouvements du casque ne serviront que comme caméra. La manette sera utilisée pour contrôler le vol plané puis sera remplacée par des gants équipés.

Les gants permettront de situer les bras de la personne. Ils fonctionneront comme ceci :

 - Si les bras sont en croix (tendus, perpendiculaires et opposés par rapport au buste), la hauteur permettra de contrôler l'angle du vol.

 - Si les bras sont le long du corps, le vol plané partira en piqué.
