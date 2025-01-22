# Synoptique
```mermaid
flowchart TD
    n1["Power"] --> n2["Speaker x 4"]
    n1 -- Câble Ethernet --> n3["Ordinateur"]
    n3 --> n10["Écran, Clavier et Souris"]
    n3 -- Connecteur USB --> n11["Carte&nbsp; de Son"]
    n4["M5Atom"] --> n13["Ordinateur"] & n3
    n7["Power"] --> n8["Projecteur"] & n9["Lumière 5PX-Hex"]
    n9 -- Câble XLR/USB --> n3
    n11 -- Câble XLR --> n2
    n16["M5Atom"] --> n13 & n3
    n14["M5Atom"] --> n13 & n3
    n13 --> n10
    n15["Tof Unit x5"] --> n18(["PBHub"])
    n18 --> n14
    n5["Tof Unit x5"] --> n19(["PBHub"])
    n17["Tof Unit x5"] --> n20(["PBHub"])
    n19 --> n16
    n20 --> n4
    n3 -- Cable HDMI --> n8

    n1@{ shape: rounded}
    n2@{ shape: rect}
    n3@{ shape: diam}
    n13@{ shape: diam}
    n7@{ shape: rounded}
    n16@{ shape: rect}
    n14@{ shape: rect}
    n15@{ shape: rect}
    n17@{ shape: rect}
    style n1 stroke:#D50000,fill:#D50000,color:#FFD600
    style n2 stroke:#0288D1,fill:#0288D1,color:#FFFFFF
    style n3 fill:#616161,color:#FFFFFF
    style n13 fill:#616161,color:#FFFFFF
    style n7 fill:#D50000,color:#FFD600
    style n10 fill:#43A047,color:#FFFFFF
    style n11 fill:#FF9800,color:#FFFFFF
    style n8 fill:#8E24AA,color:#FFFFFF
    style n9 fill:#8E24AA,color:#FFFFFF
    style n16 fill:#0288D1,color:#FFFFFF
    style n14 fill:#0288D1,color:#FFFFFF
    style n15 fill:#FF5722,color:#FFFFFF
    style n17 fill:#FF5722,color:#FFFFFF
    style n18 fill:#9C27B0,color:#FFFFFF
    style n19 fill:#9C27B0,color:#FFFFFF
    style n20 fill:#9C27B0,color:#FFFFFF

```

## Références

* [Synoptique](https://tim-montmorency.com/582523-gestion/#/contenus/3_planification/10_synoptique/)

