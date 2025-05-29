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
- Des plateformes qui apparaissent après l'activation d'un bouton. Elle disparaissent peu de temps apres donc il faut être rapide !
- Des plateformes qui se déplace. Il faut bien viser et prédir où sera la plateforme pour ne pas tomber dans le vide !
- Des plateformes fixes, souvent accompagné de laser.
- Des petites îles et des éléments décoratifs utiles pour atteindre certain endroits.

Les laser peuvent parfois avoir un mouvement. Si vous en touchez un, vous serez projetté violement !


---

### Fin du jeu

Quand les 12 orbes ont été récupérées, un **portail de sortie** s’active dans la zone centrale.  
Le joueur doit s’y rendre pour terminer le jeu avant la fin du compte à rebours de 30 minutes.  
Une cinématique finale est déclenchée.

---

## 🧱 Assets

### Modèles 3D

Tous les modèles 3D ont été réalisés par l’équipe dans **Blender**, incluant :
- Îles, plateformes, piliers
- Orbes, socles de checkpoint
- Portail final
- Boutons, interrupteurs, lasers, murs

Les modèles ont été conçus pour être **cohérents visuellement** et optimisés pour le web.

---

### Textures

Le style utilise peu de textures :  
- Couleurs unies (via matériaux Babylon.js)
- Quelques éléments émissifs pour les lumières et effets brillants
- Le glow et les ombres apportent la profondeur visuelle sans surcharge

---

### Sons et musique

Les sons ont été ajoutés pour renforcer l’immersion :
- Sons d’interaction (boutons, orbes, portail)
- Ambiance de fond discrète
- Aucun bruitage inutile, afin de garder un ton calme et mystérieux

Les sons sont stockés localement dans le projet et joués avec le système audio Babylon.js.

---


