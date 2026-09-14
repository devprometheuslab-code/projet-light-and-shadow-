# 03 — Armées et sièges

## Vue d'ensemble

La guerre RvR s'appuie sur des **armées data-driven** : les troupes sont définies dans des tables de données (voir [Systèmes backend](../06_ETAT_DU_PROJET/03_systemes_backend.md)), ce qui permet d'équilibrer et d'étendre le système sans toucher au code.

---

## Types de troupes

| Type | Rôle |
|---|---|
| **Infanterie** | Ligne de front, tenue de position |
| **Archers** | Dégâts à distance |
| **Cavalerie** | Charge, mobilité, écrasement des lignes légères |
| **Machines de siège** | Destruction des fortifications |
| **Mages** | Soutien magique, dégâts de zone |
| **Soigneurs** | Maintien des troupes en vie |
| **Espions** | Renseignement et sabotage |

---

## Système de contres

Les troupes se contrent mutuellement, à la manière d'un pierre-feuille-ciseaux militaire :

| Contre | Effet |
|---|---|
| **Piquiers > Cavalerie** | Les piquiers brisent les charges de cavalerie |
| **Cavalerie > Archers** | La cavalerie écrase les lignes d'archers |

Ce système force la **composition d'armée** et la lecture du champ de bataille : on ne gagne pas en empilant une seule unité.

---

## Saveurs par royaume

Chaque royaume aligne des troupes à sa saveur :

| Royaume | Troupes emblématiques |
|---|---|
| **Cœur-Sylvain (Lumière)** | Archers, rangers |
| **Crête-Éternelle (Neutre)** | Arbalétriers nains, marteleurs (hammerers) |
| **Plaie-d'Ombre (Ombre)** | Soldats-esclaves, morts-vivants |

> ⚠️ **Recruter des esclaves fait chuter le karma** — voir [Karma Lumière/Ombre](../03_SYSTEMES_DE_JEU/01_karma_lumiere_ombre.md). L'efficacité militaire de l'Ombre a un prix moral que le monde retient.

---

## Économie de guerre

La guerre se paie et se gère via trois leviers (voir [Système féodal](02_systeme_feodal.md)) :

| Levier | Description |
|---|---|
| **Taxes** | Revenus tirés des fiefs pour financer les armées |
| **Fortification** | Investissement dans les défenses des places |
| **Contentement paysan** | Une population pressurée peut **se révolter** — taxer aveuglément fragilise l'arrière |

---

## Sièges

Les sièges sont le point culminant militaire :

- Introduits en campagne par **Le Grand Siège** (Acte II) — voir [Acte II](../04_CAMPAGNE/03_acte_2_guerre.md).
- En endgame, ils permettent de prendre les forts de la frontière contestée — voir [RvR](01_rvr_guerre_royaumes.md).
- Les **machines de siège** sont le type de troupe dédié à la destruction des fortifications.

---

## Paix négociée

Une guerre peut aussi se terminer par la négociation :

- **Tribut** — payer pour la paix.
- **Cession de territoire** — céder des terres.

---

**Voir aussi :** [RvR — Guerre des royaumes](01_rvr_guerre_royaumes.md) · [Système féodal](02_systeme_feodal.md) · [Karma Lumière/Ombre](../03_SYSTEMES_DE_JEU/01_karma_lumiere_ombre.md)
