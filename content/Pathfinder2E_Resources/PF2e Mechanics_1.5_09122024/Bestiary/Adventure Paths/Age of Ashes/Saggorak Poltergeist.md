---
title: "Saggorak Poltergeist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y8x3xLmQJZlOuNn8" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Saggorak Poltergeist"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #148: Fires of the Haunted City"
name: "Saggorak Poltergeist"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[lawful]]
trait_04: [[spirit]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Dwarven, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Intimidation: +24, Stealth: +25"
abilityMods: [-5, 7, 2, -1, 4, 5]
speed:  fly 30 feet
sourcebook: "_Pathfinder #148: Fires of the Haunted City_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +18, __Ref__ +25, __Will__ +22"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, rejuventation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  The Saggorak poltergeist cannot travel more than 120 feet from area **F2**."

abilities_mid:
  - name: ""
  - name: "Natural Invisibility"
    desc: "  A poltergeist is naturally [[Conditions/Invisible|Invisible]]. It becomes visible only when it uses Frighten."

  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "Telekinetic Defense"
    desc: "`pf2:r`  **Trigger** A creature approaches within 10 feet of the poltergeist.\n* * *\n\n**Effect** The poltergeist makes a telekinetic object Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Telekinetic Object"
    desc: "+27 (magical, occult, range increment 60 feet)\n__Damage__  4d12 untyped"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +27; __6th __  _[[Spells/Telekinetic Haul|Telekinetic Haul (At Will)]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_\n__Cantrips__  __(6th)__ _[[Spells/Telekinetic Hand|Mage Hand]]_"

  - name: "Frighten"
    desc: "`pf2:1` (concentrate,emotion,fear,incapacitation,mental) **Requirement** The poltergeist must be [[Conditions/Invisible|Invisible]].\n* * *\n\n**Effect** The poltergeist becomes visible, appearing as a skeletal, ghostlike humanoid. Each creature within 30 feet must attempt a DC 33 Will check save, becoming [[Conditions/Frightened|Frightened 2]] on a failure. On a critical failure, it's also [[Conditions/Fleeing|Fleeing]] for as long as it's frightened. On a success, the creature is temporarily immune for 1 minute.\n\nAt the start of its next turn, the poltergeist becomes invisible again."

  - name: "Telekinetic Storm"
    desc: "`pf2:2` (concentrate,occult) The poltergeist telekinetically throws numerous small and jagged chunks of stone rubble, either spreading them out among multiple foes or directing them at one target.\n\n*   When this effect is spread out among multiple foes, the poltergeist makes a telekinetic object Strike at a -2 penalty against each creature within 30 feet. These count as one attack for the poltergeist's multiple attack penalty, and the penalty doesn't increase until after all the attacks.\n*   When this effect has only one target, the poltergeist makes a telekinetic object Strike against the target, and the damage increases to 6d12. It deals 2d12 untyped damage on a failure, and no damage on a critical failure."
 
```

```encounter-table
name: Saggorak Poltergeist
creatures:
  - 1: Saggorak Poltergeist
```




