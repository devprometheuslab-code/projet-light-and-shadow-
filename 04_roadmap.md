# 04 — Roadmap

## Vue d'ensemble

Le backend est complet ; la feuille de route se concentre sur la **connexion des systèmes à la boucle jouable** et sur les manques identifiés.

---

## Priorités

### Priorité #1 — Animations
> **Blocage majeur actuel.**

Les animations sont la priorité absolue du projet : elles conditionnent le ressenti du combat (skillshots, 5 tiers de capacités), la crédibilité des PNJ et l'impact de la narration.

### Priorité haute — Narration jouable
Rendre la campagne (Actes I-III) **jouable** : les quêtes et dialogues existent en tables de données, il faut les brancher sur l'expérience effective.

### Priorité haute — Écrans manquants
Compléter les interfaces manquantes (CommonUI) au-delà des écrans déjà fonctionnels de la démo.

### Priorité moyenne — Câblage audio
Brancher l'ambiance sonore : musiques, bruitages, identités sonores des trois royaumes (voir [Direction artistique](../01_VISION_ET_MONDE/04_direction_artistique.md)).

### Priorité moyenne — QA humaine
Organiser les tests humains de la boucle complète : au-delà des tests automatisés des systèmes (sauvegarde 9/9), le jeu doit être **joué** et éprouvé.

---

## État d'avancement synthétique

| Chantier | État | Prochaine étape |
|---|---|---|
| Backend systémique (~50 systèmes) | ✅ Fait | Maintenance |
| Données (~40 tables, ~140 PNJ) | ✅ Fait | Enrichissement |
| Démo packagée v93 | ✅ Fait (juin 2026) | Itérations |
| Sauvegarde (9/9) | ✅ Fait | — |
| Animations | 🔴 Priorité #1 | Production |
| Narration jouable | 🟠 À connecter | Branchement campagne |
| Écrans | 🟠 Partiel | Compléter les manquants |
| Audio | 🟠 À câbler | Intégration |
| QA humaine | 🟠 À organiser | Sessions de test |

---

## Contenus prévus non encore jouables

- **4 classes** supplémentaires (12 prévues, 8 jouables) — voir [Classes](../02_PERSONNAGE/03_classes.md).
- **2 races déblocables** : Drakir, Hethym — voir [Races](../02_PERSONNAGE/02_races.md).
- **Extension du Grimoire** : de 12 sorts actuels vers ~40 sorts en 5 écoles — voir [Magie et Grimoire](../03_SYSTEMES_DE_JEU/05_magie_et_grimoire.md).
- **2 fins secrètes** — voir [Fins multiples](../04_CAMPAGNE/05_fins_multiples.md).

---

**Voir aussi :** [État actuel](01_etat_actuel.md) · [Démo jouable](02_demo_jouable.md) · [Systèmes backend](03_systemes_backend.md)
