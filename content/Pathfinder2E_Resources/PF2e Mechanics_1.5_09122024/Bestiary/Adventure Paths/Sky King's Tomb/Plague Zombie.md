---
title: "Plague Zombie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CcpKYQFjw3X9hvsb" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fungus
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Plague Zombie"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #193: Mantle of Gold"
name: "Plague Zombie"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[fungus]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
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
sourcebook: "_Pathfinder #193: Mantle of Gold_"
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
    desc: "+9 ()\n__Damage__  1d8 + 4 bludgeoning plus grab,zombie-rot"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 ()\n__Damage__  1d12 + 4 piercing plus zombie-rot"

  - name: "Zombie Rot"
    desc: " (disease) An infected creature can't heal damage it takes from zombie rot until it has been cured of the disease.\n* * *\n\n**Saving Throw** DC 18 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 1d6 void damage (1 day)\n\n**Stage 3** 1d6 void damage (1 day)\n\n**Stage 4** 1d6 void damage (1 day)\n\n**Stage 5** dead, rising as a plague zombie immediately"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Plague Zombie
creatures:
  - 1: Plague Zombie
```


Variant Plague Zombie

Plague zombies are infested with hideous contagions.

* * *

A zombie's only desire is to consume the living. Unthinking and ever-shambling harbingers of death, zombies stop only when they're destroyed.
