---
title: "Gray Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SBsCybp5c38Xn3D8" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Gray Ooze"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Gray Ooze"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +11, Stealth: +10"
abilityMods: [5, 2, 4, -5, 0, -5]
speed: 10 feet,  climb 10 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +12, __Ref__ +10, __Will__ +8"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  acid,  critical hits,  precision,  unconscious,  visual,  mental; __Resistances__ slashing 5, piercing 5"
abilities_top:
  - name: ""

  - name: "Motion Sense"
    desc: "  A gray ooze can sense nearby creatures through vibration and air or water movement."

  - name: "Puddled Ambush"
    desc: "  **Trigger** A creature enters a space occupied by a gray ooze\n\n**Requirements** Initiative has not yet been rolled\n* * *\n\n**Effect** The gray ooze automatically notices the creature, then makes a pseudopod Strike against one creature adjacent to itself before rolling initiative."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+13 (agile)\n__Damage__  1d6 + 5 bludgeoning plus grab 1d6 acid plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6 bludgeoning plus 1d6 acid, DC 21 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Gray Ooze Acid"
    desc: "  A gray ooze's acid damages only metal and organic materials, not stone."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Gray Ooze
creatures:
  - 1: Gray Ooze
```



These dangerous oozes are the bane of any who travel through swamps, marshes, or damp caves. Easily masquerading as pools of clear water or patches of wet stone, gray oozes lie in wait for unwary victims to reach down for a drink or step into what appears to be a puddle, then lash out with whiplike pseudopods to ensnare and consume their hapless prey.
