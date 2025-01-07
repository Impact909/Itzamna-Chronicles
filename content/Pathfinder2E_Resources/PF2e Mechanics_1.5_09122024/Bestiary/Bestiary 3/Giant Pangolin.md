---
title: "Giant Pangolin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PsLyF8gtp9At9ksO" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Giant Pangolin"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Giant Pangolin"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +13, Stealth: +8, Survival: +10"
abilityMods: [5, 0, 3, -4, 2, 0]
speed: 30 feet,  burrow 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +8, __Will__ +10"
hp: 63
health:
  - name: ""
  - name: HP
    desc: "63"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile)\n__Damage__  1d10 + 7 piercing"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+13 ()\n__Damage__  1d6 + 7 bludgeoning plus grab"

  - name: "Devourer of Swarms"
    desc: "  The giant pangolin ignores the resistances of swarms, and its tongue Strike deals an additional 2d6 damage against swarms."

  - name: "Emit Musk"
    desc: "`pf2:1` (olfactory) The giant pangolin releases a disorienting and repulsive musk within a 5-foot emanation. Each creature in the area must attempt a DC 20 Fortitude check save.\n\nThe pangolin can't Emit Musk again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature becomes temporarily immune to pangolin musk for 1 minute.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Critical Failure** The creature becomes sickened 1 and is [[Conditions/Off-Guard|Off-Guard]] until no longer sickened."

  - name: "Roll Up"
    desc: "`pf2:1` (move) The giant pangolin falls [[Conditions/Prone|Prone]] and rolls up into a ball.\n\nWhile rolled up, the only actions the giant pangolin can perform are Emit Musk and Stand, and it also becomes [[Conditions/Blinded|Blinded]] and gains resistance 10 to physical damage.\n\nAn adjacent creature that hits a rolled-up giant pangolin with a melee Strike takes 1d6 slashing damage. These effects end once the giant pangolin Stands."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Pangolin
creatures:
  - 1: Giant Pangolin
```



Despite their prodigious size, giant pangolins are solitary, reclusive creatures who forage by night for insects and vermin. To defend themselves from predators, they rely on a veritable arsenal of natural defenses to dissuade their foes: thick armor of wickedly sharp scales, a flexible and muscular body capable of rolling into a defensive ball, and a noxious musk. Against more persistent threats, giant pangolins' powerful digging claws prove mighty weapons in a pinch.

While a pangolin's defenses serve well against natural predators, they've long been targets of poaching by humanoid cultures, partly for meat, but largely due to the high value of their unique scales. These scales see widespread use in alchemy, folk medicine, and crafting, and thus demand for them-and the associated profits from their sale-remain high. Giant pangolins are better protected against humanoid hunters, but the larger size of their scales means wider applications and greater volume. The increased difficulty of acquiring pangolins makes doing so all the more profitable, and unscrupulous poachers can make a considerable living from hunting these creatures.
