# 02 — Mémoire des PNJ

## Vue d'ensemble

La **mémoire des PNJ** est le premier pilier du DNA de Light & Shadow. Chaque PNJ possède une **opinion personnelle** du joueur et mémorise des **faits** sur ses actions. Les témoins propagent les crimes, et le temps érode les souvenirs — sauf les pires.

> C'est le système qui rend littérale la promesse : *« Qu'est-ce que tu fais quand ton monde t'a vu faire une connerie ? »*

---

## Opinion personnelle

Chaque PNJ note le joueur sur une échelle de **-100 à +100**, traduite en **5 attitudes** :

| Attitude | Zone d'opinion | Comportement typique |
|---|---|---|
| **Dévoué** | Très positive | Aide active, confiance, avantages |
| **Amical** | Positive | Coopération, dialogue ouvert |
| **Neutre** | Autour de 0 | Comportement standard |
| **Méfiant** | Négative | Méfiance, dialogue fermé, surveillance |
| **Hostile** | Très négative | Refus, dénonciation, agression possible |

---

## Les faits mémorisés

- Chaque PNJ peut mémoriser jusqu'à **32 faits** concernant le joueur.
- Un « fait » est un événement observé ou appris : un vol, un meurtre, une aide rendue, une promesse tenue ou brisée.
- Les faits alimentent l'opinion et donc l'attitude du PNJ.

---

## Propagation par les témoins

Les crimes ne restent pas privés :

1. Un crime commis **devant un témoin** est mémorisé par ce témoin.
2. Le témoin **propage l'information** : d'autres PNJ apprennent ce que vous avez fait.
3. L'opinion se dégrade donc **au-delà de la scène du crime** — la rumeur fait le travail.

Tuer un témoin peut empêcher la propagation… mais un meurtre est lui-même un fait, et les meurtres s'oublient plus lentement (voir ci-dessous).

---

## Érosion temporelle

Les souvenirs s'estompent avec le temps :

- **Durée d'érosion standard :** environ **90 jours** de jeu.
- **Les meurtres s'effacent plus lentement** que les autres faits : le monde pardonne les dettes, moins le sang.

---

## Interconnexions

| Système | Interaction |
|---|---|
| [Karma Lumière/Ombre](01_karma_lumiere_ombre.md) | Les faits négatifs propagent une trajectoire de karma ; l'aura de karma colore à son tour les réactions. |
| [Réputation de factions](03_reputation_factions.md) | Les crimes contre les membres d'une faction impactent la réputation auprès de cette faction. |
| [Sauvegarde](06_sauvegarde.md) | L'état de la mémoire des PNJ est persisté par l'orchestrateur de sauvegarde. |

---

## Conséquences en jeu

- **Dialogues :** l'attitude d'un PNJ conditionne ses répliques et les options proposées.
- **Commerce :** un PNJ méfiant vendra moins bien (effet cumulé avec le karma).
- **Quêtes :** certains PNJ refusent de traiter avec un personnage qu'ils haïssent.
- **Sécurité :** un personnage hostilement perçu peut être dénoncé, refusé aux portes, ou attaqué.

---

## Données

Le roster de PNJ du monde compte environ **140 PNJ** définis dans les tables de données — voir [Systèmes backend](../06_ETAT_DU_PROJET/03_systemes_backend.md).

---

**Voir aussi :** [Karma Lumière/Ombre](01_karma_lumiere_ombre.md) · [Réputation de factions](03_reputation_factions.md) · [Sauvegarde](06_sauvegarde.md)
