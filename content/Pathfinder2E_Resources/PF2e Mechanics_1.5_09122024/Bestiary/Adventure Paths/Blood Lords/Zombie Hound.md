---
title: "Zombie Hound"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6YYbtruDeah33dJa" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/-1
statblock: inline
name: "Zombie Hound"
level: -1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Zombie Hound"
level: "Creature -1"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[zombie]]
modifier: 1
perception:
  - name: "Perception"
    desc: "+1; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +5"
abilityMods: [2, -1, 2, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__ +5, __Ref__ +0, __Will__ +3"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 5, slashing 5"
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

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+6 ()\n__Damage__  1d4 + 3 piercing plus knockdown"

  - name: "Flesh Tearer"
    desc: "  The zombie hound's Strikes deal 1d4 extra damage to [[Conditions/Prone|Prone]] creatures."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Zombie Hound
creatures:
  - 1: Zombie Hound
```




