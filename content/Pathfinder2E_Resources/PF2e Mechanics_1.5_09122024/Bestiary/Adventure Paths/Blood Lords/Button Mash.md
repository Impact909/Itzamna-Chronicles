---
title: Button Mash
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - mechanical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #186: Ghost King&#x27;s Rage
aliases: "Actor.E0MIsOpCAn6Y7qdn" 
level: 17
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King's Rage"
name: "Button Mash"
level: "Hazard 17"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[mechanical]]
trait_03: [[trap]]
modifier: 24
sourcebook: "_Pathfinder #186: Ghost King's Rage_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +32, __Ref__ +26, "
hp: 110
health:
  - name: ""
  - name: "HP"
    desc: "110; __Hardness__ 28; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 24" 
    desc: "(master)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The room floods with harmful effects by pressing a magic sigil on a console. Each sigil causes different results. There are six sigils on the console."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Arcana check (master) to disenchant each sigil (can be done from either side of the reception desk), DC 43 Thievery check (master) twice to disable the console (can only be done while behind the reception desk), or [[Spells/Dispel Magic|Dispel Magic]] (8th level; counteract DC 40) to counteract each sigil; prevent Noph from pressing the buttons by gaining access to the reception desk or other methods"
attacks:
  - name: ""

  - name: "Lockdown"
    desc: "`pf2:r` (force) **Trigger** Noph or another creature arms the trap by pressing a sigil on the console\n* * *\n\n**Effect** A barrier of force forms from floor to ceiling surrounding the reception desk. The DC to counteract this barrier with [[Spells/Dispel Magic|Dispel Magic]] is 43. The trap then rolls initiative."
  - name: "Melee"
    desc: "Comet +33 () "

  - name: "Routine"
    desc: "(2 actions) Noph frantically pecks and stomps on the console, using each action to press a random sigil. Roll [[/gmr 1d6 #Pressed Sigil]] to determine which sigil Noph presses. Psychopomps are immune to the effects of these sigils.\n\n**1** The area is flooded with holy light, dealing 3d12+19 vitality damage to each creature in the area (DC 43 Reflex check).\n\n**2** The area is flooded with unholy darkness, dealing 3d12+19 void damage to each creature in the area (DC 43 Reflex check).\n\n**3** The area is flooded with blue flames, dealing 3d10+19 fire damage to each creature in the area (DC 43 Reflex check). On a critical failure, a creature additionally takes 1d10 persistent fire damage.\n\n**4** A comet streaks through the area, attacking the nearest creature to Noph with a comet Strike.\n\n**5** Force tethers sprout from the floor, grasping at intruders. Each creature in the area is [[Conditions/Immobilized|Immobilized]] for 1 round unless they succeed at a DC 43 Fortitude check save.\n\n**6** Ghostly blue mist surrounds each psychopomp in the area, healing them 3d8+19 HP and granting them [[Conditions/Concealed|Concealment]] for 1 round."

```

```encounter-table
name: Button Mash
creatures:
  - 1: Button Mash
```

