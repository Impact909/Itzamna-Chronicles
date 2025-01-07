---
title: "Sand Wolf"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.z8ZhZQbqqx9Xf74a" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/beast
  - pf2e/creature/type/earth
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Sand Wolf"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: The Enmity Cycle"
name: "Sand Wolf"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[air]]
trait_02: [[beast]]
trait_03: [[earth]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Low-Light Vision, Tremorsense (Imprecise) 30 Feet"
languages: "Petran, Sussuran; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Performance: +13, Stealth: +11, Survival: +12"
abilityMods: [5, 4, 2, -2, 2, 3]
speed: 30 feet,  burrow 20 feet,  fly 20 feet
sourcebook: "_Pathfinder Adventure: The Enmity Cycle_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +12, __Ref__ +15, __Will__ +9"
hp: 92
health:
  - name: ""
  - name: HP
    desc: "92; __Weaknesses__ water 5; __Resistances__ acid 5, electricity 5, piercing 5, slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Collapse Into Sand"
    desc: "`pf2:r`  **Trigger** The sand wolf is hit by an attack\n* * *\n\n**Effect** The sand wolf's body falls apart into a cloud of sand. It takes no damage from the triggering attack, and its resistances increase to 8. The sand wolf must spend one action to reform its body before it can move or attack."

  - name: "Water Vulnerability"
    desc: "  Sand wolves take 5 additional damage from attacks and effects with the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  2d6 + 5 piercing plus grab"

  - name: "**Ranged** `pf2:1` Sand Blast"
    desc: "+12 (range 30 feet)\n__Damage__  2d10 slashing"

  - name: "Choking Sands"
    desc: "`pf2:2` (air,earth,primal) The sand wolf discorporates into a cloud of whirling sand. It can Stride, moving freely through occupied spaces. Any creatures within those spaces take 2d10 damage and must attempt a DC 19 Reflex check save.\n* * *\n\n**Critical Success** The target takes no damage.\n\n**Success** The target takes half damage.\n\n**Failure** The target takes full damage and is [[Conditions/Sickened|Sickened 1]].\n\n**Critical Failure** As failure, but the effect is increased to [[Conditions/Sickened|Sickened 3]]."

  - name: "Susurrating Song"
    desc: "`pf2:1` (air,earth,primal,sonic) The sand wolf sings a short, enchanting song. Any creature other than a sand wolf within 30 feet must attempt a DC 19 Will check save.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune to further susurrating song exposures for 24 hours.\n\n**Success** The target is [[Conditions/Stupefied|Stupefied 1]].\n\n**Failure** The target is [[Conditions/Stupefied|Stupefied 2]].\n\n**Critical Failure** As failure, and the target is [[Conditions/Slowed|Slowed 1]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sand Wolf
creatures:
  - 1: Sand Wolf
```



A sand wolf is an elemental creature which dwells in the sandy deserts of elemental earth that drift to, or have been conjured on, the Plane of Air. Occasionally, these creatures seep through planar rifts or are summoned by elementalists on the Material Plane. Sand wolves are prized as guardians for their relative intelligence, keen perception, and ability to disguise themselves, easily blending with the shifting sands in desert terrain. Cunning and agile, they fiercely pursue any creatures they ambush, no matter how nimble their prey. Sand wolves also have a remarkable ability to sing beautiful, haunting songs, and their music is considered high entertainment among djinn who inhabit the Plane of Air. Many djinni viziers and even certain Material Plane rulers seeking the attention of their peers keep at least one of these creatures in their employ to show off at special events and ceremonies. The wolves' wordless songs evoke both the strength of the earth and the power of wind to erode it.

## The Eternal Hourglass

Deep within a cavern in the Plane of Earth is a massive, seemingly indestructible hourglass the size of a small city, its top filled with thousands of sand wolves. As each wolf reaches the opening to the bottom, they are turned to sand and do not reform, instead piling up in a huge mound. It is not clear who constructed or placed the hourglass, how the sand wolves got there, or what—if anything—the hourglass is timing. Some claim the wolves will break loose and rampage freely when the sand runs out, while others believe the glass is counting down to the end of time itself.
