3cs :

Camera : Flotte au dessus du joueur mais le suis (style Animal crossing new horizon), quand le joueur zoom la camera va à la première personne

Character : Un paysan, les mouvement de bases d’unreal feront l’affaire

Controls : Stick directionnelle gauche pour bouger, X pour interagir/arroser/planter/accepter, Y pour ouvrir l’inventaire, B pour faire retour, gâchettes pour zoomer, épaules pour faire naviguer la barre d’objet ou, si une structure est sélectionner, tourner les structures dans leurs différentes position (en général gauche, droite, haut et bas)

- Si le joueur appui sur X, alors que la selection de la barre d’objet est sur l’arrosoir , sur un terrain avec une graine il l’arrose

- Si le joueur appui sur X , alors que la selection de la barre d’objet est sur une graine, il l’a plante

- Si le joueur appui sur X, alors que la selection de la barre d’objet est sur un fruit et que la plateforme sur laquelle le joueur a une partie vide alors la correspondante au fruit apparaît en jaune, ou en rouge si le joueur essaye de la mettre sur un terrain invalide (pas de vide), si il réappui sur X alors que la plateforme est jaune il place la plateforme, si il appui sur B il annule la pose de la plateforme

- Si le joueur appui sur X, alors que la selection de la barre d’objet est sur une structure et que la plateforme sur laquelle le joueur ne possède pas de plante alors la structure apparaît en jaune, ou en rouge si le joueur essaye de la mettre sur un terrain invalide vide ou sur un terrain avec une plante, si il réappui sur X alors que la structure est jaune il place la structure, si il appui sur B il annule la pose de la plateforme, si il appui sur les épaules il tourne la structure (épaule de gauche pour tourner à gauche et droite pour tourner à droite)  
  
  

  

Player’s fantasy : Soit un paysans sur une île flottante, fais pousser tes plantes pour agrandir ton île et utilise les pour te déplacer. Dans ce jeu, cultiver c’est construire.

  

Principe :

Le joueur commence sur une petite île de 4/4 ( avec une cabane (qui prends 4 cases), un plan de travail (prends 2 cases), le reste de l’île est cultivable (toute les plateforme du jeu sont cultivable si elle n’est pas occupé par une structure ou une autre plante), avec 4 plan de graine plate planté :

| Maison | Maison |        | Plan de travail |
| ------ | ------ | ------ | --------------- |
|        |        |        |                 |
|        | Graine | Graine |                 |
|        | Graine | Graine |                 |


Il y a un système de jour :

- Si un plan de terre :

- N’est pas occupé par une structure (comme la maison ou le plan de travail)

- Qu’il y a une graine/plante germé dessus

- Qu’il est arrosé

  

Alors la plante dessus passe au niveau supérieur : Graine → Plante germé → Plantes avec fruits

La plantes avec fruits possèdes entres 1-3 fruits et 0-2 graines.

Il y a trois types de plantes :

- Les plantes Plates : Qui donnent des fruits plats et des graines plates

- Les plantes Élevées : Qui donnent des fruits élevés et des graines élevées

- Les plantes Basses : Qui donnent des fruits bas et des graines basses

  

Quand on récolte un fruit ont détruit la plantes laissant la plateforme non occupé : Les fruits ont des pouvoir particulier :

- Le fruit plats quand posé sur le coté d’une plateforme crée 1 autre plateforme (2x2x0,5) au même niveau que le joueur sur laquelle il peut marché.

- Le fruits élevés quand posé sur le coté d’une plateforme crée une échelle du même coté vers le haut (0,2x0,01x1) avec au bout une autre plateforme (2x2x0,5) 

- Le fruit bas quand posé sur le coté d’une plateforme crée une échelle du même coté vers le bas (0,2x0,01x-1) avec au bout une autre plateforme (2x2x0,5)

  

Les fruits peuvent aussi créer des objets quand on interagi avec le plan de travail ou plan de travail portatif :

- Cuiseur plat : (pour construire : 5 fruit plat, 3 graines plates) : Quand on interagi avec on peut transformer 5 fruit plat pour obtenir 1 plat plat

- Cuiseur élevé : (pour construire : 5 plat plat ,5 fruit bas, 3 graines basses) : Quand on interagi avec on peut transformer 5 fruit plat pour obtenir 1 gâteau élévé

- Cuiseur bas : (pour construire : 5 gâteau élevé ,5 fruit bas, 3 graines basses) : Quand on interagi avec on peut transformer 5 fruit plat pour obtenir 1 soupe basse

- Turbine horizontale : (pour construire :5 plat plat, 20 fruit plat, 30 graines plates) : Fais bouger l’île entière de 1 plateforme dans la direction où la turbine est pointé (gauche, droite, devant, derrière)

- Turbine verticale : (pour construire :3 gâteau élevé, 2 soupe basse, 10 fruit élevé, 10 fruit bas,15 graines élevés, 15 graines basses) : Fais bouger l’île entière de 1 plateforme dans la direction où la turbine est pointé (haut, bas)

- Sac de couchage : (pour construire : 10 gâteau élevé, 10 soupe basse, 10 plat plat) : Permet d’aller au jour suivant sans avoir besoin de revenir à la cabine

- Atelier portatif : (pour construire : 20 fruits plats, 20 fruits élevé, 20 fruits bas, 20 graines plates, 20 graines élevés, 20 graines basses) : Permet de construire des structures sans avoir besoin de revenir à la cabine

- Grand arrosoir : (pour construire : 5 soupe basse, 10 fruit bas, 20 graines basses, 10 gateau élevé) : Durer d’arrosage X2

- Super engrais : (pour construire :1 soupe basse, 10 fruit bas, 10 graines basses) : Utilisation unique. Transforme une graine en plante à fruit immédiatement

- Engrais : (pour construire : 2 fruit bas, 1 graines basses) : Utilisation unique, Fais passer une plante au niveau supérieur

  

UI :

HUD : Barre en haut à droite avec 10 emplacement (style minecraft mais en haut à droite) les différents objets utilisables et leurs nombres: Graines, Arrosoirs, Grand arrosoirs, sac de couchage, atelier portatif, engrais, super engrais et les structures dans l’inventaire.

Arrosage : Petite barre bleu apparaît en haut du joueur et se rempli progressivement

Menu :

- Main menu : Deux boutons : Play, Quit

- Menu pause : 3 boutons : Resume, Play, Main menu

- Menu Inventaire : Liste de tout les objets et leurs nombre, on peut échanger les structures dans l’inventaire avec celles de la barre d’objet de l’HUD

- Menu plan de travail : Menu déroulant avec les différentes structures, leurs effets et leurs prix avec en bas les ressources en graines, fruits, plat plat, gateau élevé et soupe basse du joueur. (le plan de travail portatif à l’option : « Replier le plan de travail » en plus)

  

La dernière île est appelé « le soleil » et est le seul but que le joueur à dès le début du jeu. Il y a plusieurs autres îles flottante avec trois proches :

- Une île très proche au même niveau que celle du joueur, cette île possède des plantes élevées auquel le joueur n’avait pas accès jusqu’à lors.

- Une île proche mais en haut de 3 plateforme environ, il faut utiliser les fruits élevés pour y accèder et le joueur obtient là les plantes basses.

- Une île en bas de 5 plateforme et est proche, cette île est très grande et offre au joueur une grande quantité de terrain cultivable.