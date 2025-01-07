---
title: "Tar Zombie Snatcher"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PfLpfTCMRDeAaBFo" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Tar Zombie Snatcher"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #177: Burning Tundra"
name: "Tar Zombie Snatcher"
level: "Creature 6"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15, Stealth: +10"
abilityMods: [5, 0, 4, -5, 1, -3]
speed: 25 feet,  climb 10 feet
sourcebook: "_Pathfinder #177: Burning Tundra_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +18, __Ref__ +10, __Will__ +13"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ fire 5, vitality 5, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Flammable"
    desc: "  A tar zombie requires a successful DC 20 flat check to recover from persistent fire damage. This DC isn't reduced for assisted recovery."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+17 ()\n__Damage__  2d8 + 8 bludgeoning plus improved-grab"

  - name: "Vomit Tar"
    desc: "`pf2:2` (primal) The tar zombie vomits a gout of sticky tar in a 15-foot cone that deals 5d6 bludgeoning damage ((DC 24 Reflex check) save). Creatures that fail the save are [[Conditions/Slowed|Slowed 1]] and gain fire weakness 5. Both conditions end after 3 rounds or when the tar is scrubbed off (which requires 3 Interact actions). The tar zombie can't Vomit Tar again for 1d4 rounds.\n\n[[Bestiary Effects/Effect_ Vomit Tar|Effect: Vomit Tar]]"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Tar Zombie Snatcher
creatures:
  - 1: Tar Zombie Snatcher
```




