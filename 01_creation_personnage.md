# 01 — Création de personnage

## Vue d'ensemble

La création de personnage de Light & Shadow se déroule en **4 écrans séquentiels** :

```
Royaume  →  Race  →  Classe  →  Résumé
```

Chaque choix filtre les options suivantes et contribue au **karma initial** du personnage. L'interface est construite avec **CommonUI** (voir [Plugins et outils](../07_TECHNIQUE/03_plugins_et_outils.md)).

---

## Écran 1 — Choix du Royaume

Le joueur choisit d'abord son royaume d'allégeance :

| Royaume | Alignement | Débloque |
|---|---|---|
| **Cœur-Sylvain** | Lumière | Races Eldrim, Luminae ; classes Paladin de l'Aube, Clerc de Guerre |
| **Crête-Éternelle** | Neutre | Races Thuldor, Grunaak ; classes Mercenaire, Arcaniste Errant, Gardien du Crépuscule, Forgemage |
| **Plaie-d'Ombre** | Ombre | Race Nepharak ; classes Nyktomancien, Assassin de l'Ombre |

Les **Humains**, universels, restent accessibles quel que soit le royaume.

---

## Écran 2 — Choix de la Race

Les races proposées dépendent du royaume choisi. Le jeu compte **8 races au total, dont 6 jouables** et 2 déblocables (Drakir, Hethym) — voir [Races](02_races.md).

---

## Écran 3 — Choix de la Classe

Les classes proposées dépendent du royaume. Le jeu prévoit **12 classes au total, dont 8 jouables** à ce stade — voir [Classes](03_classes.md).

**Principe de design :** toutes les classes sont conçues pour être **solo-viables**. Il n'existe pas de classe « support » inutilisable seul.

---

## Écran 4 — Résumé

L'écran final récapitule :

- Royaume, race, classe choisis.
- **Karma initial calculé** (voir ci-dessous).
- Aperçu du personnage et de ses orientations de départ.

---

## Karma initial

Le karma de départ est **calculé à partir de l'alignement du triplet Royaume + Race + Classe**, sur une plage de **-25 à +25** :

- Un triplet cohérent avec la Lumière (ex. Cœur-Sylvain + Luminae + Paladin de l'Aube) tend vers **+25**.
- Un triplet cohérent avec l'Ombre (ex. Plaie-d'Ombre + Nepharak + Assassin de l'Ombre) tend vers **-25**.
- Les combinaisons mixtes ou neutres atterrissent entre les deux.

Ce karma initial n'est qu'un point de départ : il évoluera de -200 à +200 selon les actions du joueur — voir [Karma Lumière/Ombre](../03_SYSTEMES_DE_JEU/01_karma_lumiere_ombre.md).

---

## Liberté de combinaison

Inspiré de **Dragon's Dogma**, le jeu vise une grande liberté de combinaison race/classe : un Eldrim n'est pas enfermé dans un archétype, et les restrictions restent des orientations, pas des couloirs. Les classes non jouables au lancement (4 sur 12) et les races déblocables (Drakir, Hethym) enrichiront ces combinaisons.

---

**Voir aussi :** [Races](02_races.md) · [Classes](03_classes.md) · [Progression](04_progression.md) · [Karma Lumière/Ombre](../03_SYSTEMES_DE_JEU/01_karma_lumiere_ombre.md)
