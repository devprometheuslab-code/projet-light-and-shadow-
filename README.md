# Light & Shadow — Documentation complète du jeu

> **« Le monde se souvient de tout ce que vous faites. »**

Bienvenue dans la documentation officielle de **Light & Shadow**, un RPG d'action solo dark fantasy développé sous **Unreal Engine 5.8**. Ce dossier constitue la référence centrale de toutes les fonctionnalités du jeu : vision, monde, personnages, systèmes, campagne, endgame, état du projet et technique.

---

## 📖 Table des matières

### 01 — Vision et Monde
| Fichier | Contenu |
|---|---|
| [01_vision_generale.md](01_VISION_ET_MONDE/01_vision_generale.md) | Vision du jeu, genre, inspirations, promesse au joueur |
| [02_histoire_et_lore.md](01_VISION_ET_MONDE/02_histoire_et_lore.md) | Histoire du monde, lore, le Nexus, la guerre des royaumes |
| [03_les_trois_royaumes.md](01_VISION_ET_MONDE/03_les_trois_royaumes.md) | Cœur-Sylvain, Crête-Éternelle, Plaie-d'Ombre en détail |
| [04_direction_artistique.md](01_VISION_ET_MONDE/04_direction_artistique.md) | Style visuel, ambiance, références artistiques |

### 02 — Personnage
| Fichier | Contenu |
|---|---|
| [01_creation_personnage.md](02_PERSONNAGE/01_creation_personnage.md) | Les 4 écrans de création : Royaume → Race → Classe → Résumé |
| [02_races.md](02_PERSONNAGE/02_races.md) | Les 8 races (6 jouables + 2 déblocables) |
| [03_classes.md](02_PERSONNAGE/03_classes.md) | Les 12 classes (8 jouables), toutes solo-viables |
| [04_progression.md](02_PERSONNAGE/04_progression.md) | Niveaux, points de compétence, Arbre de Maîtrise, respec traumatique |

### 03 — Systèmes de jeu
| Fichier | Contenu |
|---|---|
| [01_karma_lumiere_ombre.md](03_SYSTEMES_DE_JEU/01_karma_lumiere_ombre.md) | Karma de -200 (Maudit) à +200 (Saint), aura, prix, corruption |
| [02_memoire_des_pnj.md](03_SYSTEMES_DE_JEU/02_memoire_des_pnj.md) | Mémoire des PNJ, opinion, propagation des crimes, érosion |
| [03_reputation_factions.md](03_SYSTEMES_DE_JEU/03_reputation_factions.md) | Réputation de faction, d'Hostile à Exalté |
| [04_combat.md](03_SYSTEMES_DE_JEU/04_combat.md) | Combat GAS, skillshots, 5 tiers de capacités, cooldowns |
| [05_magie_et_grimoire.md](03_SYSTEMES_DE_JEU/05_magie_et_grimoire.md) | Le Grimoire, 5 écoles de magie, fusion de sorts |
| [06_sauvegarde.md](03_SYSTEMES_DE_JEU/06_sauvegarde.md) | Orchestrateur de sauvegarde, 9/9 systèmes testés |

### 04 — Campagne
| Fichier | Contenu |
|---|---|
| [01_structure_actes.md](04_CAMPAGNE/01_structure_actes.md) | Vue d'ensemble des 3 actes, niveaux 1 à 10 |
| [02_acte_1_survie.md](04_CAMPAGNE/02_acte_1_survie.md) | Acte I — Survie et Choix (niveaux 1-3) |
| [03_acte_2_guerre.md](04_CAMPAGNE/03_acte_2_guerre.md) | Acte II — Guerre des Royaumes (niveaux 4-7) |
| [04_acte_3_nexus.md](04_CAMPAGNE/04_acte_3_nexus.md) | Acte III — Le Nexus (niveaux 8-10) |
| [05_fins_multiples.md](04_CAMPAGNE/05_fins_multiples.md) | Les 5 fins (3 principales + 2 secrètes) |

### 05 — Endgame
| Fichier | Contenu |
|---|---|
| [01_rvr_guerre_royaumes.md](05_ENDGAME/01_rvr_guerre_royaumes.md) | RvR façon DAOC, frontière contestée, forts capturables |
| [02_systeme_feodal.md](05_ENDGAME/02_systeme_feodal.md) | Titres de Roturier à Roi, fiefs, Marches, usurpation |
| [03_armees_et_sieges.md](05_ENDGAME/03_armees_et_sieges.md) | Armées data-driven, contres, économie de guerre |
| [04_new_game_plus.md](05_ENDGAME/04_new_game_plus.md) | New Game+, jusqu'à 10 cycles |

### 06 — État du projet
| Fichier | Contenu |
|---|---|
| [01_etat_actuel.md](06_ETAT_DU_PROJET/01_etat_actuel.md) | État d'avancement au septembre 2026 |
| [02_demo_jouable.md](06_ETAT_DU_PROJET/02_demo_jouable.md) | Démo v93 (juin 2026) : contenu et boucle de jeu |
| [03_systemes_backend.md](06_ETAT_DU_PROJET/03_systemes_backend.md) | Les ~50 systèmes C++ et ~40 tables de données |
| [04_roadmap.md](06_ETAT_DU_PROJET/04_roadmap.md) | Feuille de route, priorités, manques identifiés |

### 07 — Technique
| Fichier | Contenu |
|---|---|
| [01_fiche_technique.md](07_TECHNIQUE/01_fiche_technique.md) | Moteur, plateforme, rendu, configuration |
| [02_architecture.md](07_TECHNIQUE/02_architecture.md) | Architecture logicielle, GAS, data-driven |
| [03_plugins_et_outils.md](07_TECHNIQUE/03_plugins_et_outils.md) | Plugins UE utilisés et outils de développement |

---

## 🎮 Fiche d'identité rapide

| Champ | Valeur |
|---|---|
| **Titre** | Light & Shadow |
| **Genre** | RPG d'action solo dark fantasy, choix et conséquences |
| **Moteur** | Unreal Engine 5.8 |
| **Plateforme** | Windows 64-bit (SM5/SM6) |
| **Mode** | Solo uniquement |
| **Question centrale** | « Qu'est-ce que tu fais quand ton monde t'a vu faire une connerie ? » |
| **Inspirations** | The Witcher 3, Dark Souls, Dragon's Dogma, Pathologic, DAOC |

---

## 🧬 Les trois piliers (DNA du jeu)

1. **Mémoire des PNJ** — chaque PNJ se souvient de vos actes, les témoins propagent vos crimes.
2. **Karma Lumière/Ombre** — une échelle de -200 à +200 qui transforme votre apparence, vos prix et vos accès.
3. **Réputation de faction** — chaque action fait monter une faction… et peut en faire descendre une autre.

Ces trois systèmes sont **interconnectés** : c'est eux qui font que « le monde se souvient de tout ce que vous faites ».

---

*Documentation rédigée en français — Dernière mise à jour : septembre 2026.*
