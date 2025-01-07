---
title: "Corrupted Relic"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.txC2eS9anpUmTYC4" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Corrupted Relic"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Corrupted Relic"
level: "Creature 4"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[spirit]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision, Lifesense (Imprecise) 60 Feet"
languages: "Common, Elven"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Intimidation: +10, Stealth: +11"
abilityMods: [-5, 3, 0, 1, 1, 4]
speed:  fly 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +6, __Ref__ +11, __Will__ +11"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Amulet"
  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense (Imprecise) 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "Amulet Relic"
    desc: " (curse,divine) The corrupted relic is an amulet cursed to contain a malevolent spirit. The statistics in this stat block are for the spirit when it's manifested (see Manifest). The amulet can't take any actions except Sudden Manifestation and Manifest. As long as the spirit is manifested, the amulet is immune to spells and magical abilities and uses the saves listed here.\n\nRegardless of whether the spirit is manifested, the amulet can be targeted by Strikes (AC 21, Hardness 5, BT 10). It is not incorporeal. If the amulet becomes broken, the spirit is bound within and can't Manifest, and if the amulet is destroyed, so is the spirit. Destroying the spirit frees the amulet from its curse."

  - name: "Sudden Manifestation"
    desc: "`pf2:r`  **Trigger** The relic detects a creature using its lifesense.\n* * *\n\n**Effect** The relic Manifests. If this causes an encounter to begin, the relic gains a +4 status bonus to its initiative roll."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spectral Hand"
    desc: "+14 (agile, finesse, magical)\n__Damage__  2d6 + 3 void"

  - name: "**Ranged** `pf2:1` Deadly Spark"
    desc: "+14 (air, divine, electricity, range 20 feet)\n__Damage__  1d12 electricity"

  - name: "Death Gaze"
    desc: "`pf2:2` (concentrate,divine,void) The spirit targets a creature it can see within 30 feet, dealing to it 4d6 void damage (DC 20 Fortitude check save).\n\nA creature with [[Bestiary Ability Glossary/Void Healing|Void Healing]] instead regains 4d6 healing Hit Points and is then temporarily immune for 10 minutes."

  - name: "Manifest"
    desc: "`pf2:1` (divine) **Requirements** The relic detects at least one creature using its lifesense.\n* * *\n\n**Effect** The spirit within the relic manifests in an open space within 10 feet of the amulet. When it does, the relic teleports around its neck. The spirit remains in its manifested state until it no longer senses any living creatures within range of its lifesense."
 
```

```encounter-table
name: Corrupted Relic
creatures:
  - 1: Corrupted Relic
```



Creatures that once held particular items dear can be bound to them after death, their souls inhabiting the item from within. These might be the faithful haunting symbols of their faith, warriors clinging to their old weapons, or the greedy inhabiting their precious wealth. These spirits' physical bodies have long since degraded, but they keep their corrupted relics pristine. The spirits manifest on the unsuspecting or curious, determined to destroy anyone who would dare show any interest in their one precious possession.

Though rare, there are several kinds of corrupted relics. The bound spirit can manifest in different ways, from animating an ancient weapon to possessing anyone who dons the item. Destroying the relic often ends up being the simplest, most direct way to banish the haunt itself. Destroying or dispelling the spirit without destroying the relic, however, can sometimes leave priceless treasure behind.

The amulet shown here has the air and death aspects. Its minor gifts, deadly spark and death gaze, power some of the spirit's abilities. Someone who claims the relic might gain different gifts from those aspects.
