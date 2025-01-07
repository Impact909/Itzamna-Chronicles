---
title: "Giant Amoeba"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.aCcsjWL8hbyT483x" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Giant Amoeba"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Amoeba"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[amphibious]]
trait_02: [[mindless]]
trait_03: [[ooze]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +3"
abilityMods: [3, -2, 2, -5, 0, -5]
speed: 10 feet,  climb 10 feet,  swim 10 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 8
armorclass:
  - name: AC
    desc: "8; __Fort__ +7, __Ref__ +3, __Will__ +5"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  acid,  critical hits,  precision,  unconscious,  visual,  mental; __Weaknesses__ slashing 5"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A giant amoeba can sense nearby creatures through vibration and air or water movement."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+8 ()\n__Damage__  1d6 acid plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d4 bludgeoning plus 1d4 acid, DC 17 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Envelop"
    desc: "`pf2:3`  **Requirements** The giant amoeba begins its turn with a target its size or smaller [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The giant amoeba maintains the [[Bestiary Ability Glossary/Grab|Grab]] and extends pseudopods to surround the creature and pull it inside the amoeba's body. This thereafter has the same effect as if the amoeba had [[Bestiary Ability Glossary/Engulf|Engulfed]] the creature (DC 17, 1d6 acid damage, Escape DC 17, Rupture 3)."

  - name: "Weak Acid"
    desc: "  A giant amoeba's acid damages only organic material-not metal, stone, or other inorganic substances."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Amoeba
creatures:
  - 1: Giant Amoeba
```



These blobs of nearly transparent protoplasm are identical in form and behavior to the microscopic creatures from which they have evolved, except their outlandish size makes them all the more dangerous. Unlike slimes, puddings, and other deadly oozes, giant amoebas have an outer membrane that contains their internal structures, making them more susceptible to slashing weapons than their amorphous kin. However, this membrane is also extremely flexible and permeable, allowing them to surround prey and absorb it, suffocating and slowly digesting it in the amoeba's acidic fluids.
