---
title: "Pesgahi the Poisoner"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sL5LBuM3jmkHGNDl" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Pesgahi the Poisoner"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Pesgahi the Poisoner"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[ghoul]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Aklo, Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +8, Crafting: +12, Medicine: +9, Stealth: +11, Poison Lore: +12"
abilityMods: [1, 4, 2, 4, 1, 1]
speed: 30 feet,  burrow 5 feet
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +10, __Ref__ +12, __Will__ +11"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "6x [[Equipment/Acid Flask (Moderate)|Acid Flask (Moderate, Infused)]], 4x [[Equipment/Frost Vial (Moderate)|Frost Vial (Moderate, Infused)]], [[Equipment/Alchemist's Toolkit|Alchemist's Tools]], [[Equipment/Bracelet of Dashing|Bracelet of Dashing]], [[Equipment/Formula Book (Blank)|Formula Book]], 2x [[Equipment/Antidote (Lesser)|Antidote (Lesser, Infused)]], 2x [[Equipment/Smoke Ball (Lesser)|Smokestick (Lesser, Infused)]]"
  - name: "Infused Items"
    desc: "  Pesgahi carries the following infused items, which last for 24 hours or until the next time he makes his daily preparations: [[Equipment/Antidote (Lesser)|Antidote (Lesser)]] (2), [[Equipment/Smoke Ball (Lesser)|Smokestick (Lesser)]] (2), [[Equipment/Acid Flask (Moderate)|Acid Flask (Moderate)]] (6), [[Equipment/Frost Vial (Moderate)|Frost Vial (Moderate)]] (4)"

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 (finesse)\n__Damage__  2d6 + 5 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile, finesse)\n__Damage__  1d4 + 9 slashing plus ghoul-paralysis"

  - name: "**Ranged** `pf2:1` Acid Flask"
    desc: "+13 (range increment 20 feet, splash)\n__Damage__  1 acid 2d6 acid 2 acid"

  - name: "**Ranged** `pf2:1` Frost Vial"
    desc: "+13 (range increment 20 feet, splash)\n__Damage__  2d6 cold 2 cold"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** Pesgahi is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** Pesgahi devours a chunk of the corpse and regains 2d6 healing Hit Points.\n\nHe can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 19 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by Pesgahi's attack must succeed at a DC 19 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "Quick Bomber"
    desc: "`pf2:1`  Pesgahi can use Interact to draw a bomb and then Strike with it."

  - name: "Swift Leap"
    desc: "`pf2:1` (move) Pesgahi jumps up to half his Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Pesgahi the Poisoner
creatures:
  - 1: Pesgahi the Poisoner
```


Male ghoul poisoner


