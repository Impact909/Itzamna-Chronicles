---
title: "Poltergeist"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DDRDPsEzYIBgH6xi" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Poltergeist"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Poltergeist"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[spirit]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Intimidation: +15, Stealth: +14"
abilityMods: [-5, 5, 0, -1, 2, 4]
speed:  fly 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +9, __Ref__ +14, __Will__ +13"
hp: 55
health:
  - name: ""
  - name: HP
    desc: "55, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 5 (except force, ghost touch, vitality, or spirit; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Site Bound"
    desc: "  A poltergeist is tied to a location and can't travel more than 120 feet from the place where it was created or formed. Some poltergeists are instead bound to a specific room, building, or similar area"

abilities_mid:
  - name: ""
  - name: "Natural Invisibility"
    desc: "  A poltergeist is naturally [[Conditions/Invisible|Invisible]]. It becomes visible only when it uses Frighten."

  - name: "Rejuvenation"
    desc: " (occult) When a poltergeist is destroyed, it reforms, fully healed, where it was destroyed after 2d4 days. A poltergeist can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "Telekinetic Defense"
    desc: "`pf2:r`  **Trigger** A creature approaches within 10 feet of the poltergeist\n* * *\n\n**Effect** The poltergeist makes a telekinetic object Strike against the triggering creature."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Telekinetic Object"
    desc: "+13 (magical, occult, range increment 60 feet)\n__Damage__  2d12 untyped"

  - name: "Occult Innate Spells"
    desc: "DC 23, attack +13; __3rd __  _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver (At Will)]]_\n__Cantrips__  __(3rd)__ _[[Spells/Telekinetic Hand|Telekinetic Hand]]_"

  - name: "Frighten"
    desc: "`pf2:1` (concentrate,emotion,fear,incapacitation,mental) **Requirements** The poltergeist must be [[Conditions/Invisible|Invisible]]\n* * *\n\n**Effect** The poltergeist becomes visible, appearing as a skeletal, ghostlike humanoid. Each creature within 30 feet must attempt a DC 21 Will check save, becoming [[Conditions/Frightened|Frightened 2]] on a failure. On a critical failure, it's also [[Conditions/Fleeing|Fleeing]] for as long as it's frightened. On a success, the creature is temporarily immune for 1 minute.\n\nAt the start of its next turn, the poltergeist becomes invisible again."

  - name: "Telekinetic Storm"
    desc: "`pf2:2` (concentrate,occult) The poltergeist telekinetically throws numerous small objects, such as dozens of pieces of silverware or books, either spreading them out among multiple foes or directing them at one target.\n\n*   When this effect is spread out among multiple foes, the poltergeist makes a telekinetic object Strike at a -2 penalty against each creature within 30 feet. These count as one attack for the poltergeist's multiple attack penalty, and the penalty doesn't increase until after all the attacks.\n*   When this effect has only one target, the poltergeist makes a telekinetic object Strike against the target, and the damage increases to 3d12. It deals 1d12 untyped damage on a failure, and no damage on a critical failure."
 
```

```encounter-table
name: Poltergeist
creatures:
  - 1: Poltergeist
```



When a creature dies, and for whatever reason its spirit is unable or unwilling to leave the site of its death, that spirit may manifest as a poltergeist: a restless, invisible spirit that is still able to manipulate physical objects. Many poltergeists perished in a way that resulted from or led to extreme emotional trauma.
