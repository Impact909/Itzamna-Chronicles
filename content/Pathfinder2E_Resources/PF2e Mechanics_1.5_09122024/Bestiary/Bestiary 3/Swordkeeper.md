---
title: "Swordkeeper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LIbGRUzJB19Pk7u3" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/lawful
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Swordkeeper"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Swordkeeper"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[construct]]
trait_02: [[lawful]]
trait_03: [[mindless]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +23"
abilityMods: [7, 5, 5, -5, 2, -5]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 29
armorclass:
  - name: AC
    desc: "29 (31 with guard raised); __Fort__ +21, __Ref__ +19, __Will__ +14"
hp: 285
health:
  - name: ""
  - name: HP
    desc: "285; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void,  mental"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|+1 Striking Vitalizing Longsword]]"
  - name: "Central Weapon"
    desc: "  A swordkeeper's torso houses a single weapon of a level no higher than the swordkeeper. While the swordkeeper is operational, the chamber requires four successful DC 32 Thievery check checks to [[Actions/Disable a Device|Disable a Device]] to open; on a critical failure, the backlash deals 6d6 force damage (DC 30 Reflex check save) to the creature attempting the check.\n\nIf the swordkeeper is [[Conditions/Immobilized|Immobilized]], [[Conditions/Grabbed|Grabbed]], [[Conditions/Prone|Prone]], or [[Conditions/Stunned|Stunned]], both DCs are reduced by 2.\n\nIf the weapon is removed, the swordkeeper's echoblades vanish."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Echoblade"
    desc: "+23 (magical, reach 10 feet, versatile p)\n__Damage__  2d8 + 13 slashing 1d8 force"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+23 (agile, reach 10 feet)\n__Damage__  2d8 + 13 bludgeoning"

  - name: "**Ranged** `pf2:1` Echoblade"
    desc: "+23 (agile, magical, thrown 30 ft.)\n__Damage__  2d8 + 13 slashing 1d8 force"

  - name: "Colossal Echo"
    desc: "`pf2:2` (force) **Requirements** The swordkeeper has a central weapon\n* * *\n\n**Effect** The swordkeeper projects a massive echoblade held in all four hands, dealing 9d8 force damage to all creatures in a 30-foot line (DC 30 Reflex check save).\n\nIt can't use Colossal Echo again for 1d4 rounds."

  - name: "Echoblade Flurry"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The swordkeeper makes two melee Echoblade Strikes. If both Strikes hit the same creature, combine their damage for the purpose of resistances and weakness. Apply the swordkeeper's multiple attack penalty normally."

  - name: "Project Echoblade"
    desc: "  **Requirements** The swordkeeper has a central weapon\n* * *\n\n**Effect** The swordkeeper projects an echoblade-a force copy of its central weapon that deals 1d8 force damage and gains thrown 30 feet. Echoblades inherit the weapon damage dice, weapon traits, and runes of the central weapon, but no other abilities or activations. The swordkeeper gains access to their critical specialization effects. The swordkeeper can have up to four echoblades at once; unattended echoblades vanish at the end of the swordkeeper's turn."

  - name: "Raise Guard"
    desc: "`pf2:1`  **Effect** The swordkeeper raises an echoblade to protect itself, gaining a +2 circumstance bonus to AC until the start of its next turn.\n\n[[Bestiary Effects/Effect_ Raise Guard|Effect: Raise Guard]]"
 
```

```encounter-table
name: Swordkeeper
creatures:
  - 1: Swordkeeper
```



Collectors who want to guard their magical arsenals procure or build swordkeepers. These constructs are equal parts display case and security system, each holding a single weapon within its body and projecting copies of the weapon it stores to deter would-be thieves.
