# 06 — Sauvegarde

## Vue d'ensemble

Le système de sauvegarde de Light & Shadow est assuré par un **orchestrateur de sauvegarde** central qui persiste l'ensemble des systèmes de jeu.

> **État :** l'orchestrateur est testé **9/9** — les neuf systèmes couverts passent leurs tests de sauvegarde/chargement.

---

## Ce qui est persisté

L'orchestrateur couvre notamment :

| Domaine | Contenu sauvegardé |
|---|---|
| **Personnage** | Royaume, race, classe, niveau, points de compétence, maîtrise |
| **Karma** | Valeur de karma (-200 à +200) et palier |
| **Mémoire des PNJ** | Opinions (-100 à +100), faits mémorisés (jusqu'à 32 par PNJ), état d'érosion |
| **Réputation de factions** | Rangs auprès des factions (Hostile → Exalté) |
| **Campagne** | Progression des actes, choix effectués (Marque de l'Ombre, Alliances de Sang…) |
| **Magie** | Sorts appris et configuration du Grimoire |
| **Monde** | État des forts, sièges, factions territoriales |
| **New Game+** | Compteur de cycles, éléments conservés |

---

## Pourquoi un orchestrateur

Le monde de Light & Shadow est **systémique** : karma, mémoire des PNJ et réputation s'influencent mutuellement. Une sauvegarde partielle ou désynchronisée casserait la promesse « le monde se souvient ». L'orchestrateur garantit que **tous les systèmes sont sauvegardés et rechargés de manière cohérente**, en une seule opération.

---

## Dans la démo jouable

La démo v93 (juin 2026) inclut déjà la boucle **sauvegarde / chargement** : menu → création de personnage → donjon 6 vagues → boss → sauvegarde/chargement — voir [Démo jouable](../06_ETAT_DU_PROJET/02_demo_jouable.md).

---

**Voir aussi :** [Systèmes backend](../06_ETAT_DU_PROJET/03_systemes_backend.md) · [Démo jouable](../06_ETAT_DU_PROJET/02_demo_jouable.md) · [Architecture](../07_TECHNIQUE/02_architecture.md)
