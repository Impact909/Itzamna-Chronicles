---
title: "Spawn Of Kothogaz"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ecW36sgZp5HMrBnm" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Spawn Of Kothogaz"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Spawn Of Kothogaz"
level: "Creature 6"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[evil]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +14, Stealth: +13"
abilityMods: [4, 5, 3, -4, 2, 0]
speed: 40 feet,  burrow 25 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +13, __Ref__ +17, __Will__ +10"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70, regeneration 10 (deactivated by holy); __Immunities__  acid"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Holy)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Disharmonious Decay"
    desc: " (poison) When a spawn dies, its foulness seeps into the land in a 100-foot radius. Non-magical plant life in the area decays within 1 hour, and new non-magical growth can't sprout for 1 month. A creature can act on the spawn's corpse within 1 minute of its death to limit this decay to a 10-foot square by succeeding at a DC 22 Medicine check, DC 22 Nature check, or DC 22 Occultism check check."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+17 (finesse, versatile s)\n__Damage__  2d10 + 7 piercing"

  - name: "**Melee** `pf2:1` Wing Shard"
    desc: "+17 (agile, finesse)\n__Damage__  1d6 + 7 piercing 1d6 sonic"

  - name: "**Ranged** `pf2:1` Putrid Spit"
    desc: "+17 (range increment 60 feet)\n__Damage__  2d8 + 4 acid"

  - name: "Fusing Spit"
    desc: "`pf2:2` (acid) The spawn retches up thick, caustic sludge and spits it at a creature within 60 feet, causing equipment and flesh to melt and partially fuse together. The creature must succeed at a DC 23 Reflex check save or be [[Conditions/Clumsy|Clumsy 2]] for 1 minute."
 
```

```encounter-table
name: Spawn Of Kothogaz
creatures:
  - 1: Spawn Of Kothogaz
```



Kothogaz's presence causes the land to sprout festering hives. Insectile, acid-drooling spawn slither from these growths as lesser versions of their creator.
