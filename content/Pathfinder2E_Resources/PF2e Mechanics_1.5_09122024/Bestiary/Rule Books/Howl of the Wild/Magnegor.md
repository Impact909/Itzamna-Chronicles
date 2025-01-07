---
title: "Magnegor"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.R5cPnUeeCTiHIMkB" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Magnegor"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Magnegor"
level: "Creature 6"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15, Intimidation: +13, Survival: +15"
abilityMods: [5, 2, 4, -4, 2, -2]
speed: 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +17, __Ref__ +11, __Will__ +14"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Metal Allergy"
    desc: "  When a magnegor takes damage from a metal weapon or an effect with the metal trait, it takes 5 untyped additional damage and must succeed at a DC 5 Flat check or become [[Conditions/Sickened|Sickened 1]]. The value of the sickened condition increases each time the magnegor fails such a check, to a maximum of 3."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horn"
    desc: "+17 (reach 10 feet)\n__Damage__  2d8 + 5 piercing"

  - name: "Excavating Spines"
    desc: " (earth) The magnegor inadvertently digs a 10-foot-deep continuous trench in any square it Wallows through, as long as the ground in that space isn't made of stone, rock, or some other surface too hard to excavate. The trench is greater difficult terrain. At the GM's discretion, any excavated square can reveal a deposit of sedimentary rock filled with metal ore that has Hardness 7 and 28 Hit Points."

  - name: "Magnetized Coat"
    desc: "  When a magnegor comes within 30 feet of a metal object or a deposit of metal ore, its thousands of wiry hairs stand on end, pointing towards the metal and creating a magnetic field. Metal items of light or negligible Bulk that touch the magnegor's coat adhere to it magnetically, requiring an Interact action to be pried free. Creatures wearing or primarily composed of metal treat all squares in a 10-foot radius around the magnegor as difficult terrain, unless they are moving directly towards it."

  - name: "Wallow"
    desc: "`pf2:3` (move) **Requirements** The magnegor is [[Conditions/Prone|Prone]]\n* * *\n\n**Effect** The magnegor rolls on its spine-covered back, up to its Speed, furrowing the earth and crushing any Large or smaller creatures in its path. This deals 4d10 piercing damage with a DC 24 Reflex check save; on a failed save, a creature wearing metal armor or made of metal is [[Conditions/Restrained|Restrained]] by the magnegor's magnetized coat ([[Actions/Escape|Escape]] DC 24). For each metal object or piece of equipment a restrained creature chooses to leave stuck to the magnegor, it gains a +1 circumstance bonus to its attempts to Escape. A creature that relinquishes all its metal Escapes automatically. The magnegor can move at its full Speed while it has a creature restrained in this way, bringing the creature along."
 
```

```encounter-table
name: Magnegor
creatures:
  - 1: Magnegor
```




