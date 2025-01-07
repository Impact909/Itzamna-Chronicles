---
title: "Hollow Husk"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.t1ti6fnSBzu1Bfxo" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Hollow Husk"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Hollow Husk"
level: "Creature 5"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +14"
abilityMods: [5, -1, 4, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder #183: Field of Maidens_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +15, __Ref__ +9, __Will__ +11"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  A hollow husk is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+15 ()\n__Damage__  2d8 + 7 bludgeoning plus grab"

  - name: "Memory Drain"
    desc: "`pf2:1`  **Requirements** The hollow husk has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** Memories flow from the grabbed creature into the empty void that is the hollow husk's mind. The hollow husk deals the creature 3d6 mental damage, and the creature must attempt a DC 16 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is [[Conditions/Stupefied|Stupefied 1]] for 1 minute.\n\n**Critical Failure** The creature takes full damage and is [[Conditions/Stupefied|Stupefied 2]] for 1 minute."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Hollow Husk
creatures:
  - 1: Hollow Husk
```




