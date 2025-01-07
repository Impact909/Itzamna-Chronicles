---
title: "Sunburst Corpse"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PIbuK2PK250wzonY" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Sunburst Corpse"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Sunburst Corpse"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Intimidation: +29, Occultism: +25"
abilityMods: [5, 1, 8, 1, 3, 7]
speed: 35 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 35
armorclass:
  - name: AC
    desc: "35; __Fort__ +28, __Ref__ +21, __Will__ +25"
hp: 255
health:
  - name: ""
  - name: HP
    desc: "255; __Immunities__  blinded,  dazzled,  fire; __Weaknesses__ cold 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Blinding Aura"
    desc: " (aura,incapacitation,light,occult,visual) 60 feet. The sunburst corpse sheds bright light. Any creature that starts its turn in the emanation must succeed at a DC 31 Fortitude check save. If it fails, it's [[Conditions/Blinded|Blinded]] for 1 minute, and if it critically fails, it's blinded permanently. A creature that succeeds at its save is temporarily immune to this effect for 24 hours."

  - name: "Darkness Vulnerability"
    desc: "  A sunburst corpse is [[Conditions/Sickened|Sickened 1]] while in areas of magical darkness. If the level of the magical darkness effect is at least half of the sunburst corpse's level (a 7th-rank effect against most sunburst corpses), the sunburst corpse is also [[Conditions/Slowed|Slowed 1]] while in the area."

  - name: "Light Camouflage"
    desc: "  The sunburst corpse is [[Conditions/Concealed|Concealed]] in areas of natural bright light, such as due to sunlight or torches, even to creatures that can see clearly in bright light. Magical bright light and light from the sunburst corpse's blinding aura don't conceal the sunburst corpse."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile, finesse)\n__Damage__  3d6 + 13 slashing plus grab,residual-light 2d8 fire plus grab,residual-light"

  - name: "**Ranged** `pf2:1` Sunfire"
    desc: "+25 (range increment 40 feet)\n__Damage__  7d6 fire"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+6 bludgeoning plus 2d8 fire and Residual Light, DC 34 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Nova Burst"
    desc: "`pf2:3` (light,occult) The sunburst corpse intensifies its light and unleashes a burning blast of energy. It deals 12d8 fire damage to all creatures in a 20-foot emanation (DC 34 Fortitude check save). A creature that fails its save becomes [[Conditions/Dazzled|Dazzled]] until the end of its next turn. The sunburst corpse can't use Nova Burst again for 1d4 rounds, and its blinding aura becomes inactive during this time."

  - name: "Residual Light"
    desc: " (light,occult) When a sunburst corpse Strikes or Grapples a creature, some of the corpse's light clings to the creature for a moment. The creature must attempt a DC 34 Fortitude check save. On a failure, the creature is [[Conditions/Dazzled|Dazzled]] until the end of its next turn. On a critical failure, the creature is dazzled for 1 minute. A dazzled creature can use an Interact action to wick off the light and remove the dazzled condition."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sunburst Corpse
creatures:
  - 1: Sunburst Corpse
```




