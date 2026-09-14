# 01 — État actuel du projet

> **Situation au : septembre 2026**

## Vue d'ensemble

Light & Shadow dispose d'un **backend systémique très avancé** et d'une **démo jouable packagée**. Le défi principal du projet n'est plus de créer des systèmes, mais de **les connecter à la boucle de jeu jouable**.

---

## Ce qui existe

| Domaine | État |
|---|---|
| **Démo jouable** | ✅ Version packagée **v93** (juin 2026) — voir [Démo jouable](02_demo_jouable.md) |
| **Systèmes backend C++** | ✅ Environ **50 systèmes** — voir [Systèmes backend](03_systemes_backend.md) |
| **Tables de données** | ✅ Environ **40 tables** (quêtes, dialogues, bestiaire, lore, ~140 PNJ, troupes, fiefs) |
| **Sauvegarde** | ✅ Orchestrateur testé **9/9** |
| **New Game+** | ✅ Système en place |
| **Sièges** | ✅ Système backend en place |

---

## Le défi principal

> **Connecter les systèmes backend à la boucle jouable.**

Les systèmes existent et sont testés individuellement, mais le cœur du travail restant consiste à les faire vivre dans l'expérience de jeu effective : narration jouable, écrans, audio, animations.

---

## Manques identifiés

| Priorité | Manque | Impact |
|---|---|---|
| **#1** | **Animations** | Blocage majeur pour le ressenti de combat et la crédibilité du monde |
| Haute | **Narration jouable** | La campagne existe en données mais pas encore en expérience jouée |
| Haute | **Écrans manquants** | Certaines interfaces restent à réaliser |
| Moyenne | **Câblage audio** | L'ambiance sonore n'est pas encore branchée |
| Moyenne | **QA humaine** | Tests humains de la boucle complète à organiser |

Voir [Roadmap](04_roadmap.md) pour le plan de résolution.

---

## Repères de versions

| Date | Jalons |
|---|---|
| Juin 2026 | Démo packagée **v93** |
| Septembre 2026 | État actuel : backend complet, connexion à la boucle jouable en cours |

---

**Voir aussi :** [Démo jouable](02_demo_jouable.md) · [Systèmes backend](03_systemes_backend.md) · [Roadmap](04_roadmap.md)
