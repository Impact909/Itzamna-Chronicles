---
title: "Corrosive Lizard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DRDetccZOrdKSEef" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Corrosive Lizard"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Corrosive Lizard"
level: "Creature 2"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[animal]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +8, Stealth: +6"
abilityMods: [2, 2, 4, -4, 1, -2]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +8, __Will__ +5"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30; __Immunities__  acid; __Weaknesses__ holy 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Gnashing Bite"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by the corrosive lizard's jaws fails a check to [[Actions/Escape|Escape]]\n* * *\n\n**Effect** The lizard's jaws deal 1d6 piercing damage and 1d6 acid damage to the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (unholy)\n__Damage__  1d10 + 2 piercing plus grab 1d6 acid plus grab"

  - name: "Gout of Acid"
    desc: "`pf2:2` (acid,primal) The corrosive lizard vomits a gout of acid in a 15-foot cone. Each creature in this area takes 3d6 acid damage (DC 20 Reflex check save).\n\nThe lizard can't use Gout of Acid again for 1d4 rounds."

  - name: "Lurching Charge"
    desc: "`pf2:2`  The corrosive lizard Strides up to double its Speed and then makes a jaws Strike. If the lizard moved at least 20 feet away from its starting position, it gains a +2 circumstance bonus to this attack roll."
 
```

```encounter-table
name: Corrosive Lizard
creatures:
  - 1: Corrosive Lizard
```




