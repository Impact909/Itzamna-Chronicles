---
title: "Giant Tardigrade"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ProFRznmy7BOYifo" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Giant Tardigrade"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Giant Tardigrade"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[animal]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +19, Stealth: +14, Survival: +18"
abilityMods: [4, 3, 6, -5, 3, 1]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +23, __Ref__ +16, __Will__ +16"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Resistances__ all damage 10"
abilities_top:
  - name: ""

  - name: "Eyespots"
    desc: "  A giant tardigrade can't see anything beyond 30 feet."

abilities_mid:
  - name: ""
  - name: "Tun State"
    desc: "`pf2:0`  **Trigger** The tardigrade would be reduced to 0 Hit Points or would die due to starvation, suffocation, or similar environmental causes\n\n**Frequency** once per week\n\n**Requirements** The tardigrade isn't already in tun state\n* * *\n\n**Effect** The giant tardigrade doesn't die but instead remains at 1 Hit Point and curls into a dry ball, called a tun. While in this tun state, the giant tardigrade is [[Conditions/Unconscious|Unconscious]], doesn't need to eat, drink, or breathe, and doubles its resistance to 20. It remains in tun state indefinitely until covered in significant amounts of water, at which point it begins to rehydrate, gaining regeneration 5. The regeneration persists until it reaches maximum Hit Points. The giant tardigrade then exits its tun state."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Stylet"
    desc: "+19 ()\n__Damage__  3d8 + 6 piercing 1d8 bleed"

  - name: "**Melee** `pf2:1` Claws"
    desc: "+19 (agile, reach 10 feet)\n__Damage__  3d6 + 6 slashing plus grab"

  - name: "Vacuum Mouth"
    desc: "`pf2:2`  **Requirements** The giant tardigrade doesn't have a target [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The giant tardigrade draws in air with its mouth. All creatures in a 20-foot cone must succeed at a DC 25 Reflex check save or be pulled adjacent to the giant tardigrade. The tardigrade chooses one creature that failed its save, Grabbing the target in its claws and making a stylet Strike."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Tardigrade
creatures:
  - 1: Giant Tardigrade
```




