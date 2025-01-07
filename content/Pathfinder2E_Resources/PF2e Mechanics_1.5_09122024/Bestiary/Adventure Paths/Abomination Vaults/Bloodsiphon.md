---
title: "Bloodsiphon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.irE5rIXYlThP4rDA" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Bloodsiphon"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Bloodsiphon"
level: "Creature 4"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Tremorsense (Imprecise) 30 Feet"
languages: "Aklo; cannot speak any language"
skills:
  - name: "Skills"
    desc: "Athletics: +12"
abilityMods: [4, 1, 3, -2, 3, -2]
speed: 10 feet,  swim 20 feet
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +11, __Ref__ +7, __Will__ +11"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Death Burst"
    desc: " (occult) When the bloodsiphon dies, its body explodes in a cloudy red burst of necrotic dried blood in a 20-foot area.\n\nCreatures in range must attempt a DC 21 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 2d6 void damage.\n\n**Failure** The creature takes 4d6 void damage.\n\n**Critical Failure** The creature takes 6d6 void damage and is [[Conditions/Enfeebled|Enfeebled 2]] for 1 hour."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mouth"
    desc: "+14 ()\n__Damage__  2d8 + 6 piercing plus grab"

  - name: "**Ranged** `pf2:1` Spittle"
    desc: "+11 (range 30 feet)\n__Damage__  3d6 void"

  - name: "Blood Drain"
    desc: "`pf2:1`  **Requirements** The bloodsiphon has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The bloodsiphon drains blood from the creature it has grabbed. This deals 4d4 untyped damage and the bloodsiphon grows temporarily moist and slimy as it regains 8 healing Hit Points, gaining any excess as temporary Hit Points that last for 1 minute.\n\nA creature that has its blood drained by the bloodsiphon is [[Conditions/Drained|Drained 1]] until it receives any type of healing."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Bloodsiphon
creatures:
  - 1: Bloodsiphon
```




