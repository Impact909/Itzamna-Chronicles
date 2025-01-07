---
title: "Rust Zombie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.X8MKYDOxFdXpW3QU" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Rust Zombie"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Rusthenge"
name: "Rust Zombie"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 3
perception:
  - name: "Perception"
    desc: "+3; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +7"
abilityMods: [4, -2, 3, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder Adventure: Rusthenge_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +6, __Ref__ +3, __Will__ +4"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  A zombie is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+9 ()\n__Damage__  1d8 + 4 bludgeoning plus grab,rust-creep"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d12 + 4 piercing plus rust-creep"

  - name: "Rust Creep"
    desc: " (disease,divine) Those afflicted by rust creep develop uncomfortable rust-colored bruises on their flesh and endure full-body aches like those one might experience after a long workout. As the affliction progresses, their bodies—as well as the clothing and items they wear or carry—increasingly break down until a painful death occurs. If a character successfully resists contracting rust creep, or recovers from a case of rust creep, they are temporarily immune to future rust creep infections for 24 hours.\n\n**Saving Throw** DC 15 Fortitude check\n\n**Stage 1** –1 status penalty to Athletics checks (1 day)\n\n**Stage 2** as stage 1 (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 4** enfeebled 1 and [[Conditions/Stupefied|Stupefied 1]], plus any armor, clothing and items you carry and that are of a level equal to or less than the disease become broken as the decay spreads to them (1 day; broken items remain broken)\n\n**Stage 5** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 6** unconscious (1 day)\n\n**Stage 7** death"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Rust Zombie
creatures:
  - 1: Rust Zombie
```



Plague zombies are infested with hideous contagions.

* * *

A zombie's only desire is to consume the living. Unthinking and ever-shambling harbingers of death, zombies stop only when they're destroyed.
