# Fungimaker 0.7

Un outil créé à l’aide d’Houdini et sa composante Houdini Engine qui permet de facilement créer et itérer des formes de champignon à l’intérieur des moteurs Unity et Unreal Engine.

## Avant-Propos

L’outil nécessite Houdini Engine, qui n’est pas inclu avec la version gratuite de Houdini, Apprentice. Il est nécessaire de faire une installation rapide de l’extension Houdini Engine sur le moteur choisi afin que l’outil fonctionne sur les ordinateurs du centre de l’UQAT à Montréal. 

Il est nécessaire de vérifier la [compatibilité](https://www.sidefx.com/changelog/) de Houdini Engine avec le moteur choisi afin d’en assurer son fonctionnement. Les catégories Houdini Engine for Unreal plug-In et Houdini Engine for Unity plug-in permettent de voir la dernière version du moteur supportée. 

## Installation de Houdini Engine

**Unreal Engine 4** 

1. Trouver l'emplacement de l'extension :  *C:\Programmes\Side Effects Software\HoudiniXX.X.XXX\engine\unreal\Y.YY\HoudiniEngine* ;
2. Copier le **dossier** HoudiniEngine à l'emplacement de votre installation de Unreal Engine : 
*c:\Programmes\Epic Games\UE_Y.YY\Engine\Plugins\Runtime* ;
3. Vérifier l'installation de Houdini Engine sous l'onglet Plugins de Unreal Engine ;
4. Glisser-déposer le fichier fungimaker_x_x.hda dans votre scène ;

**Unity**
1. Trouver l'emplacement de l'extension :  *C:\Program Files\Side Effects Software\HoudiniXX.X.XXX\engine\unity* ;
2. Dans l'éditeur, importer le package (Assets>import package) ; 
3. Glisser-déposer le fichier fungimaker_x_x.hda dans votre scène ;

## Installation de l'outil 

**Unity et Unreal Engine 4**

Il suffit de cliquer-glisser l'objet dans le dossier du projet à l'intérieur du moteur, et d'ensuite le glisser dans la scène.   

## Utilisation 

### Paramètres 
Les différents paramètres modifient la forme du champignon. Les paramètres _LOD permettent de changer le niveau de détail du modèle. 
Le paramètre row permet de définir facilement la définition du champignon. 
### Baking 
Il est nécessaire de bake le modèle paramétrable. Il est possible de bake le champignon à l'intérieur d'un prefab dans Unity. Plus d'information à venir. 

## Support
Les versions 18.0.348 de Houdini, 4.25 de Unreal et 2019.4.1 de Unity fonctionnent présentement avec l’outil. (13/01/21)

Il est possible de me contacter à mon adresse guimond.antoine@gmail.com. 

## License
[MIT](https://choosealicense.com/licenses/mit/)
