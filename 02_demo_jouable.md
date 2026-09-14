# 02 — Démo jouable

## Vue d'ensemble

Une **démo jouable packagée** existe : version **v93**, datée de **juin 2026**.

---

## Boucle de jeu de la démo

La démo couvre la chaîne complète suivante :

```
Menu principal
     ↓
Création de personnage (4 écrans : Royaume → Race → Classe → Résumé)
     ↓
Donjon — 6 vagues d'ennemis
     ↓
Boss
     ↓
Sauvegarde / Chargement
```

| Étape | Contenu |
|---|---|
| **Menu** | Entrée du jeu |
| **Création de personnage** | Les 4 écrans complets, avec calcul du karma initial (-25 à +25) |
| **Donjon** | **6 vagues** d'ennemis successives |
| **Boss** | Affrontement de fin de donjon |
| **Sauvegarde / Chargement** | Persistance via l'orchestrateur (testé 9/9) |

---

## Ce que la démo démontre

- ✅ La chaîne technique complète : du menu à la sauvegarde, en version **packagée** (pas seulement en éditeur).
- ✅ La création de personnage fonctionnelle (royaumes, races, classes, karma initial).
- ✅ Le combat en conditions réelles (vagues + boss).
- ✅ La persistance (sauvegarde/chargement).

## Ce que la démo ne contient pas encore

- ❌ La narration jouable de la campagne (Actes I-III).
- ❌ Les animations finalisées (priorité #1 du projet).
- ❌ Certains écrans et le câblage audio.
- ❌ La connexion complète des systèmes backend (karma, mémoire PNJ, réputation) à la boucle jouée.

Voir [État actuel](01_etat_actuel.md) et [Roadmap](04_roadmap.md).

---

## Informations techniques

| Champ | Valeur |
|---|---|
| Version | **v93** |
| Date | Juin 2026 |
| Moteur | Unreal Engine 5.8 |
| Plateforme | Windows 64-bit |
| Format | Build packagée |

---

**Voir aussi :** [État actuel](01_etat_actuel.md) · [Systèmes backend](03_systemes_backend.md) · [Fiche technique](../07_TECHNIQUE/01_fiche_technique.md)
