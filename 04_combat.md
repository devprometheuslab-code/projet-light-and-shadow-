# 04 — Combat

## Vue d'ensemble

Le combat de Light & Shadow est un **action combat exigeant**, inspiré de Dark Souls, construit sur le **Gameplay Ability System (GAS)** d'Unreal Engine, et fondé sur les **skillshots** : les capacités se **visent**, il n'y a pas d'auto-lock.

> Le joueur vise, cadence et assume ses erreurs. Chaque affrontement compte.

---

## Fondations techniques

| Élément | Choix |
|---|---|
| **Framework** | Gameplay Ability System (GAS) |
| **Ciblage** | Skillshot — visée manuelle, pas de verrouillage automatique |
| **Input** | Enhanced Input |
| **Effets** | Niagara (impacts, projectiles, magie) |

Voir [Architecture](../07_TECHNIQUE/02_architecture.md) et [Plugins et outils](../07_TECHNIQUE/03_plugins_et_outils.md).

---

## Les 5 tiers de capacités

Les capacités sont classées en **5 tiers**, chacun avec son rythme et son risque :

| Tier | Nom | Rythme | Particularité |
|---|---|---|---|
| 1 | **Rapides** | Instantané | Réactions immédiates, faible coût, faible impact |
| 2 | **Standards** | Visées | Le cœur du combat : capacités à viser, rapport coût/effet équilibré |
| 3 | **Signatures** | Long cast | Capacités puissantes à longue incantation — ⚠️ **si interrompues, tout le mana est perdu** |
| 4 | **Canalisées** | Canalisation | Effet maintenu tant que la canalisation tient |
| 5 | **Réactives** | Fenêtre de réaction | Parade / esquive : récompense le timing défensif |

### Le risque des Signatures
Les capacités Signature incarnent le pari du combat : un long cast pour un effet majeur, mais **une interruption fait perdre la totalité du mana investi**. Positionnement, lecture de l'ennemi et timing deviennent critiques.

---

## Cooldowns calculés sur la puissance réelle

Les temps de recharge ne sont **pas arbitraires** : ils sont **calculés à partir de la puissance réelle** de la capacité, en fonction de :

- **Dégâts**
- **Contrôle** (cc : ralentissements, étourdissements…)
- **Zone** (taille de l'effet)
- **Utilité** (mobilité, soin, buff…)

Plus une capacité est puissante sur ces axes, plus son cooldown est long. L'équilibrage est donc **dérivé des données**, pas fixé à la main capacité par capacité.

---

## Combat et progression

- Les branches de l'[Arbre de Maîtrise](../02_PERSONNAGE/04_progression.md) modifient directement le combat : HP/mêlée/armure (Guerre), puissance des sorts/mana/cooldowns (Arcane), critique/vol de vie/vitesse (Ombre).
- Les classes définissent les capacités accessibles — voir [Classes](../02_PERSONNAGE/03_classes.md).
- Les sorts du [Grimoire](05_magie_et_grimoire.md) s'insèrent dans ce cadre GAS.

---

## Philosophie de difficulté

- **Chaque erreur se paie :** une esquive ratée, un cast interrompu, une aggro mal gérée ont un coût réel.
- **La maîtrise se mérite :** le système récompense la lecture des ennemis, la gestion des ressources et la précision de la visée.
- **Solo-viable :** toutes les classes disposent des outils pour survivre seules — voir [Classes](../02_PERSONNAGE/03_classes.md).

---

**Voir aussi :** [Magie et Grimoire](05_magie_et_grimoire.md) · [Progression](../02_PERSONNAGE/04_progression.md) · [Architecture](../07_TECHNIQUE/02_architecture.md)
