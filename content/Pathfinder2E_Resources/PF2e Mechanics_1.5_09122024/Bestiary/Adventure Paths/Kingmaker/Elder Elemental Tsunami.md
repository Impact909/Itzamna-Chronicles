---
title: "Elder Elemental Tsunami"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.htnIDUTpzlNiy8hV" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Elder Elemental Tsunami"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Elder Elemental Tsunami"
level: "Creature 14"

alignment: ""
size: "huge"
trait_01: [[aquatic]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +28, Stealth: +28"
abilityMods: [8, 8, 8, 0, 5, 0]
speed: 35 feet,  swim 100 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +26, __Ref__ +28, __Will__ +23"
hp: 260
health:
  - name: ""
  - name: HP
    desc: "260; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ fire 10"
abilities_top:
  - name: ""

  - name: "Water-Bound"
    desc: "  When not touching water, the elemental tsunami is [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "Vortex"
    desc: " (aura,water) 50 feet. Water in the area that is in the same body of water as the elemental tsunami is difficult terrain for Swimming creatures that don't have the water trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Wave"
    desc: "+30 (reach 20 feet)\n__Damage__  3d12 + 16 bludgeoning plus blinding-sickness,push-or-pull-10-feet"

  - name: "Blinding Sickness"
    desc: " (disease) A creature that takes damage from an elder elemental tsunami's wave Strike or Surge is exposed to blinding sickness.\n* * *\n\n**Saving Throw** DC 34 Fortitude check\n\n**Stage 1** carrier with no ill effects\n\n**Stage 2** [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** [[Conditions/Enfeebled|Enfeebled 2]] (1 day)\n\n**Stage 4** enfeebled 2 and permanently [[Conditions/Blinded|Blinded]] (1 day)\n\n**Stage 5** [[Conditions/Enfeebled|Enfeebled 4]] (1 day)\n\n**Stage 6** [[Conditions/Unconscious|Unconscious]] (1 day)\n\n**Stage 7** death"

  - name: "Drench"
    desc: "`pf2:1` (primal,water) The elemental puts out all fires in a 20-foot emanation.\n\nIt extinguishes all non-magical fires automatically and attempts to counteract magical fires (+20 counteract modifier)."

  - name: "Surge"
    desc: "`pf2:2`  The elemental tsunami quickly expands its space to fill the area of its vortex. Creatures within the vortex's emanation take 6d12+8 bludgeoning damage (DC 34 Fortitude check save). A creature that fails this save is Pushed 20 feet. The elemental tsunami then retracts to its former space.\n\nA creature that takes damage is exposed to blinding sickness.\n\nThe elemental tsunami can't Surge again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Push|Push or Pull 10 feet]]"
    desc: "`pf2:1`  The elemental tsunami can also pull the creature.\n* * *\n\n**Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Elder Elemental Tsunami
creatures:
  - 1: Elder Elemental Tsunami
```


Variant elemental tsunami

Elemental tsunamis are huge and destructive.

* * *

Water elementals can be very destructive, but often not intentionally so; just as water can bring life to those in need on the Material Plane, its waves can pound shores and rains can flood cities. Water elementals are similarly difficult to predict.
