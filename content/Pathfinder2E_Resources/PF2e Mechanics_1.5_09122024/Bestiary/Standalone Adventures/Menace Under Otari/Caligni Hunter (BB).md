---
title: "Caligni Hunter (BB)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.FIwvS7YngK5xrZ43" 
tags:
  - pf2e/creature/type/caligni
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Caligni Hunter (BB)"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Beginner Box"
name: "Caligni Hunter (BB)"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[caligni]]
trait_02: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +8, Stealth: +13, Survival: +12, Thievery: +11"
abilityMods: [2, 5, 2, -1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Beginner Box_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +0, __Ref__ +0, __Will__ +0"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Shortsword|Shortsword]], [[Equipment/Leather Armor|Leather Armor]]"
  - name: "[[Menace Under Otari/Caligni Dancer (BB)/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the caligni can't see until the end of their next turn. All squares are difficult terrain for them, and they take a -4 status penalty to Perception. If they try to attack a creature, the attack fails unless they succeed at a DC 11 Flat check. Light doesn't blind them again for 1 hour."

  - name: "[[Bestiary Ability Glossary/Darkvision|Sneak Attack]]"
    desc: "  The caligni hunter deals an extra 1d6 damage to creatures that have the [[Conditions/Off-Guard|Off-Guard]] condition."

abilities_mid:
  - name: ""
  - name: "[[Menace Under Otari/Caligni Dancer (BB)/Final Fate|Final Fate]]"
    desc: "  When a caligni hunter dies, their body explodes. All creatures within 20 feet must take 5d6 fire. Each creature in the area must attempt a DC 19 Reflex check save."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+13 (agile, finesse, versatile s)\n__Damage__  1d6 + 7 piercing plus darkening-poison"

  - name: "Occult Innate Spells"
    desc: "DC 19, attack +11; __2nd __  _[[Spells/See the Unseen|See the Unseen (At Will)]]_\n__Cantrips__  __(2nd)__ _[[Spells/Figment|Figment]]_"

  - name: "Darkening Poison"
    desc: "`pf2:1` (poison) The next time the hunter deals damage with a shortsword Strike, the target must succeed at a DC 16 Fortitude check save or take 1d8 poison damage and treat all creatures as [[Conditions/Concealed|Concealed]] for 1 round."
 
```

```encounter-table
name: Caligni Hunter (BB)
creatures:
  - 1: Caligni Hunter (BB)
```



Caligni lurk in subterranean cities, and they relish the chance to creep above ground at night to steal resources, spy on surface dwellers, or simply cause mischief.
