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
    x --> B[commencer]
    x --> N[quitter]
    B --> C[Interaction]
    C --> F[résultat sur l'écran]
    F --> M[progression phase attaque]
    M --> U[Terminer]
    U --> H[recommencer]
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

