---
title: Punish the Impertinent
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - shadow
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #202: Severed at the Root
aliases: "Actor.q1cGAy7CPWzw8pLq" 
level: 10
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Punish the Impertinent"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[shadow]]
trait_03: [[trap]]
modifier: 15
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +22, "
hp: 30
health:
  - name: ""
  - name: "HP"
    desc: "30; __Hardness__ 15; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three shadow tendrils emerge from the ground and seize trespassers."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 32 Arcana check or DC 32 Occultism check (expert) to banish one of the three the shadow tendrils or DC 34 Thievery check (master) twice to confound the bowl's magical sensors\n\n**Bypass** A creature who places an offering worth at least 10 gp into the bowl doesn't trigger the trap and isn't targeted by the trap."
attacks:
  - name: ""

  - name: "Shadow Tendrils"
    desc: "`pf2:r` **Trigger** A living creature passes by the statue without placing an offering worth at least 10 gp in the bowl\n* * *\n\n**Effect** Shadow tendrils rise from the ground and make a lash Strike against the triggering creature. The trap then rolls initiative."

  - name: "Constrict"
    desc: "action 2d12 bludgeoning, DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."
  - name: "Melee"
    desc: "Lash +23 (reach 15 feet) "

  - name: "Improved Grab"
    desc: "`pf2:0` **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "Routine"
    desc: "(2 actions per shadow tendril) On its turn, each shadow tendril uses 1 action to make a lash Strike against a creature in the area, then uses 1 action to Constrict a creature it has [[Conditions/Grabbed|Grabbed]]. The shadow tendrils don't apply the trap's multiple attack penalty."
  - name: "Reset"
    desc: "The trap resets after 10 minutes."
```

```encounter-table
name: Punish the Impertinent
creatures:
  - 1: Punish the Impertinent
```

