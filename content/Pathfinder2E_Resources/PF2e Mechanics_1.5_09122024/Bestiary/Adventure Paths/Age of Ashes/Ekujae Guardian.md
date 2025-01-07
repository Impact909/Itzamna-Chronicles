---
title: "Ekujae Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tM86QAE2sNY3lGsI" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/elf
  - pf2e/creature/type/good
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Ekujae Guardian"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #146: Cult of Cinders"
name: "Ekujae Guardian"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[elf]]
trait_03: [[good]]
trait_04: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Low-Light Vision"
languages: "Elven, Mwangi"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +7, Nature: +6, Stealth: +7, Survival: +6"
abilityMods: [3, 3, 0, 1, 2, 0]
speed: 30 feet
sourcebook: "_Pathfinder #146: Cult of Cinders_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +6, __Ref__ +9, __Will__ +6"
hp: 26
health:
  - name: ""
  - name: HP
    desc: "26"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Cold Iron Dagger]], [[Equipment/Dagger|Silver Dagger]], [[Equipment/Longbow|Longbow]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], 6x [[Equipment/Black Adder Venom|Black Adder Venom]], 20x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Cold Iron Dagger"
    desc: "+11 (agile, cold iron, versatile s)\n__Damage__  1d4 + 3 piercing"

  - name: "**Melee** `pf2:1` Silver Dagger"
    desc: "+11 (agile, silver, versatile s)\n__Damage__  1d4 + 3 piercing"

  - name: "**Ranged** `pf2:1` Cold Iron Dagger"
    desc: "+11 (agile, cold iron, thrown 10 ft., versatile s)\n__Damage__  1d4 + 3 piercing"

  - name: "**Ranged** `pf2:1` Silver Dagger"
    desc: "+11 (agile, silver, thrown 10 ft., versatile s)\n__Damage__  1d4 + 3 piercing"

  - name: "**Ranged** `pf2:1` Longbow"
    desc: "+11 (deadly d10, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 piercing plus black-adder-venom"

  - name: "Primal Innate Spells"
    desc: "DC 16, attack +8\n__Cantrips__  __(1st)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Vitality Lash|Disrupt Undead]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Double Slice"
    desc: "`pf2:2`  The Ekujae guardian makes two Strikes against the same target, one with each of their daggers. The guardian combines the damage of any attacks that hit and applies precision damage, resistance, and weaknesses only once. Both attacks count toward the guardian's multiple attack penalty, but the penalty increases only after both attacks."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The ekujae guardian deals 1d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Woodland Stride"
    desc: "  The Ekujae guardian ignores difficult terrain from plants."
 
```

```encounter-table
name: Ekujae Guardian
creatures:
  - 1: Ekujae Guardian
```




