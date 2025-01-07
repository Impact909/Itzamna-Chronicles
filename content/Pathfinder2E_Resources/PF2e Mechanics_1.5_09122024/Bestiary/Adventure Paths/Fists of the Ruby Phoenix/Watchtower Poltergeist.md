---
title: "Watchtower Poltergeist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NS58bpNJAavxmmpJ" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Watchtower Poltergeist"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #166: Despair on Danger Island"
name: "Watchtower Poltergeist"
level: "Creature 14"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[lawful]]
trait_04: [[spirit]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "Tien"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Intimidation: +30, Stealth: +29"
abilityMods: [-5, 8, 2, -1, 4, 7]
speed:  fly 20 feet
sourcebook: "_Pathfinder #166: Despair on Danger Island_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +22, __Ref__ +27, __Will__ +26"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 15 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Creature Family Ability Glossary/(Ghost) Site Bound|Site Bound]]"
    desc: "  The poltergeist is tied to its watchtower.\n* * *\n\nA typical ghost can stray only a short distance from where it was killed or the place it haunts. A typical limit is 120 feet. Some ghosts are instead bound to a room, building, item, or creature that was special to it rather than a location."

abilities_mid:
  - name: ""
  - name: "Natural Invisibility"
    desc: "  A poltergeist is naturally [[Conditions/Invisible|Invisible]]. It becomes visible only when it uses Frighten."

  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When the watchtower poltergeist is destroyed, it re-forms, fully healed, at the watchtower after 12 hours. Destroying the poltergeist and lighting its watchtower's brazier permanently destroys it."

  - name: "Telekinetic Defense"
    desc: "`pf2:r`  **Trigger** A creature approaches within 10 feet of the poltergeist.\n* * *\n\n**Effect** The poltergeist makes a telekinetic object Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Telekinetic Object"
    desc: "+27 (magical, occult, range increment 60 feet)\n__Damage__  3d12 + 10 untyped"

  - name: "Occult Innate Spells"
    desc: "DC 35, attack +25; __7th __  _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Telekinetic Hand|Mage Hand]]_"

  - name: "Frighten"
    desc: "`pf2:1` (concentrate,emotion,fear,incapacitation,mental) **Requirements** The poltergeist must be [[Conditions/Invisible|Invisible]].\n* * *\n\n**Effect** The poltergeist becomes visible, appearing as a skeletal, ghostlike humanoid. Each creature within 30 feet must attempt a DC 33 Will check save, becoming [[Conditions/Frightened|Frightened 2]] on a failure. On a critical failure, it's also [[Conditions/Fleeing|Fleeing]] for as long as it's frightened. On a success, the creature is temporarily immune for 1 minute. At the start of its next turn, the poltergeist becomes invisible again."

  - name: "Telekinetic Storm"
    desc: "`pf2:2` (concentrate,occult) The poltergeist telekinetically throws numerous small objects, such as dozens of pieces of silverware or books, either spreading them out among multiple foes or directing them at one target. When this effect is spread out among multiple foes, the poltergeist makes a telekinetic object Strike at a -2 penalty against each creature within 30 feet. These count as one attack for the poltergeist's multiple attack penalty, and the penalty doesn't increase until after all the attacks. When this effect has only one target, the poltergeist makes a telekinetic object Strike against the target, and the damage increases to 4d12+15. It deals 2d12 untyped damage on a failure, and no damage on a critical failure."
 
```

```encounter-table
name: Watchtower Poltergeist
creatures:
  - 1: Watchtower Poltergeist
```


Variant poltergeist

When a creature dies, and for whatever reason its spirit is unable or unwilling to leave the site of its death, that spirit may manifest as a poltergeist: a restless invisible spirit that is still able to manipulate physical objects. Many poltergeists perished in a way that resulted from or has led to extreme emotional trauma.
