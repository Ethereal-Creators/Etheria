# Scénario

<!-- Ici mettre tous les documents et références concernant la scéanrisation de l'expérience   -->
<!--
* Tous les verbes disponibles à vos interacteurs

* Tous les objets sur lesquels chaque verbe peut agir et comment ils le font

* Actions émergentes que vous aimeriez que vos interacteurs effectuent

* Toutes les façons que les interacteurs peuvent faire progresser l’expérience-->

```mermaid
graph TD

    x[Intéracteur] --> id1{Interaction avec les figures?}
    id1 --Non--> A[Retour en mode veille]
    id1 --Oui--> B[Commencement du jeu] 
    B --> id2{Utiliser la figure pour attaquer?}
    id2 --Non--> M{Pierre protégé ?}
    id2 --Oui--> M
    M --Oui--> K[Prochaine Manche]
    M --Non--> U[Terminer]
    K --> id2
    U --> B
    A --> x
```

## Progression
Chaque utilisateur fait progresser l'expérience en jouant à tour de rôle avec les les cartes qui sont placés devant eux qui ajoute des sons et des effets pour leur donner un produit final qui leur est satisfaisant lorsqu'elles sont détectées.

<!--
## Références

* [Scénario Interactif](https://tim-montmorency.com/582523-gestion/#/contenus/2_scenarisation/20_scenario/20_interactif/)
* [Expérience usager UX](https://tim-montmorency.com/582523-gestion/#/contenus/2_scenarisation/20_scenario/40_ux/)-->

