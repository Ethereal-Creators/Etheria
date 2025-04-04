# Joshua Gonzalez-Barrera

<!--<img src="./josh_00000.jpg" alt="josh" width="720"/>-->
![Josh](./josh_00000.jpg)

 ## Réalisations

 <!-- Une image par semaine de la réalisation dont tu es le plus fier avec une légende -->
### Semaine 1
Reconception du projet, refaire le github au complet. Notre idée principale n'était pas si bonne, donc est retourné à la case départ. Avec mon équipe, j'ai écrit notre nouvel concept de projet, en ajoutant le plus de détails possibles et de décrire l'expérience dans la vision de l'intéracteur. Nous avons eu l'autorisation de continuer avec cette idée.

![Nouveau Texte](../../Assets/images/images_doc_joshua/nouveauText.jpg)

### Semaine 2
Production de la vidéo explicative sur After Effects. Je suis allé pour une approche inspiré par les types de vidéos explicatives avec des graphiques que j'ai vue sur Youtube. J'ai aussi séparé le contenu pour faciliter la compréhension du projet. J'ai écrit le script pour la partie explication et donné des repères pour mes coéquipiers pour leurs enregistrements.

![Script_Général](../../Assets/images/images_doc_joshua/scriptGeneral.jpg)


![Script Explication](../../Assets/images/images_doc_joshua/scriptExplication.jpg)


![Montage Vidéo sur After Effects](../../Assets/images/images_doc_joshua/montage_etheria.jpg)


!["Making Of" de la vidéo explicative](../../Assets/images/images_doc_joshua/montage_video.jpg)


### Semaine 3 
Correction de la vidéo explicative au demandes du professeurs (sous-titres sur Youtube directement / couper certaines parties de la partie équipe / mettre les sources / avoir un titre approprié pour Youtube).
![Sous_Titres](../../Assets/images/images_doc_joshua/soustitres.jpg)

#### Commencement de quelques assets

![Arbre](../../Assets/images/images_doc_joshua/tree.png) 

![Explosion Normal](../../Assets/images/images_doc_joshua/explosion.gif)

![Explosion Magique](../../Assets/images/images_doc_joshua/explosion_magic.gif)


#### Début de la réalisation de l'espace.

![Maquette_projecteurs](../../Assets/images/images_doc_joshua/InstallationMaquette.jpg)

### Semaine 4
#### Structure de la maquette
Finalisation de la structure de la maquette, de plus en équipe nous avons connectés les haut-parleurs et testé le son. 
![Début_installation_audio](../../Assets/images/images_doc_joshua/audioInstallation.jpg)

#### Animations états du jeu
Sur After Effects, j'ai créer les animations pour les états du jeu, j'ai premièrement essayé de les mettre sur "greenscreen", mais en voyant que cela allait pas marcher avec un shader en ligne, j'ai décidé de faire un rendu en PNG pour ensuite rendre les animations en sprites. 

![Animation Succès](../../Assets/images/images_doc_joshua/animationSucces.gif)

#### Menu
J'ai aussi fait le "start menu" pour le jeu, la première scène avant que le jeu commence. J'ai créer un script pour qu'au contact d'un cube, le jeu nous transporte dans la scène de jeu.
```
using System.Collections;
using System.Collections.Generic;
using UnityEngine;
using UnityEngine.SceneManagement;

public class startGame : MonoBehaviour
{
    
    public void OnTriggerEnter2D(Collider2D obj) {
        Debug.Log("Collision");
        SceneManager.LoadScene("test01_OSC");
    }

}
```
J'ai intégrer l'OSC dans la scène Menu et ensuite créé des animations différentes pour attirer l'intéracteur vers le projet et l'aider en changeant l'opacité de l'instruction

![Animations menu](../../Assets/images/images_doc_joshua/etheriaMenu.jpg)

### Semaine 5

- Remise de la maquette
- Avancement des assets "crystal" et extra
- Corriger ce que les commentaires des profs

![Crystal 25%](../../Assets/images/images_doc_joshua/crystal_25-Sheet.png)

![Crystal 50%](../../Assets/images/images_doc_joshua/crystal_50-Sheet.png)

![Crystal 75%](../../Assets/images/images_doc_joshua/crystal_75-Sheet.png)

### Semaine 6

#### Nouveau power up créer pour le paladin et le mage.

![Pouvoir Mage](../../Assets/images/images_doc_joshua/powerBeam_mage.gif)

![Pouvoir Paladin](../../Assets/images/images_doc_joshua/power_slash.gif)

#### Kinect et Cable Management

On a installé la Kinect. Grâce au Raspberry Pi de Guillaume, on peut maintenant se connecter à lui à distance. De plus, on a installé des lumières infrarouges pour améliorer la visibilité de la Kinect. Enfin, j'ai essayé d'améliorer la gestion des câbles de la structure en haut, qui en avait vraiment besoin.

![Cable Management](../../Assets/images/images_doc_joshua/cableManage.jpg)

![Cable Managemenet 2](../../Assets/images/images_doc_joshua/cableManage2.jpg)

#### Animation Chargement

Création d'une nouvelle animation de chargement

![Animation Chargement](../../Assets/images/images_doc_joshua/animationLoading.png)

### Semaine de rattrapage

#### Amélioration des scènes 03 et 04 (Changement de texture, placement des pouvoirs, etc.)

![Vague 03](../../Assets/images/images_doc_joshua/Scene06Box.png)

![Vague 04](../../Assets/images/images_doc_joshua/Scene07Box.png)


### Semaine 7

#### Montage Vidéo Bande Annonce

J'ai fini le montage de la vidéo bande annonce.

![Bande Annonce Montage](../../Assets/images/images_doc_joshua/annonceEdit.png)

#### Changement niveau

On a également décidé de réduire le nombre de niveaux à 6 au lieu de 10. On a constaté que 10 niveaux étaient trop nombreux et qu'on pouvait intégrer les différentes méthodes de progression sans rendre le jeu trop long.

#### Création d'un nouveau indicateur pour le menu

![Indicateur Menu](../../Assets/images/images_doc_joshua/squareIndicator-Sheet.png)

#### Animation Manche

J'ai aussi créer des nouvelles animations pour les manches différentes (1-6).

![Manche Différente](../../Assets/images/images_doc_joshua/mancheDif.png)

#### Amélioration Table et Pions

J'ai installé les lumières en dessous la table. L'équipe est aussi allé acheter tout ce qui était nécessaire pour le projet, incluant des herbes/girlandes comme décoration et une texture pour permettre au pion de bien glisser sur la table. Je l'ai ensuite installé.

![Lumière en dessous de la table](../../Assets/images/images_doc_joshua/lumiereEndessous.jpg)

![Texture Pion](../../Assets/images/images_doc_joshua/ajoutTexture.jpg)

#### Création déco desert (Eau)

![Eau](../../Assets/images/images_doc_joshua/waterr.gif)


### Semaine 8 

#### Making Of

Finition de la bande annonce et le making of.

![Montage Making Of](../../Assets/images/images_doc_joshua/makingOfEdit.png)

![Script Making Of](../../Assets/images/images_doc_joshua/scriptMaking.png)


