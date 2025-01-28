# Scénario

<!-- Ici mettre tous les documents et références concernant la scéanrisation de l'expérience   -->
<!--
* Tous les verbes disponibles à vos interacteurs

* Tous les objets sur lesquels chaque verbe peut agir et comment ils le font

* Actions émergentes que vous aimeriez que vos interacteurs effectuent

* Toutes les façons que les interacteurs peuvent faire progresser l’expérience-->

```mermaid
graph TD
    A[Retour en mode veille] --> x[Menu]
    x --> B[Commencer]
    x --> N[Quitter]
    B --> id1{Interaction avec les figures?}
    id1 --Non--> B
    id1 --Oui--> F[Résultat sur l'écran]
    F --> id2{Plus d'interaction avec figure?}
    id2 --Non--> M[Progression phase attaque]
    id2 --Oui--> F
    M --> id3{Tour d'agir?}
    id3 --Oui--> K[Agir]
    id3 --Non--> id3
    K --> id4{Fin de partie?}
    id4 --Oui--> U[Terminer]
    id4 --Non--> id3
    U --> H[Recommencer]
    H --> x
    U --> N
    N --> A
```

## Progression
Chaque utilisateur fait progresser l'expérience en jouant à tour de rôle avec les les cartes qui sont placés devant eux qui ajoute des sons et des effets pour leur donner un produit final qui leur est satisfaisant lorsqu'elles sont détectées.

<!--
## Références

* [Scénario Interactif](https://tim-montmorency.com/582523-gestion/#/contenus/2_scenarisation/20_scenario/20_interactif/)
* [Expérience usager UX](https://tim-montmorency.com/582523-gestion/#/contenus/2_scenarisation/20_scenario/40_ux/)-->

