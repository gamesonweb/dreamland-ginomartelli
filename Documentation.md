![image](https://github.com/user-attachments/assets/3a5f2105-a456-479a-9766-ce5cf4f36928)

# Documentation

## Sommaire :
- #### Description détaillée du jeu
  - [Général](#général)
  - [Controls](#controls)
  - [Checkpoints](#checkpoints)
  - [Style](#style)
  - [Autres paramètres du menu](#autres-paramètres-du-menu)
  - [Lit](#lit)
  - [Parcours](#parcours)
  - [Orbes](#orbes)
  - [Fin du jeu](#fin-du-jeu)
  - [Menu développeur](#menu-développeur)
- #### Assets
  - [Modèles 3D](#modèles-3d)
  - [Textures](#textures)
  - [Sons et musique](#sons-et-musique)

---

## 🎮 Description détaillée du jeu

### Général

**DREAM'SCAPE** est un jeu d'aventure en 3D à la première personne, jouable dans un navigateur.  
Le joueur incarne un étudiant piégé dans un rêve étrange, peuplé d’îles flottantes, de mécanismes et d’énigmes.  
Son objectif : **récupérer 12 orbes dispersées dans le monde** pour activer un portail final et s’échapper **avant la fin du temps imparti (30 minutes)**.
Le jeu repose sur des mécaniques de plateformes, d’observation, et de logique, avec une progression libre entre les différentes zones.

Il faut cliquer sur **Play** pour lancer le jeu. Apres le chargement, le menu **Help** est affiché pour vous aider. Il suffit de cliquer hors du menu **Help** pour le chacher. 

![image](https://github.com/user-attachments/assets/e4c9f694-2fa2-45b3-9f6b-1b37413a9e04)

Vous commencez dans le lit sur l'île du début. Pour commencer à controler le joueur et la camera, il faut avoir cliqué sur l'écran pour cacher la souris. Le temps commence à s'écouler lorsque le joueur quitte le lit. Le temps restant est affiché en bas : Bonne chance !

---

### Controls

- **ZQSD** – Déplacement
- **Espace** – Saut
- **Shift** – Courir (maintenir) 
- **Souris** – Orientation de la caméra
- **Molette** – Zoom avant/arrière
- **Clic gauche** – Verrouille le curseur pour jouer (pointer lock)
- **ECHAP ou clic à nouveau** – Affiche le curseur

Les touches sont modifiables via le menu **Controls** : Cliquez sur le bouton correspondant au mouvement que vous voulez modifier et cliquez ensuite sur la touche de votre choix.

![image](https://github.com/user-attachments/assets/e408f429-8a16-4b23-820e-5fa26098829f)

Vous pouvez aussi modifier la sensibilité de la camera avec le curseur à droite.

---

### Checkpoints

Le monde est structuré autour de **chemins menant à différentes zones**, chacune contenant plusieurs orbes.  
Il y a 12 **socles lumineux** qui font office de **checkpoints déverrouillables**. Il suffit d'aller dessus pour les activer. Il s'ajouteront dans le menu **Checkpoints** et vous pourrez ensuite selectionnez la pastille de la couleur du checkpoint pour vous y teleporter.

![image](https://github.com/user-attachments/assets/2474e2e2-876c-4de5-aec5-f1888af73488)

Lorsque vous tombez dans le vide, vous réapparaitrez au dernier checkpoint débloqué ou utilisé. Lorsque vous n'avez toujours pas de chekpoint débloqué (excepté celui par défaut*) vous réapparaitrez dans le lit.

*Un checkpoint est déja débloqué au début du jeu pour pouvoir vous y téléporter si vous ne pouvez plus bouger (cela n'est jamais arrivé mais des problèmes peuvent toujours arriver sur les ordinateurs les moins puissants). 

---

### Style

Vous pouvez changer les couleurs des vetements du joueur : dans le menu **Style**, il suffit de cliquer sur la pastille correspondant au vetement pour choisir la couleur du vetement. 

![image](https://github.com/user-attachments/assets/08b7f100-edab-4000-8dec-cadb7b1b91fc)

Lorsque le menu style est activé, la caméra tourne autour du joueur afin de le voir de tous les cotés !

---

### Autres paramètres du menu

- **Sound** :
  Vous pouvez modifier le volume avec le curseur et activez/desactivez la musique et/ou les sons avec les 2 boutons à gauche :
![image](https://github.com/user-attachments/assets/ca37013e-d6d8-4e66-968d-f4831b45b49e)

- **Help** :
  Cette option affiche des informations pour vous aider. Le lien du GitHub et de la vidéo de completion du jeu y sont :
![image](https://github.com/user-attachments/assets/6c2b260f-6709-4a3e-994b-890674844ba2)

- **Pause** :
  Avec cette option, le temps se met en pause et vous pouvez ensuite continuer ou relancer le jeu :
![image](https://github.com/user-attachments/assets/9436c80e-3abb-4ee6-a33f-ab6f234cb1ec)

---

### Lit

Lorsque vous allez dans le lit, le jeu se met en pause et une animation se lance avec un ronflement :
![image](https://github.com/user-attachments/assets/405b8ae1-a78e-4cc1-bbdb-c1b182e25304)

Il suffit de se déplacer pour sortir du lit et reactiver le timer.

---

### Orbes

Les **12 orbes** sont le cœur du gameplay.  
Elles sont visibles de loin graçe à leur effet lumineux. Vous devrez réussir des parcours et trouver comment atteindre certain endroit pour récolter toutes les orbes.

![image](https://github.com/user-attachments/assets/43fd5d98-6fb0-4cce-b9a0-51245e0b9997)
![image](https://github.com/user-attachments/assets/982d4f27-8ca4-4890-a867-f0def770b0d3)

Pour récolter une orbe, il suffit d'aller dessus. Elle se deplacera jusqu'à son socle autour du portail :
![image](https://github.com/user-attachments/assets/bb6a9e80-8513-4bfd-a59d-aadad75260c7)

--- 

### Parcours

Le joueur doit parfois activer des éléments pour progresser, résoudre de petites énigmes ou faire preuve de rapidité.

Il y a plusieurs type de plateformes pour les parcours :
- Des plateformes qui apparaissent après l'activation d'un bouton. Elle disparaissent peu de temps apres donc il faut être rapide :

![image](https://github.com/user-attachments/assets/9d0b9378-86c4-493a-bcb1-47e9d3e411f7)

- Des plateformes qui se déplace. Il faut bien viser et prédir où sera la plateforme pour ne pas tomber dans le vide :

![image](https://github.com/user-attachments/assets/ffd3c39b-c539-4b12-bec3-875a0b619412)


- Des plateformes fixes, souvent accompagné de laser :

![image](https://github.com/user-attachments/assets/901f4692-6856-4e4b-9b6f-8361cbaa9857)


- Des petites îles et des éléments décoratifs utiles pour atteindre certain endroits :

![image](https://github.com/user-attachments/assets/85602fad-fe1f-42cc-b1d1-a24facc5b73a)



Les laser peuvent parfois avoir un mouvement. Si vous en touchez un, vous serez projetté violement !



Il y a aussi des gros murs qu'il faut faire disparaître pour aller derrière: allez sur le bouton qui activera le défi. 

![image](https://github.com/user-attachments/assets/94401558-9a94-4c89-ab5c-dfc83d4a7d80)

Une des touches sur le mur va s'illuminer : il faut appuyer sur la touche du mouvement correspondant. Après avoir réussi la première séquence, une touche supplémentaire aléatoire va s'illuminer, et la nouvelle séquence va apparaître sur le mur. Il faudra alors repeter la séquence en rajoutant la nouvelle touche à la fin. Cela se repete un certain nombre de fois jusqu'à disparition du mur.

Les touches de la séquence s'affichent en jaune. Lorsque vous appuyez sur la bonne touche elle s'affichera en vert. Vous pouvez ensuite appuyer sur la prochaine touche de la séquence.

![image](https://github.com/user-attachments/assets/9ed5a6ba-ba6c-4e66-bdc7-369777676c97)
![image](https://github.com/user-attachments/assets/eeab3f49-8c67-4321-9f53-a552b69d398e)

> [!TIP]
> Si vous êtes bloqué à un certain endroit dans le jeu, vous pouvez regarder la [vidéo de complétion](https://www.youtube.com/watch?v=XJVGw6Uxr3U)

---

### Fin du jeu

Quand les 12 orbes ont été récupérées, une animation se lance et un pont reliant l'île du début à l'île du portail apparait. Le portail s'active :

![image](https://github.com/user-attachments/assets/7c39f229-67b6-46b8-9913-a477bb4c2791)

![image](https://github.com/user-attachments/assets/c5e9372a-a7c8-4ee0-9b42-9f1d40d6f1b9)


Le joueur doit traverser le portail pour terminer le jeu mais un dernier defi est apparu à l'entrée du pont :  

![image](https://github.com/user-attachments/assets/aff66ee7-635d-46b5-8459-2dd65043ded3)



Le jeu est gagné si le joueur traverse le portail avant la fin des 30 minutes : 

![image](https://github.com/user-attachments/assets/00da86af-2569-44b6-b090-b794180cfd20)


Si les 30 minutes s'écoule avant que le joueur réussise, ceci apparaît :

![image](https://github.com/user-attachments/assets/7caf828d-1082-45a1-bc2d-f40287f2cc01)


---

### Menu développeur

Appuyez sur la touche **i** (minuscule) pour activer le menu d'aide développeur : 

![image](https://github.com/user-attachments/assets/ef58c781-f34d-4b8f-8a63-fd8b60fd1c55)

Vous pouvez vous amusez avec les paramètres (et tricher en déplacant des élements) ! 
Ce menu a été rajouté avec BABYLON afin de placer les éléments plus facilement lors de la création du monde. On a decidé de le laisser car il peut être amusant et peut aussi aider des joueurs si ils sont bloqués quelque part.

## 🧱 Assets

### Modèles 3D

Tous les modèles 3D ont été réalisés par l’équipe dans **Blender**, à l'exception des formes simple qui sont crées directement avec BABYLON à la création du monde (plateformes, bouton, laser...).

Le style de chaque modèle a été conçus pour être cohérents avec le style général et simple pour avoir un jeu optimisés pour le web.
Les animations du joueur viennent de [Mixamo](https://www.mixamo.com/#/)

---

### Textures

Le jeu utilise peu de textures :  
- La texture des plateformes et du mur viennent de la même image, modifié sur Gimp :

![platform](https://github.com/user-attachments/assets/017a8a4d-1cb9-4877-a827-6e103b18c50b)
![buttonInvis](https://github.com/user-attachments/assets/3bf2143b-5e36-4f5a-9c46-e7ce4b4208a8)
![platformLaser](https://github.com/user-attachments/assets/832f96ab-48b9-43a8-a9b8-9730b1cbe947)
![platformInvis](https://github.com/user-attachments/assets/3ac86229-92f5-4bed-aabf-6ce12844f96f)
![plateformMove](https://github.com/user-attachments/assets/f8da5b4a-d7bd-4ee7-9757-d201dd3ff295)
![buttonSimon](https://github.com/user-attachments/assets/841d6203-e301-4547-a1e2-bd31d042e4c1)

- Les îles, le portail, les orbes, le pont final, les lampes, les socles des checkpoints et les bancs ont comme texture une partie de l'image *gradient.png* :

![gradient](https://github.com/user-attachments/assets/6171f730-c72e-4325-a1ee-77fc01d0c3cc)

- Le glow et les ombres apportent la profondeur visuelle sans surcharge
- Le ciel à été fait sur Gimp :

![ciel2](https://github.com/user-attachments/assets/e0dddc61-0085-46d6-ab49-2966a0e71cbd)

- L'intérieur du portail :

![portail](https://github.com/user-attachments/assets/95f81d0c-34b1-4bf3-9657-3026ec9aaa38)

Tous les autres éléments ont une couleur uni.

---

### Sons et musique

Les sons viennent de Youtube et sont utilisables gratuitement sans copyright.

La musique : [https://youtu.be/zjTyprOLMxo?si=DbDfk77EcCsBjdC_](https://youtu.be/zjTyprOLMxo?si=DbDfk77EcCsBjdC_)  

---


