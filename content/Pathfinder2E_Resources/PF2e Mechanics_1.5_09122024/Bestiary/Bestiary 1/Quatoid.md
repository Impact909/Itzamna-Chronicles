---
title: "Quatoid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4Pt1lEuw2bd2Ug7H" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/lawful
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Quatoid"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Quatoid"
level: "Creature 7"

alignment: ""
size: "Small"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[lawful]]
trait_04: [[water]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +15, Diplomacy: +12, Occultism: +17, Society: +17, Stealth: +13, Elemental Lore: +17"
abilityMods: [4, 2, 0, 4, 3, 1]
speed: 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +13, __Ref__ +15, __Will__ +18"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ bludgeoning 5, fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Calming Bioluminescence"
    desc: " (aura,emotion,mental,visual) 30 feet. The aura sheds dim light. Creatures in the emanation gain a +2 circumstance bonus to saving throws against emotion effects. The quatoid can activate or deactivate its calming bioluminescence as a single action, which has the concentrate trait.\n\n[[Bestiary Effects/Effect_ Calming Bioluminescence|Effect: Calming Bioluminescence]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+16 (reach 10 feet)\n__Damage__  2d12 + 6 bludgeoning plus grab"

  - name: "Primal Innate Spells"
    desc: "DC 27, attack +17; __2nd __  _[[Spells/Hydraulic Push|Hydraulic Push (At Will)]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d12+6 bludgeoning, DC 25 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Quatoid
creatures:
  - 1: Quatoid
```



Quatoids are peculiar, mysterious elementals native to the Plane of Water that resemble four-tentacled octopuses with eerily humanoid faces on their mantles.

* * *

Water elementals can be very destructive, but often not intentionally so; just as water can bring life to those in need on the Material Plane, its waves can pound shores and rains can flood cities. Water elementals are similarly difficult to predict.
