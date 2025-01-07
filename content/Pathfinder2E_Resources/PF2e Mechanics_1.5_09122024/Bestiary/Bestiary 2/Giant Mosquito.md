---
title: "Giant Mosquito"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.l6KWr5lj3CwH8fvF" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Giant Mosquito"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Mosquito"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision, Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Stealth: +13"
abilityMods: [4, 5, 2, -5, 2, -5]
speed: 20 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +14, __Ref__ +17, __Will__ +12"
hp: 80
health:
  - name: ""
  - name: HP
    desc: "80"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Proboscis"
    desc: "+17 (finesse)\n__Damage__  2d10 + 7 piercing plus grab,septic-malaria"

  - name: "Blood Drain"
    desc: "`pf2:1`  **Requirements** The giant mosquito has a creature grabbed\n* * *\n\n**Effect** The giant mosquito uses its proboscis to drain blood from the grabbed creature. This deals 3d6 damage, and the giant mosquito gains temporary Hit Points equal to the damage dealt. A creature that has its blood drained by a giant mosquito is [[Conditions/Drained|Drained 1]] until it receives healing of any kind or amount."

  - name: "Septic Malaria"
    desc: " (disease) The victim can't reduce its [[Conditions/Sickened|Sickened]] condition while it's affected by septic malaria\n\n**Saving Throw** DC 24 Fortitude check\n\n**Onset** 1 day\n\n**Stage 1** [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 1]] and [[Conditions/Sickened|Sickened 1]] (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 5** dead"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Mosquito
creatures:
  - 1: Giant Mosquito
```



These horrifically enlarged versions of the common mosquito often prey upon megafauna like dinosaurs and other large creatures, but they won't turn down a chance to drink the blood of a smaller target-such as a humanoid.
