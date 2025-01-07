---
title: "Hryngar Sharpshooter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ujiv8KzYL26yE37a" 
tags:
  - pf2e/creature/type/duergar
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Hryngar Sharpshooter"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Hryngar Sharpshooter"
level: "Creature 0"

alignment: ""
size: "Medium"
trait_01: [[duergar]]
trait_02: [[dwarf]]
trait_03: [[humanoid]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +3, Stealth: +5"
abilityMods: [1, 3, 3, 0, 2, -2]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +7, __Ref__ +7, __Will__ +4; +2 status to all saves vs. magic"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|Crossbow]], [[Equipment/Light Mace|Light Mace]], [[Equipment/Chain Shirt|Chain Shirt]], 3x [[Equipment/Bolts|Bola Bolts]], 10x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Light Mace"
    desc: "+5 (agile, finesse, shove)\n__Damage__  1d4 + 1 bludgeoning"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+7 (range increment 120 feet, reload 1)\n__Damage__  1d8 piercing plus bolts"

  - name: "Occult Innate Spells"
    desc: "DC 12, attack +4; __2nd __  _[[Spells/Blood Vendetta|Blood Vendetta]]_, _[[Spells/Paranoia|Paranoia]]_\n__Cantrips__  __(1st)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Bola Bolt"
    desc: "  This shot deals no damage, but on a hit, the target must succeed at a DC 16 Reflex check save or be knocked [[Conditions/Prone|Prone]] and [[Conditions/Immobilized|Immobilized]] until it is freed with a successful DC 15 check to [[/act escape dc=15]]. This check can be attempted either by the target or a creature adjacent to the target."
 
```

```encounter-table
name: Hryngar Sharpshooter
creatures:
  - 1: Hryngar Sharpshooter
```



Deep beneath the surface, the dour dwarves known as hryngars stubbornly toil, claiming the ancestral subterranean homelands of other dwarves as their own. Long ago, hryngar leaders refused to venture to the surface along with their "cousins," forsaking the Quest for Sky. An exiled dwarven deity named Droskar offered hryngars salvation from the horrors that beset them in the Darklands, offering them power, cunning, and knowledge in exchange for their unending servitude. Many hryngar believe that by working harder than their brethren, they can build a society far greater than anything under the sun, claiming unending riches from the planet's metallic veins in days of relentless toil.

Through Droskar's blessings and their own fearsome work ethic, hryngar kingdoms now rule a significant portion of the upper Darklands region of NarVoth, and it's common to see hryngar caravans moving through the tunnels, drawn by teams of immense beetles. Hryngar leadership typically consists of powerful divine servants of Droskar, along with fearsomely implacable warriors whose martial prowess, backed by innate occult magic, ensures they can overcome any direct threat to hryngar rule. Almost every aspect of hryngar society is controlled by a strict hierarchy of leadership, with taskmasters directing subordinates across all walks of life.
