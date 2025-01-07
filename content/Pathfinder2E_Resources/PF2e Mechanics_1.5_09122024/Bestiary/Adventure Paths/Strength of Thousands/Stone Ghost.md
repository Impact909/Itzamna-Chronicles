---
title: "Stone Ghost"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.lvz1lxe8WW5ibot7" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/oread
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Stone Ghost"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #169: Kindled Magic"
name: "Stone Ghost"
level: "Creature 5"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[oread]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; "
languages: "Common, Kholo, Petran"
skills:
  - name: "Skills"
    desc: "Arcana: +12, Athletics: +12, Intimidation: +12, Nature: +13, Stealth: +11, Magaambya Lore: +12"
abilityMods: [3, 0, 4, 3, 4, 1]
speed: 25 feet
sourcebook: "_Pathfinder #169: Kindled Magic_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +11, __Ref__ +9, __Will__ +15"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Resistances__ all damage 5 (except force or ghost touch; double resistance vs. non-magical or earth)"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Morningstar|+1 Morningstar]], [[Equipment/Sling|Sling]], [[Equipment/Leather Armor|Leather Armor]], 10x [[Equipment/Sling Bullets|Sling Bullets]]"
  - name: "Stone Spirit"
    desc: "  Stone Ghost can pass through objects made of stone or soil, including walls. When inside an object, Stone Ghost can't perceive, attack, or interact with anything outside the object, and if he starts his turn inside an object, he is [[Conditions/Slowed|Slowed 1]]."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Morningstar"
    desc: "+15 (magical, versatile p)\n__Damage__  1d6 + 5 bludgeoning"

  - name: "**Ranged** `pf2:1` Sling"
    desc: "+11 (propulsive, range increment 50 feet, reload 1)\n__Damage__  1d6 + 5 bludgeoning"

  - name: "Prepared Primal Spells"
    desc: "DC 22, attack +14; __3rd __  _[[Spells/Earthbind|Earthbind]]_; __2nd __  _[[Spells/Darkvision|Darkvision]]_, _[[Spells/Revealing Light|Glitterdust]]_, _[[Spells/Shatter|Shatter]]_, _[[Spells/Summon Elemental|Summon Elemental (Earth Only)]]_; __1st __  _[[Spells/Command|Command (Animals Only)]]_, _[[Spells/Grease|Grease]]_, _[[Spells/Vanishing Tracks|Pass Without Trace]]_\n__Cantrips__  __(3rd)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Know the Way|Know Direction]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Tangle Vine|Tanglefoot]]_"

  - name: "Entombing Grasp"
    desc: "`pf2:2` (earth,manipulate) **Requirements** A foe within Stone Ghost's reach is standing on stone or soil\n* * *\n\n**Effect** Stone Ghost briefly extends his intangibility to a foe and drags or pounds them into the earth. He makes an Athletics check check against the target's Fortitude DC. On a success, the foe is planted waist-deep in the ground and is immobilized and off-guard until it Escapes (DC 22). On a critical success, the foe is completely buried and must hold its breath until it is free or else start suffocating. A successful Escape returns the foe to its original square on the surface, or the closest unoccupied square."
 
```

```encounter-table
name: Stone Ghost
creatures:
  - 1: Stone Ghost
```




