---
title: "Vargouille"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QC3KUEJsBb5WtmcJ" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Vargouille"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Vargouille"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Diabolic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Stealth: +8"
abilityMods: [3, 4, 4, -2, 3, -1]
speed:  fly 25 feet
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +8, __Will__ +7"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+10 (finesse, unholy)\n__Damage__  1d8 + 3 piercing plus vargouille-venom"

  - name: "Kiss"
    desc: "`pf2:1`  The vargouille kisses an adjacent creature that's asleep, [[Conditions/Paralyzed|Paralyzed]], or [[Conditions/Unconscious|Unconscious]], exposing it to the vargouille transformation disease."

  - name: "Shriek"
    desc: "`pf2:2` (auditory,concentrate,visual) The vargouille shrieks, its scream so terrible that all non-vargouilles within 60 feet must succeed at a DC 16 Fortitude check save or be [[Conditions/Paralyzed|Paralyzed]] for 3 rounds.\n\nThe effect ends early for a creature if the vargouille moves out of sight, moves farther than 60 feet from the creature, or attacks the creature with its fangs.\n\nAfter attempting its save, a creature is immune to that particular vargouille's Shriek for 24 hours."

  - name: "Vargouille Transformation"
    desc: " (disease) Exposing the victim to sunlight or any light spell of 3rd level or higher pauses the progression of the disease until the victim is no longer in light.\n\n**Saving Throw** DC 18 Fortitude check\n\n**Stage 1** carrier with no effect (1d6 hours)\n\n**Stage 2** victim's hair falls out (1d6 hours)\n\n**Stage 3** victim's ears grow into leathery wings, tentacles sprout on the chin and scalp, and the teeth become long, pointed fangs (1 day)\n\n**Stage 4** victim's mind regresses to a vicious and unintelligent shell of its former self (1d6 hours)\n\n**Stage 5** victim's head breaks free of the body (which dies) and becomes a new vargouille"

  - name: "Vargouille Venom"
    desc: " (poison) **Saving Throw** DC 18 Fortitude check\n\n**Stage 1** Damage the victim has taken from vargouille fangs can't be healed magically.\n\nOnce all vargouille fang damage has been healed nonmagically, the poison ends."
 
```

```encounter-table
name: Vargouille
creatures:
  - 1: Vargouille
```




