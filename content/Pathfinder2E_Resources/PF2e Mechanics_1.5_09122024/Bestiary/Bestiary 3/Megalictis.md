---
title: "Megalictis"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rig6OFLAb9lOPj52" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Megalictis"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Megalictis"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +8, Stealth: +9"
abilityMods: [3, 4, 3, -4, 1, 0]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +8, __Ref__ +11, __Will__ +6"
hp: 42
health:
  - name: ""
  - name: HP
    desc: "42"
abilities_top:
  - name: ""

  - name: "Lithe"
    desc: "  A megalictis treats any tight space it can barely fit its head in or wider as difficult terrain and doesn't need to [[Actions/Squeeze|Squeeze]] to move through it."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (finesse)\n__Damage__  1d12 + 5 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile, finesse)\n__Damage__  1d10 + 5 slashing"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d12+2 piercing, DC 20 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Megalictis
creatures:
  - 1: Megalictis
```



These giant weasels are driven by the same hunger that plagues their smaller cousins, but because of their much larger size, they can quickly devastate the wildlife in an environment. They tend to avoid humanoids but have been known to attack if driven by hunger or fear.

A megalictis uses the same constricting bite as smaller weasels, remaining attached even if other creatures attack. Given their remarkable stature, a megalictis can take down sizable prey, including horses and even the occasional bear, if the opportunity presents itself.

A megalictis can grow to be 5 feet long and weighs around 150 pounds.

* * *

Weasels are lithe, clever predators known for both their beautiful, sleek fur and their ability to crawl into tight spaces. Pound for pound, few animals are as voracious as weasels. Insatiably hungry, they eat almost half their own weight each day, leading them to constantly hunt for new prey to satisfy their hunger.
