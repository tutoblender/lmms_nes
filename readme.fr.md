[Version original](https://github.com/tutoblender/lmms_nes)

![Thumbnail](https://github.com/tutoblender/lmms_nes/raw/master/doc/thumbnail_instructables.png)
LMMS propose un module nommée **Nescaline** qui permet de reproduire le son d'une NES.
Nous allons voir comment utiliser ce logiciel pour faire des musiques dans le style 8bit.

* Tout d'abord nous allons récupérer une session LMMS prête à être utilisé
* Puis nous allons apprendre à créer une pattern
* Pour finir, nous verrons comment créer une musique

Video: https://www.youtube.com/watch?v=BVlNJcDRlbo

# Session pour la nes
Nous allons utiliser une session toute prête.
* Télécharger **LMMS** : https://lmms.io/
* Télécharger http://nes.madnerd.org
* Ouvrez **nes.mmpz**

# Interface de LMMS
Regardons l'interface de LMMS, nous avons 
* Le Piano Roll    
Le piano roll permet de créer une pattern, un **ensemble de notes**
* L'Editeur de Morceau (Song-Editor)    
Chaque pattern peut être réutilisé dans l'éditeur de morceau afin de créer notre musique.
* Le FX Mixer    
Chaque instruments est assigné à une chaine sur la table de mixage, vous pouvez ici régler le volume.
* Les instruments     
Chaque instrument peut être modifié, Cliquer sur CH1/CH2/CH3/CH4 dans l'éditeur de morceau pour les afficher

![FX Mixer](https://github.com/tutoblender/lmms_nes/raw/master/doc/fxmixer.png)     
Ici nous avons **4 instruments**, elles représentent les **4 channels** de notre **nes**
(Il y en a une 5ème channel pour les sons digitalisés)
* CH1 / CH2 produit des **pulse wave**, elles sont utilisés pour **la mélodie**
* CH3 produit des **triangle wave**, elles sont utilisés pour **la basse**
* CH4 produit du **noise**, elles sont utilisés pour **les percussions**
Pour plus d'informations, allez voir ces deux vidéos sur youtube!
Source: https://www.youtube.com/watch?v=la3coK5pq5w
Source: https://www.youtube.com/watch?v=q_3d1x2VPxk

# Piano Roll : Créer une pattern
![Song Editor](https://github.com/tutoblender/lmms_nes/raw/master/doc/songeditor.png)    
Pour créer une pattern, dans **l'éditeur de morceau** : 
* Cliquez sur une case vide
* Double-cliquez dessus pour l'afficher dans le **piano roll**

![Piano roll](https://github.com/tutoblender/lmms_nes/raw/master/doc/piano-roll.png)   
Vous pouvez maintenant créer votre pattern dans le piano roll.
* Créer une note: Cliquer dans le **vide**
* Déplacer une note: Cliquer sur la **note**
* Rallonger/Réduire une note: Cliquer sur le bord droit de la note 
* Jouer la pattern : Barre d'espace

# Editeur de morceau : Créer une musique
![Play](https://github.com/tutoblender/lmms_nes/raw/master/doc/play.png) 
Afin d'écouter plusieurs patterns en même temps:
Cliquer sur **l'éditeur de morceau** et appuyer sur la **Barre d'espace**

## Créer une boucle
![Loop](https://github.com/tutoblender/lmms_nes/raw/master/doc/loop.png) 
Le morceau ne se répétera pas, vous devez créer une boucle pour ça.
* Activer la boucle : Clic gauche sur les deux triangles verts (Enable/Disable loop points)
* Déplacer le début : Bouton du milieu 
* Déplacer la fin : Clic droit

## Copier/Coller une pattern
![Copy-Paste](https://github.com/tutoblender/lmms_nes/raw/master/doc/copypaste.png) 
* Cliquez sur une **case vide**
* Clic droit sur la **pattern** / Copier
* Clic droit sur la **case** / Coller

Vous pouvez **effacer une pattern** avec le **bouton du milieu**

# Modifier les instruments
![CH1](https://github.com/tutoblender/lmms_nes/raw/master/doc/ch1.png)     
![CH2](https://github.com/tutoblender/lmms_nes/raw/master/doc/ch2.png)     
![CH3](https://github.com/tutoblender/lmms_nes/raw/master/doc/ch3.png)     
![CH4](https://github.com/tutoblender/lmms_nes/raw/master/doc/ch4.png)     
Essayer de modifier les instruments, chaque channel est sur une ligne.

* VOL : Volume
* CRS : Accordage (tuning) par incrément de 1 note (1 --> C3 devient D3)
* ENV/LEN : Réduit la durée de la note
* Width : Change le son généré
* ∞ : Tant que la note dure elle sera répété
* Sweep/AMT/Rate : La hauteur de la note augmente progressivement
* Note : Le son change selon la note
* Mode : Son plus métallique


Voilà pour les bases, j'espère que cela vous aura inspiré à créer de la musique old-school.

![Shortcuts](https://github.com/tutoblender/lmms_nes/raw/master/doc/lmms_shortcuts.png) 