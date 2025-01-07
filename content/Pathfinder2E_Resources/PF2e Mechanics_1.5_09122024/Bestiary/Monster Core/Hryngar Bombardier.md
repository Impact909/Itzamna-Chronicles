---
title: "Hryngar Bombardier"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.fKGyPHaNbGGlc5iP" 
tags:
  - pf2e/creature/type/duergar
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Hryngar Bombardier"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Hryngar Bombardier"
level: "Creature 1"

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
    desc: "Acrobatics: +6, Crafting: +6, Occultism: +6, Stealth: +6, Survival: +4"
abilityMods: [1, 3, 2, 3, 1, -1]
speed: 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +8, __Will__ +4; +2 status to all saves vs. magic"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Warhammer|Warhammer]], 2x [[Actor.B9QhDLiqnH6g4SKh.Item.rQnUzeBRVb714hi9|Alchemical Grenade (Acid)]], 2x [[Actor.B9QhDLiqnH6g4SKh.Item.rQnUzeBRVb714hi9|Alchemical Grenade (Fire)]], 2x [[Actor.B9QhDLiqnH6g4SKh.Item.rQnUzeBRVb714hi9|Alchemical Grenade (Cold)]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], [[Equipment/Alchemist's Toolkit|Alchemist's Toolkit]]"
  - name: "Alchemical Grenades"
    desc: "  A hryngar bombardier carries 6 alchemical grenades that deal either acid, cold, or fire damage plus 1 persistent damage and 1 splash damage of the same type (typically two of each). The bombardier replenishes these grenades each day using easily collected materials."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Warhammer"
    desc: "+4 (shove)\n__Damage__  1d8 + 1 bludgeoning"

  - name: "**Ranged** `pf2:1` Alchemical Grenade"
    desc: "+8 (range increment 20 feet, splash)\n__Damage__  1d6 acid"

  - name: "Occult Innate Spells"
    desc: "DC 17, attack +9; __2nd __  _[[Spells/Blood Vendetta|Blood Vendetta]]_, _[[Spells/Paranoia|Paranoia]]_\n__Cantrips__  __(1st)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Quick Bombardier"
    desc: "`pf2:1`  The hryngar bombardier draws an alchemical grenade with an Interact action and throws it as a ranged Strike."
 
```

```encounter-table
name: Hryngar Bombardier
creatures:
  - 1: Hryngar Bombardier
```



Hryngar chemists have a knack for creating alchemical grenades. Their traditions often motivate them to constantly experiment and innovate, though the hostile nature of their environs tends to focus these innovations on weapons or other tools of war. Hryngar bombardiers eagerly steal notes and secrets from their underlings, pushing their students to cut corners to produce results while gleefully pillaging the credit and profits. For those hryngar bombardiers who find themselves pressed into combat service, each thrown grenade represents a new opportunity to observe the suffering they inflict, before eagerly incorporating that data into their next experiment or innovation to create an even more terrible tool of torment.

* * *

Deep beneath the surface, the dour dwarves known as hryngars stubbornly toil, claiming the ancestral subterranean homelands of other dwarves as their own. Long ago, hryngar leaders refused to venture to the surface along with their "cousins," forsaking the Quest for Sky. An exiled dwarven deity named Droskar offered hryngars salvation from the horrors that beset them in the Darklands, offering them power, cunning, and knowledge in exchange for their unending servitude. Many hryngar believe that by working harder than their brethren, they can build a society far greater than anything under the sun, claiming unending riches from the planet's metallic veins in days of relentless toil.

Through Droskar's blessings and their own fearsome work ethic, hryngar kingdoms now rule a significant portion of the upper Darklands region of NarVoth, and it's common to see hryngar caravans moving through the tunnels, drawn by teams of immense beetles. Hryngar leadership typically consists of powerful divine servants of Droskar, along with fearsomely implacable warriors whose martial prowess, backed by innate occult magic, ensures they can overcome any direct threat to hryngar rule. Almost every aspect of hryngar society is controlled by a strict hierarchy of leadership, with taskmasters directing subordinates across all walks of life.
