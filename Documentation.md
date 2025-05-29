![image](https://github.com/user-attachments/assets/3a5f2105-a456-479a-9766-ce5cf4f36928)

# Documentation

## Sommaire :
- #### Description détaillée du jeu
  - [Général](#general)
  - [Controls](#controls)
  - [Checkpoints](#checkpoints)
  - [Style](#style)
  - [Menu](#menu)
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
![image](https://github.com/user-attachments/assets/e4c9f694-2fa2-45b3-9f6b-1b37413a9e04)

---

### Controls

- **ZQSD** – Déplacement
- **Espace** – Saut
- **Shift** – Courir
- **Souris** – Orientation de la caméra
- **Molette** – Zoom avant/arrière
- **Clic gauche** – Verrouille le curseur pour jouer (pointer lock)
- **ECHAP ou clic à nouveau** – Affiche le curseur

Les touches sont modifiables via le menu.

![image](https://github.com/user-attachments/assets/e408f429-8a16-4b23-820e-5fa26098829f)
![image](https://github.com/user-attachments/assets/2474e2e2-876c-4de5-aec5-f1888af73488)

![image](https://github.com/user-attachments/assets/08b7f100-edab-4000-8dec-cadb7b1b91fc)
![image](https://github.com/user-attachments/assets/ca37013e-d6d8-4e66-968d-f4831b45b49e)
![image](https://github.com/user-attachments/assets/9436c80e-3abb-4ee6-a33f-ab6f234cb1ec)


---

### Checkpoints

Le monde est structuré autour de **chemins menant à différentes zones**, chacune contenant un orbe.  
Des **socles lumineux** font office de **checkpoints déverrouillables** : une fois activés, ils permettent de se téléporter à une zone directement depuis le menu ou l’interface HUD.

---

### Style

Le style graphique est minimaliste mais cohérent :  
- Univers nocturne et spatial
- Îles géométriques et éléments brillants
- Ambiance onirique, renforcée par l’éclairage dynamique et les effets de glow

Tous les éléments visuels sont originaux et ont été créés en 3D spécifiquement pour ce projet.

---

### Menu

Le menu permet :
- De lancer une nouvelle partie
- De reconfigurer les touches
- D'ajuster les paramètres visuels (glow, résolution, affichage FPS)
- De changer la qualité d’affichage
- De retourner à un checkpoint débloqué

Une **interface HUD** simple est également affichée en jeu : temps restant, nombre d’orbes collectées, options.

---

### Parcours

Chaque zone du jeu propose un **type de challenge différent** :
- Sauts de plateforme en temps limité
- Plateformes invisibles
- Lasers et obstacles mobiles
- Murs, leviers, ascenseurs

Le joueur doit parfois activer des éléments pour progresser, résoudre de petites énigmes ou faire preuve de précision.

---

### Orbes

Les **12 orbes** sont le cœur du gameplay.  
Elles sont visibles de loin et placées dans des lieux accessibles uniquement après avoir complété les parcours.

![image](https://github.com/user-attachments/assets/43fd5d98-6fb0-4cce-b9a0-51245e0b9997)
![image](https://github.com/user-attachments/assets/982d4f27-8ca4-4890-a867-f0def770b0d3)

![image](https://github.com/user-attachments/assets/bb6a9e80-8513-4bfd-a59d-aadad75260c7)
![image](https://github.com/user-attachments/assets/405b8ae1-a78e-4cc1-bbdb-c1b182e25304)

Lorsque le joueur s’en approche, un effet visuel et sonore est déclenché.  
Une fois l’orbe collectée, elle disparaît et s’ajoute à l’interface.

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


