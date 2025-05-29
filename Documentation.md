![image](https://github.com/user-attachments/assets/3a5f2105-a456-479a-9766-ce5cf4f36928)

# Documentation

## Sommaire | Table of Contents :

### Version Française :
- #### Description détaillée du jeu
  - [Général](#général)
  - [Contrôles](#contrôles)
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

### English Version :
- #### Detailed Game Description
  - [General](https://github.com/gamesonweb/dreamland-ginomartelli/blob/main/Documentation.md#general)
  - [Controls](#controls)
  - [Checkpoints](https://github.com/gamesonweb/dreamland-ginomartelli/blob/main/Documentation.md#checkpoints-1)
  - [Style](https://github.com/gamesonweb/dreamland-ginomartelli/blob/main/Documentation.md#style-1)
  - [Other Menu Settings](#other-menu-settings)
  - [Bed](#bed)
  - [Parkour](#parkour)
  - [Orbs](#orbs)
  - [End of the Game](#end-of-the-game)
  - [Developer Menu](#developer-menu)
- #### Assets
  - [3D Models](#3d-models)
  - [Textures](https://github.com/gamesonweb/dreamland-ginomartelli/blob/main/Documentation.md#textures-1)
  - [Sounds and Music](#sounds-and-music)

---

## 🎮 Description détaillée du jeu

### Général

**DREAM'SCAPE** est un jeu d'aventure en 3D à la première personne, jouable dans un navigateur.  
Vous incarnez un étudiant piégé dans un étrange rêve rempli d'îles flottantes, de mécanismes et d'énigmes.  
Votre but : **récupérer 12 orbes dispersées** dans le monde pour activer le portail final et vous échapper **avant la fin du temps imparti (30 minutes)**.  
Le jeu propose des mécaniques de plateforme, de logique et d'observation, avec une progression libre entre les zones.

Il faut cliquer sur **Play** pour lancer le jeu. Apres le chargement, le menu **Help** est affiché pour vous aider. Il suffit de cliquer hors du menu **Help** pour le cacher. 

![image](https://github.com/user-attachments/assets/e4c9f694-2fa2-45b3-9f6b-1b37413a9e04)

Vous commencez dans un lit sur l’île principale. Pour contrôler le joueur et la caméra, cliquez sur l’écran pour cacher la souris.  
Le chronomètre commence une fois sorti du lit. Le temps restant est affiché en bas de l’écran. Bonne chance !

---

### Contrôles

- **ZQSD** – Déplacement
- **Espace** – Saut
- **Shift** – Courir (maintenir) 
- **Souris** – Orientation de la caméra
- **Molette** – Zoom avant/arrière
- **Clic gauche** – Verrouille le curseur pour jouer (pointer lock)
- **ECHAP ou clic à nouveau** – Affiche le curseur

Vous pouvez modifier les touches dans le menu **Contrôles**. Cliquez sur un bouton d’action puis appuyez sur une nouvelle touche.  
La sensibilité de la caméra est aussi ajustable.

![image](https://github.com/user-attachments/assets/e408f429-8a16-4b23-820e-5fa26098829f)

---

### Checkpoints

Le monde est construit autour de **chemins menant à différentes zones**, chacune contenant plusieurs orbes.  
Il existe 12 **socles lumineux** qui servent de **checkpoints déblocables**. Il suffit de marcher dessus pour les activer.  
Ils apparaissent dans le menu **Checkpoints**, où vous pouvez cliquer sur un point de couleur pour vous téléporter.

![image](https://github.com/user-attachments/assets/2474e2e2-876c-4de5-aec5-f1888af73488)

Si vous tombez, vous réapparaissez au dernier checkpoint débloqué. Si aucun n’est débloqué (sauf celui du départ), vous revenez au lit.

> Un checkpoint de base est disponible au début en cas de bugs ou de blocage. 

---

### Style

Vous pouvez changer la couleur des vêtements de votre personnage dans le menu **Style**. Cliquez sur un point coloré pour choisir.  
Pendant que ce menu est ouvert, la caméra tourne autour du joueur pour avoir une vue complète.

![image](https://github.com/user-attachments/assets/08b7f100-edab-4000-8dec-cadb7b1b91fc)

---

### Autres paramètres du menu

- **Sound** : Ajustez le volume avec le curseur, activez/désactivez la musique et les sons via les deux boutons :
  
![image](https://github.com/user-attachments/assets/ca37013e-d6d8-4e66-968d-f4831b45b49e)

- **Help** : Affiche l’aide ainsi que des liens vers le GitHub et une vidéo de gameplay complète :

![image](https://github.com/user-attachments/assets/6c2b260f-6709-4a3e-994b-890674844ba2)

- **Pause** : Stop le chronomètre. Vous pouvez reprendre ou recommencer la partie depuis ce menu :

![image](https://github.com/user-attachments/assets/9436c80e-3abb-4ee6-a33f-ab6f234cb1ec)

---

### Lit

Revenir au lit met le jeu en pause et déclenche une animation de ronflement :

![image](https://github.com/user-attachments/assets/405b8ae1-a78e-4cc1-bbdb-c1b182e25304)

Bougez pour sortir du lit et reprendre le chrono.

---

### Orbes

Les **12 orbes** sont au cœur du gameplay.  
Elles brillent et sont visibles de loin. Vous devrez résoudre des énigmes et franchir des obstacles pour les atteindre :

![image](https://github.com/user-attachments/assets/43fd5d98-6fb0-4cce-b9a0-51245e0b9997)
![image](https://github.com/user-attachments/assets/982d4f27-8ca4-4890-a867-f0def770b0d3)

Pour en collecter une, il suffit de marcher dessus. Elle s’envole alors vers un socle autour du portail :

![image](https://github.com/user-attachments/assets/bb6a9e80-8513-4bfd-a59d-aadad75260c7)

--- 

### Parcours

Le joueur doit activer des éléments, résoudre de petites énigmes ou faire preuve de réflexes.

Types de plateformes :
- **Temporisées** : Apparaissent après pression d’un bouton, disparaissent peu après :

![image](https://github.com/user-attachments/assets/9d0b9378-86c4-493a-bcb1-47e9d3e411f7)

- **Mobiles** : Il faut anticiper leurs mouvements et sauter au bon moment :

![image](https://github.com/user-attachments/assets/ffd3c39b-c539-4b12-bec3-875a0b619412)

- **Fixes** : Souvent combinées à des lasers. Ces laser peuvent parfois avoir un mouvement. Si vous en touchez un, vous serez projetté violement !

![image](https://github.com/user-attachments/assets/901f4692-6856-4e4b-9b6f-8361cbaa9857)

- Petites îles et éléments décoratifs utiles pour atteindre certain endroits :

![image](https://github.com/user-attachments/assets/85602fad-fe1f-42cc-b1d1-a24facc5b73a)


Il y a aussi des gros murs qu'il faut faire disparaître pour aller derrière : allez sur le bouton qui activera le défi. 

![image](https://github.com/user-attachments/assets/94401558-9a94-4c89-ab5c-dfc83d4a7d80)

En marchant sur un bouton, un **mini-jeu de mémoire** démarre :
- Une direction s’allume. Appuyez sur la touche de déplacement correspondante.
- Une nouvelle direction s’ajoute à chaque tour. Reproduisez la séquence complète.
- Les bonnes touches deviennent vertes. Le mur disparaît à la fin.

![image](https://github.com/user-attachments/assets/9ed5a6ba-ba6c-4e66-bdc7-369777676c97)
![image](https://github.com/user-attachments/assets/eeab3f49-8c67-4321-9f53-a552b69d398e)

> [!TIP]
> Si vous êtes bloqué, regardez la [vidéo de complétion](https://www.youtube.com/watch?v=XJVGw6Uxr3U)

---

### Fin du jeu

Une fois les 12 orbes récupérées, une animation se lance et un pont apparaît, reliant l’île de départ au portail.  
Le portail s’active, mais un **dernier défi** vous attend au début du pont.

![image](https://github.com/user-attachments/assets/c5e9372a-a7c8-4ee0-9b42-9f1d40d6f1b9)

Le joueur doit traverser le portail pour terminer le jeu mais un dernier defi est apparu à l'entrée du pont :  

![image](https://github.com/user-attachments/assets/aff66ee7-635d-46b5-8459-2dd65043ded3)



La partie est gagnée si vous traversez le portail avant la fin des 30 minutes : 

![image](https://github.com/user-attachments/assets/00da86af-2569-44b6-b090-b794180cfd20)


Sinon, vous perdez et voyez un écran d’échec :

![image](https://github.com/user-attachments/assets/7caf828d-1082-45a1-bc2d-f40287f2cc01)


---

### Menu développeur

Appuyez sur **i** pour ouvrir/fermer le **menu de debug développeur** : 

![image](https://github.com/user-attachments/assets/ef58c781-f34d-4b8f-8a63-fd8b60fd1c55)

Maintenez **Shift** pour déplacer la camera avec la souris.
Vous pouvez y expérimenter et déplacer des éléments librement — voire tricher !  
Ce menu a été ajouté avec BABYLON pour aider au placement pendant le développement.  
Nous l’avons conservé car il est amusant et peut aider les joueurs bloqués.

## 🧱 Assets

### Modèles 3D

Tous les modèles 3D ont été créés par l’équipe avec **Blender**, sauf les formes simples (plateformes, boutons, lasers...) faites directement avec **BABYLON**.  
Les animations viennent de [Mixamo](https://www.mixamo.com/#/).

Le style de chaque modèle a été conçus pour être cohérents avec le style général et simple pour avoir un jeu optimisés pour le web.

---

### Textures

Le jeu utilise peu de textures :  
- Les plateformes et murs partagent une base modifiée dans Gimp :

![platform](https://github.com/user-attachments/assets/017a8a4d-1cb9-4877-a827-6e103b18c50b)
![buttonInvis](https://github.com/user-attachments/assets/3bf2143b-5e36-4f5a-9c46-e7ce4b4208a8)
![platformLaser](https://github.com/user-attachments/assets/832f96ab-48b9-43a8-a9b8-9730b1cbe947)
![platformInvis](https://github.com/user-attachments/assets/3ac86229-92f5-4bed-aabf-6ce12844f96f)
![plateformMove](https://github.com/user-attachments/assets/f8da5b4a-d7bd-4ee7-9757-d201dd3ff295)
![buttonSimon](https://github.com/user-attachments/assets/841d6203-e301-4547-a1e2-bd31d042e4c1)

- Les îles, le portail, les orbes, le pont final, les lampes, les socles de checkpoints et bancs utilisent une section du même `gradient.png` :

![gradient](https://github.com/user-attachments/assets/6171f730-c72e-4325-a1ee-77fc01d0c3cc)


- Le ciel a été fait sur Gimp :

![ciel2](https://github.com/user-attachments/assets/e0dddc61-0085-46d6-ab49-2966a0e71cbd)

- L'intérieur du portail :

![portail](https://github.com/user-attachments/assets/95f81d0c-34b1-4bf3-9657-3026ec9aaa38)

Tous les autres éléments ont une couleur uni.
Le glow et les ombres apportent déjà de la profondeur visuelle sans surcharge

---

### Sons et musique

Tous les effets sonores sont libres et viennent de YouTube (copyright-free).  
Musique principale : [https://youtu.be/zjTyprOLMxo?si=DbDfk77EcCsBjdC_](https://youtu.be/zjTyprOLMxo?si=DbDfk77EcCsBjdC_)  

---

## English Version

### General

**DREAM'SCAPE** is a first-person 3D adventure game playable in a browser.  
You play as a student trapped in a strange dream filled with floating islands, mechanisms, and puzzles.  
Your goal: **collect 12 scattered orbs** in the world to activate the final portal and escape **within the time limit (30 minutes)**.  
The game features platforming, logic, and observation mechanics, with a free progression between zones.

Click on **Play** to launch the game. After loading, the **Help** menu appears. Click outside the Help panel to close it.

![image](https://github.com/user-attachments/assets/e4c9f694-2fa2-45b3-9f6b-1b37413a9e04)

You start in a bed on the starting island. To control the player and camera, click on the screen to hide the mouse.  
The timer starts once you leave the bed. Remaining time is shown at the bottom. Good luck!

---

### Controls

- **ZQSD** – Movement
- **Space** – Jump
- **Shift** – Sprint (hold)
- **Mouse** – Camera look
- **Mouse wheel** – Zoom in/out
- **Left click** – Locks cursor for gameplay
- **ESC or click again** – Unlocks cursor

Keybindings can be modified via the **Controls** menu. Click on the action button, then press a new key.  
Camera sensitivity can also be adjusted.

![image](https://github.com/user-attachments/assets/e408f429-8a16-4b23-820e-5fa26098829f)

---

### Checkpoints

The world is built around **paths leading to different zones**, each containing several orbs.  

There are 12 **glowing pedestals** acting as **unlockable checkpoints**. Just step on one to activate it.  
They appear in the **Checkpoints** menu, where you can click a color dot to teleport.

![image](https://github.com/user-attachments/assets/2474e2e2-876c-4de5-aec5-f1888af73488)

If you fall, you'll respawn at the last unlocked checkpoint. If none are unlocked yet (except the default one), you respawn in bed.

> A default checkpoint is available at the start in case of bugs or being stuck.

---

### Style

You can change your player's clothing colors from the **Style** menu. Click on the color dot to choose a color.

While the style menu is open, the camera rotates around the player for a full view.

![image](https://github.com/user-attachments/assets/08b7f100-edab-4000-8dec-cadb7b1b91fc)

---

### Other Menu Settings

- **Sound**:  
  Adjust the volume with the slider, toggle music and sounds via the two buttons.

![image](https://github.com/user-attachments/assets/ca37013e-d6d8-4e66-968d-f4831b45b49e)

- **Help**:  
  Displays help and links to the GitHub and a full gameplay video.

![image](https://github.com/user-attachments/assets/6c2b260f-6709-4a3e-994b-890674844ba2)

- **Pause**:  
  Freezes time. You can continue or restart the game from here.

![image](https://github.com/user-attachments/assets/9436c80e-3abb-4ee6-a33f-ab6f234cb1ec)

---

### Bed

Going back to the bed pauses the game and triggers a snoring animation.  

![image](https://github.com/user-attachments/assets/405b8ae1-a78e-4cc1-bbdb-c1b182e25304)

Move to get out of bed and resume the timer.

---

### Orbs

The **12 orbs** are the core gameplay.  
They glow and are visible from afar. You'll need to solve puzzles and complete platforming to reach them.

![image](https://github.com/user-attachments/assets/43fd5d98-6fb0-4cce-b9a0-51245e0b9997)
![image](https://github.com/user-attachments/assets/982d4f27-8ca4-4890-a867-f0def770b0d3)

To collect one, just walk over it. It will fly to a pedestal around the portal.

![image](https://github.com/user-attachments/assets/bb6a9e80-8513-4bfd-a59d-aadad75260c7)

---

### Parkour

Players must activate elements, solve small puzzles, or use timing skills.

Types of platforms:
- **Timed**: Appear after pressing a button, disappear shortly after.

![image](https://github.com/user-attachments/assets/9d0b9378-86c4-493a-bcb1-47e9d3e411f7)

- **Moving**: You must predict their movement and jump at the right time.

![image](https://github.com/user-attachments/assets/ffd3c39b-c539-4b12-bec3-875a0b619412)

- **Fixed**: Often combined with lasers. Touching a laser will launch you back.

![image](https://github.com/user-attachments/assets/901f4692-6856-4e4b-9b6f-8361cbaa9857)

- Little islands and decorative elements seful for exploration and reaching areas.

![image](https://github.com/user-attachments/assets/85602fad-fe1f-42cc-b1d1-a24facc5b73a)

There are also large walls hiding areas.  

![image](https://github.com/user-attachments/assets/94401558-9a94-4c89-ab5c-dfc83d4a7d80)

Step on a button to trigger a **memory mini-game**:  
- A direction lights up. Press the corresponding movement key.
- A new direction is added each round. Repeat the full sequence.
- Correct inputs turn green. The wall disappears once all rounds are done.

![image](https://github.com/user-attachments/assets/9ed5a6ba-ba6c-4e66-bdc7-369777676c97)
![image](https://github.com/user-attachments/assets/eeab3f49-8c67-4321-9f53-a552b69d398e)

> [!TIP]  
> If you're stuck, watch the [completion video](https://www.youtube.com/watch?v=XJVGw6Uxr3U)

---

### End of the Game

When all 12 orbs are collected, an animation plays and a bridge appears linking the start island to the portal.  

![image](https://github.com/user-attachments/assets/c5e9372a-a7c8-4ee0-9b42-9f1d40d6f1b9)

The portal activates, but a **final challenge** awaits at the bridge’s entrance.

![image](https://github.com/user-attachments/assets/aff66ee7-635d-46b5-8459-2dd65043ded3)


The game is won if you cross the portal before the 30-minute timer runs out. 

![image](https://github.com/user-attachments/assets/00da86af-2569-44b6-b090-b794180cfd20)

If time runs out before that, you lose and see a fail screen.

![image](https://github.com/user-attachments/assets/7caf828d-1082-45a1-bc2d-f40287f2cc01)

---

### Developer Menu

Press **i** to toggle the **developer debug menu**.

![image](https://github.com/user-attachments/assets/ef58c781-f34d-4b8f-8a63-fd8b60fd1c55)

Use **Shift** to move the camera.
You can experiment and move elements freely — even cheat!  
This menu was added with BABYLON to help place objects during development.  
We kept it because it’s fun and can help players who get stuck.

---

## 🧱 Assets

### 3D Models

All 3D models were created by the team using **Blender**, except simple shapes (platforms, buttons, lasers...) made directly with **BABYLON**.  
Animations are from [Mixamo](https://www.mixamo.com/#/).

The style was chosen for consistency and browser performance.

---

### Textures

The game uses minimal textures:

- Platforms and walls use the same base texture modified in Gimp:

![platform](https://github.com/user-attachments/assets/017a8a4d-1cb9-4877-a827-6e103b18c50b)
![buttonInvis](https://github.com/user-attachments/assets/3bf2143b-5e36-4f5a-9c46-e7ce4b4208a8)
![platformLaser](https://github.com/user-attachments/assets/832f96ab-48b9-43a8-a9b8-9730b1cbe947)
![platformInvis](https://github.com/user-attachments/assets/3ac86229-92f5-4bed-aabf-6ce12844f96f)
![plateformMove](https://github.com/user-attachments/assets/f8da5b4a-d7bd-4ee7-9757-d201dd3ff295)
![buttonSimon](https://github.com/user-attachments/assets/841d6203-e301-4547-a1e2-bd31d042e4c1)

- Islands, portal, orbs, final bridge, lamps, checkpoint pedestals, benches use a section of the same `gradient.png` :

![gradient](https://github.com/user-attachments/assets/6171f730-c72e-4325-a1ee-77fc01d0c3cc)

- Skybox created in Gimp:

![ciel2](https://github.com/user-attachments/assets/e0dddc61-0085-46d6-ab49-2966a0e71cbd)

- Portal interior:

![portail](https://github.com/user-attachments/assets/95f81d0c-34b1-4bf3-9657-3026ec9aaa38)

Other elements use solid colors
Glow effects and shadowing add depth.

---

### Sounds and Music

All sound effects are free and sourced from YouTube (copyright-free).  
Main music: [https://youtu.be/zjTyprOLMxo?si=DbDfk77EcCsBjdC_](https://youtu.be/zjTyprOLMxo?si=DbDfk77EcCsBjdC_)

---

