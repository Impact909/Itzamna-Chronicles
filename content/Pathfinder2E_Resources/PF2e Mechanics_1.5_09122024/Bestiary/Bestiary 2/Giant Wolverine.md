---
title: "Giant Wolverine"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bCLurZHbR7CjO6wu" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Giant Wolverine"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Wolverine"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +12, Stealth: +11"
abilityMods: [6, 3, 3, -4, 3, 0]
speed: 25 feet,  climb 10 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +11, __Will__ +9"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 ()\n__Damage__  2d6 + 8 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile)\n__Damage__  2d4 + 8 slashing"

  - name: "Gnaw"
    desc: "`pf2:1`  **Requirements** The wolverine has a creature grabbed from its jaws Strike\n* * *\n\n**Effect** The wolverine chews violently on the creature, dealing 2d6 piercing damage (DC 21 Fortitude check save). A creature that fails its save also takes 2d6 bleed."

  - name: "Pounce"
    desc: "`pf2:1`  The giant wolverine Strides and makes a Strike at the end of that movement. If the giant wolverine begins this action [[Conditions/Hidden|Hidden]], it remains hidden until after the attack."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Wolverine Rage"
    desc: "`pf2:1` (concentrate) The giant wolverine enters a state of pure rage that lasts either for 1 minute, until there are no enemies it can perceive, or until it falls [[Conditions/Unconscious|Unconscious]], whichever comes first. While raging, the giant wolverine has AC 20, its jaws Strike deals 2d6+11 damage, and its claw Strike deals 2d4+11 damage. While raging, the giant wolverine can't use actions that have the concentrate trait, except for [[Actions/Seek|Seek]].\n\nAfter it's stopped raging, a giant wolverine can't use Wolverine Rage again for 1 minute."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Wolverine
creatures:
  - 1: Giant Wolverine
```



Giant wolverines grow to the approximate size of horses and claim even more expansive territories than their more diminutive wolverine cousins. While a smaller wolverine will defend its prey from armed humanoids, a giant wolverine is unafraid to stalk and kill such creatures.
