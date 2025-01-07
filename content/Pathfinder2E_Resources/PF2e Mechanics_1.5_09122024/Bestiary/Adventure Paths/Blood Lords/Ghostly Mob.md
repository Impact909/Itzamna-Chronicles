---
title: "Ghostly Mob"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MAL7cqfir7qebSNW" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/troop
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Ghostly Mob"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #182: Graveclaw"
name: "Ghostly Mob"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghost]]
trait_04: [[incorporeal]]
trait_05: [[troop]]
trait_06: [[undead]]
trait_07: [[unholy]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Stealth: +16, Local Lore: +14"
abilityMods: [-5, 4, 3, 0, 4, 4]
speed:  fly 25 feet
sourcebook: "_Pathfinder #182: Graveclaw_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +14, __Will__ +18"
hp: 105
health:
  - name: ""
  - name: HP
    desc: "105, 16 squares, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  sleep; __Weaknesses__ area damage 15, splash damage 10; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Form Up|Form Up]]"
    desc: "`pf2:1`  The troop chooses one of the squares it currently occupies and redistributes its squares to any configuration in which all squares are contiguous and within 15 feet of the chosen square. The troop can't share its space with other creatures."

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  A ghostly mob can stray only a moderate distance from where its members were killed or the place it haunts. A typical limit is 240 feet."

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a ghostly mob is destroyed, it re-forms after 2d4 days, fully healed. A ghostly mob can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the troop from resting."

  - name: "[[Bestiary Ability Glossary/Troop Defenses|Troop Defenses]]"
    desc: "  **Thresholds** 70 (12 squares), 35 (8 squares)\n* * *\n\nTroops are composed of many individuals, and over the course of enough attacks and downed comrades, troops shrink in size. Most troops start with 16 squares (4 by 4), and their Hit Points have two listed thresholds, typically the first is at 2/3 their maximum Hit Points and the second is at 1/3 their maximum Hit Points. Once the troop drops below the first threshold, it loses 4 squares, leaving 12 squares remaining, and the first threshold becomes the troop's new maximum Hit Points. Once the troop falls below the second threshold, it loses another 4 squares, leaving 8 squares remaining, and the second threshold becomes the troop's new maximum Hit Points. In order to restore its size and maximum Hit Points, a troop needs to spend downtime to use long-term treatment on casualties or recruit new members to replace the fallen. At 0 Hit Points, the troop is reduced down to 4 squares, which is too few to sustain the troop, so it disperses entirely, with the few remaining members surrendering, fleeing, or easily dispatched, depending on their nature.\n\nA damaging single-target effect, such as a Strike, can't force a troop to pass through more than one threshold at once. For instance, if a troop had 60 Hit Points, with thresholds at 40 and 20, a Strike for 50 damage would leave the troop at 21 Hit Points, just above the second threshold. A damaging area effect or multi-target effect can cross multiple thresholds at once and could potentially destroy the entire troop in one shot.\n\nNon-damaging effects with an area or that target all creatures in a certain proximity affect a troop normally if they affect the entire area occupied by the troop. If an effect has a smaller area or numbers of targets, it typically has no effect on the troop. However, if the effect can target at least four creatures or cover at least four squares in the troop, and if it would prevent its targets from acting, cause them to flee, or otherwise make them unable to function as part of the troop for a round or more, the troop loses loses a number of Hit Points equal to the amount required to bring it to the next threshold, removing 4 squares. If an effect would both deal damage and automatically cross a threshold due to incapacitating some of the creatures in the troop, apply the damage first. If the damage wasn't enough to cross a threshold on its own, then reduce the Hit Points to cross the threshold for the incapacitating effect."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "Clutching Hands"
    desc: "`pf2:1` (divine) `pf2:1` to `pf2:3`\n\n**Frequency** once per round\n* * *\n\n**Effect** The troop attacks enemies within 5 feet (DC 25 Reflex check), with damage depending on the number of actions.\n\n`pf2:1` 1d6+3 void damage\n\n`pf2:2` 3d6+6 void damage\n\n`pf2:3` 4d6+9 void damage"

  - name: "Frightful Chorus"
    desc: "`pf2:2` (auditory,divine,emotion,fear,mental) The ghostly mob howls in anguish, forcing each living creature in a 30-foot emanation to attempt a DC 25 Will check save or become [[Conditions/Frightened|Frightened 2]] ([[Conditions/Frightened|Frightened 3]] on a critical failure). Regardless of the save result, the creature is then temporarily immune to the troop's Frightful Chorus for 1 minute."

  - name: "Troop Movement"
    desc: "  Whenever the ghostly mob Strides, it first Forms Up as a free action to condense into a 20-foot-by-20-foot area (minus any missing squares), and then moves. This works just like a Gargantuan creature moving; for instance, if any of the ghostly mob's squares enter difficult terrain, the extra movement cost applies to the whole group."
 
```

```encounter-table
name: Ghostly Mob
creatures:
  - 1: Ghostly Mob
```



When a horrific tragedy results in mass death, the restless spirits of the numerous dead might arise as a ghostly mob. Like other ghosts, ghostly mobs are often unaware they're dead. The spirits trapped within the mob may try to carry out a semblance of their former lives, even though their memories are fragmentary and their forms are insubstantial. When forced to confront their true state, the spirits lash out in pain and violence.
