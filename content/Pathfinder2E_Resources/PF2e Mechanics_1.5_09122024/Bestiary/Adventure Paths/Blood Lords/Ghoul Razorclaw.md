---
title: "Ghoul Razorclaw"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aUEKIGXnBc9ffNFS" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Ghoul Razorclaw"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Ghoul Razorclaw"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[ghoul]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Chthonian, Common, Draconic, Kelish, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +24, Deception: +24, Diplomacy: +24, Intimidation: +24, Medicine: +24, Society: +24, Stealth: +27, Thievery: +27, Underworld Lore: +24"
abilityMods: [6, 7, 2, 5, 4, 5]
speed: 40 feet,  climb 30 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +20, __Ref__ +26, __Will__ +23"
hp: 230
health:
  - name: ""
  - name: HP
    desc: "230, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Shortbow|+1 Striking Composite Shortbow]], [[Equipment/Leather Armor|Leather Armor]], [[Equipment/Thieves' Toolkit (Infiltrator)|Thieves' Tools (Infiltrator)]], 20x [[Equipment/Arrows|Arrows]], 3x [[Equipment/Nethershade|Shadow Essence]]"
abilities_mid:
  - name: ""
  - name: "Deny Advantage"
    desc: "  The razorclaw isn't [[Conditions/Off-Guard|Off-Guard]] to creatures of 13th level or lower that are [[Conditions/Hidden|Hidden]], [[Conditions/Undetected|Undetected]], flanking, or using [[Class Features/Surprise Attack|Surprise Attack]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (finesse)\n__Damage__  3d8 + 12 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile, finesse)\n__Damage__  3d6 + 12 slashing plus adamantine-edges"

  - name: "**Ranged** `pf2:1` Composite Shortbow"
    desc: "+27 (deadly d10, magical, propulsive, range increment 60 feet, reload 0)\n__Damage__  2d6 + 10 piercing"

  - name: "Adamantine Edges"
    desc: "  The ghoul's claws have been dipped in adamantine. The razorclaw treats any object they hit with a claw Strike as if it had half as much Hardness and any creature they hit as if they had half as much physical resistance."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghoul devours a chunk of the corpse and regains 7d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 31 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 4d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 4d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul's attack must succeed at a DC 31 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The ghoul razorclaw deals an extra 3d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "Surprise Attacker"
    desc: "  On the first round of combat, creatures that haven't acted yet are [[Conditions/Off-Guard|Off-Guard]] to the ghoul razorclaw."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghoul razorclaw jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Ghoul Razorclaw
creatures:
  - 1: Ghoul Razorclaw
```



Ghoul assassins who survive dipping their claws in molten adamantine transform into razorclaws.
