---
title: "Trollhound"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gbCdrmPVgcgVfn4w" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/troll
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Trollhound"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Trollhound"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[troll]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +11, Stealth: +8, Survival: +6"
abilityMods: [4, 1, 5, -4, 1, -2]
speed: 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +14, __Ref__ +8, __Will__ +6"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65, regeneration 15 (deactivated by acid or fire); __Weaknesses__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Acid or Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 ()\n__Damage__  1d12 + 4 piercing plus bloodfire-fever,knockdown"

  - name: "Bloodfire Fever"
    desc: " (disease) **Saving Throw** DC 18 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** Enfeebled 1 and [[Conditions/Clumsy|Clumsy 1]] (1 day)\n\n**Stage 4** [[Conditions/Enfeebled|Enfeebled 2]] and [[Conditions/Clumsy|Clumsy 2]] (1 day)\n\n**Stage 5** Enfeebled 2, Clumsy 2, and [[Conditions/Fatigued|Fatigued]] (1 day)"

  - name: "Pack Attack"
    desc: "  The trollhound deals an extra 1d6 damage to any creature within reach of at least two of the trollhound's allies."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Trollhound
creatures:
  - 1: Trollhound
```



Trollhounds are squat, slavering beasts akin to trolls in canine form. Requiring vast quantities of meat to fuel their regenerative metabolisms, packs of wild trollhounds prowl the foothills of regions where trolls dwell, their voracious hunger driving them to slaughter and consume any prey they encounter. In some regions, trolls breed trollhounds as pets, utilizing the trollhounds' keen sense of smell to aid in the hunt.

Covered in fetid, weeping sores, trollhounds are carriers of a debilitating contagion known as bloodfire fever. Creatures that contract the disease through the bite of a trollhound experience deep internal pain, as if their blood were on fire. Additional symptoms include loss of muscle coordination, pus-filled blisters, and overall lethargy and fatigue. Other than suffering from skin irritation, both trolls and trollhounds are immune to the major effects of the disease.

Trollhounds are fearless on the hunt and in combat, relying on their ability to regenerate to carry them through. Not even the threat of fire is enough to repel them, as the beasts don't recognize the danger it represents. Nevertheless, fire is one of the most effective tools in combating trollhounds; canny hunters know to burn every last remnant of a supposedly slain trollhound, for their regenerative powers are potent indeed.

While trolls themselves have had great success in domesticating, training, and even befriending trollhounds, the same cannot be said for other would-be masters. Whether impeded by constant exposure to trollhounds' diseased slobber, their ravenous hunger that never seems to be fully sated, or simply their foul personality and quick-to-bite temperament, most attempts to use trollhounds in place of more reliable guardians end in pain, misery, and a pack of feral trollhounds escaping into the hinterlands. Left to their own devices, a pack of escaped trollhounds can breed relatively quickly, and it can take less than a year for a small pack to multiply into a significant threat to the countryside. Best to leave the trollhounds to the trolls, as they say!
