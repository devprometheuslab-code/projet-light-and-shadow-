# 03 — Systèmes backend

## Vue d'ensemble

Le backend de Light & Shadow comprend environ **50 systèmes C++** et **40 tables de données**. C'est la partie la plus avancée du projet.

---

## Les ~50 systèmes C++

Principaux systèmes identifiés :

| Système | Rôle | État |
|---|---|---|
| **Karma** | Échelle -200/+200, paliers, effets (prix, aura, accès) | ✅ |
| **Réputation** | Rangs de faction, dynamique inter-factions | ✅ |
| **Mémoire des PNJ** | Opinions, 32 faits/PNJ, propagation témoins, érosion | ✅ |
| **Factions** | Gestion des trois royaumes et de leurs relations | ✅ |
| **Orchestrateur de sauvegarde** | Persistance cohérente de tous les systèmes | ✅ **testé 9/9** |
| **New Game+** | Cycles (jusqu'à 10), éléments conservés | ✅ |
| **Sièges** | Mécaniques de siège pour la campagne et le RvR | ✅ |

*(Liste non exhaustive : ~50 systèmes au total en backend.)*

---

## Les ~40 tables de données

Le contenu du jeu est **data-driven** :

| Table | Contenu |
|---|---|
| **Quêtes** | Définitions des quêtes de la campagne |
| **Dialogues** | Arbres de dialogue des PNJ |
| **Bestiaire** | Ennemis et créatures |
| **Lore** | Entrées de lore du monde |
| **PNJ** | Environ **140 PNJ** définis |
| **Troupes** | Types d'unités pour les armées RvR |
| **Fiefs** | Définitions des fiefs du système féodal |

*(~40 tables au total.)*

---

## Conséquences pour le développement

### Forces
- **Backend testé** : les systèmes existent et fonctionnent individuellement (sauvegarde 9/9).
- **Contenu data-driven** : quêtes, dialogues, PNJ, troupes et fiefs s'éditent en données, sans recompilation.
- **Architecture systémique cohérente** : karma, mémoire et réputation sont interconnectés par design.

### Le goulot d'étranglement
Le défi n'est plus de créer des systèmes mais de **les connecter à la boucle jouable** : narration jouable, écrans, audio, animations — voir [État actuel](01_etat_actuel.md) et [Roadmap](04_roadmap.md).

---

**Voir aussi :** [État actuel](01_etat_actuel.md) · [Démo jouable](02_demo_jouable.md) · [Architecture](../07_TECHNIQUE/02_architecture.md)
