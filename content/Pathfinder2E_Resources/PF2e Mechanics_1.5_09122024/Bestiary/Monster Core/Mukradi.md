---
title: "Mukradi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sr6gJO75VHy06kPo" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/15
  - remaster
statblock: inline
name: "Mukradi"
level: 15
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Mukradi"
level: "Creature 15"

alignment: ""
size: "grg"
trait_01: [[beast]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +32"
abilityMods: [9, 0, 7, -3, 3, 0]
speed: 60 feet,  burrow 60 feet,  climb 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 37
armorclass:
  - name: AC
    desc: "37 all-around vision; __Fort__ +32, __Ref__ +23, __Will__ +26"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Resistances__ acid 20, electricity 20, fire 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Partitioned Anatomy"
    desc: "`pf2:0`  **Trigger** The mukradi would be [[Conditions/Confused|Confused]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Slowed|Slowed]], or [[Conditions/Stunned|Stunned]]\n* * *\n\n**Effect** The mukradi confines the debilitating effect to a certain portion of its nervous system, ignoring the effect but causing a maw of its choice to go dormant for the effect's duration. That maw can't be used for a Strike or to Breathe Energy during that time. This ability can't be used if all the mukradi's heads are dormant."

  - name: "Spitting Rage"
    desc: "`pf2:r`  **Trigger** A creature scores a critical hit on the mukradi\n* * *\n\n**Effect** The mukradi's Breathe Energy recharges. It can use Breathe Energy immediately as part of this reaction. It can't use this reaction again until it recharges Breathe Energy naturally."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Acid Maw"
    desc: "+32 (magical, reach 20 feet)\n__Damage__  2d12 + 17 piercing 3d6 acid"

  - name: "**Melee** `pf2:1` Flame Maw"
    desc: "+32 (magical, reach 20 feet)\n__Damage__  2d12 + 17 piercing 3d6 fire"

  - name: "**Melee** `pf2:1` Shock Maw"
    desc: "+32 (magical, reach 20 feet)\n__Damage__  2d12 + 17 piercing 3d6 electricity"

  - name: "**Melee** `pf2:1` Leg"
    desc: "+32 (agile, magical, reach 15 feet)\n__Damage__  2d10 + 17 piercing"

  - name: "**Melee** `pf2:1` Tail Lash"
    desc: "+32 (magical, reach 30 feet)\n__Damage__  3d10 + 17 slashing plus knockdown"

  - name: "Breathe Energy"
    desc: "`pf2:2` (primal) The mukradi breathes a blast of energy from one of its three heads; each creature in the area must attempt a DC 36 Reflex check save.\n\nThe mukradi can't Breathe Energy again for 1d4 rounds.\n\n*   **Acid Maw** (acid) 10-foot-wide, 60-foot line of acid dealing 16d6 acid damage.\n*   **Flame Maw** (fire) 60-foot cone of fire dealing 16d6 fire damage.\n*   **Shock Maw** (electricity) 120-foot line of electricity dealing 16d6 electricity damage."

  - name: "Pull Apart"
    desc: "`pf2:2`  The mukradi makes two Strikes with different maws against the same target. If both hit, the target takes an extra 2d12+13 slashing damage, with a DC 36 Fortitude check save. On a critical failure, the creature is torn to pieces and dies.\n\nThe mukradi's multiple attack penalty increases only after all the attacks are made."

  - name: "Thrash"
    desc: "`pf2:2`  The mukradi Strikes once against each creature in its reach. It can make one of these Strikes with each of its maws, one with its tail lash, and the rest with its legs. Each attack takes a –2 circumstance penalty and counts toward the mukradi's multiple attack penalty, but the multiple attack penalty doesn't increase until after all the attacks are made."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, leg, DC 36 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Mukradi
creatures:
  - 1: Mukradi
```



Fearsome centipede-like creatures, mukradis are three-headed predators with a devastating array of ways to kill, burn, and dismember. A version of the mukradi that dwells in the Darklands is rumored to exist. It's said these variant mukradis have black scales, and all of their heads spew a black, acidic goo that animates before being reabsorbed by the mukradis.
