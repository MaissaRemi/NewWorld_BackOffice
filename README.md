> **Projet d'école** — BTS SIO, février → avril 2022.
> Dépôt conservé en l'état à titre d'archive : le code n'a pas été retouché depuis et ne reflète pas mes pratiques actuelles.

# NewWorld — Back-office

Application de bureau du back-office de la plateforme de circuit court **NewWorld** :
consultation du registre des producteurs, validation ou refus des demandes d'inscription,
suivi des visites d'exploitation.

## Stack

- C++ / Qt Widgets (`.pro`, formulaires `.ui`)
- MySQL

## Composants

| Fichier | Rôle |
|---|---|
| `connexion.*` | Écran de connexion |
| `mainwindow.*` | Fenêtre principale et registre des producteurs |
| `producteurrefuser.*` | Traitement des demandes refusées |

## Projets liés

- [NewWorld_CircuitCourt](https://github.com/MaissaRemi/NewWorld_CircuitCourt) — couche métier C++
- [NewWorld_Inscription](https://github.com/MaissaRemi/NewWorld_Inscription) — formulaire d'inscription web
