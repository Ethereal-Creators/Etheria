# Scénario

<!-- Ici mettre tous les documents et références concernant la scéanrisation de l'expérience   -->

* Tous les verbes disponibles à vos interacteurs

* Tous les objets sur lesquels chaque verbe peut agir et comment ils le font

* Actions émergentes que vous aimeriez que vos interacteurs effectuent

* Toutes les façons que les interacteurs peuvent faire progresser l’expérience

```mermaid
graph TD
    A[L'utilisateur rentre dans la la salle] --sons d'ambiance et lumière ambiante--> B[la distance affect le sons]
    B[un des 3 cubes est touché] -- le niveau de lumière affect un paramètre de l'ambiance --> C[la distance affect le sons]
    B --le niveau de lumière affect un paramètre de l'ambiance --> D[la distance affect le sons]
    B --le niveau de lumière affect un paramètre de l'ambiance --> E[la distance affect le sons]
    C --> F[l'utilisateur quitte la pièce]
    D --> F[l'utilisateur quitte la pièce]
    E --> F[l'utilisateur quitte la pièce]
    F --> A
```

## Références

* [Scénario Interactif](https://tim-montmorency.com/582523-gestion/#/contenus/2_scenarisation/20_scenario/20_interactif/)
* [Expérience usager UX](https://tim-montmorency.com/582523-gestion/#/contenus/2_scenarisation/20_scenario/40_ux/)

