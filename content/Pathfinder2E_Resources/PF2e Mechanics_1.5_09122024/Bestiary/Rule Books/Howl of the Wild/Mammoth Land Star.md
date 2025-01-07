---
title: "Mammoth Land Star"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ydWsTVgWW6s9YTWs" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/mindless
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Mammoth Land Star"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Mammoth Land Star"
level: "Creature 8"

alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[mindless]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Scent (Precise) 100 Feet, Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +16, Stealth: +15, Survival: +18"
abilityMods: [6, 3, 6, -5, 4, -2]
speed: 25 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +19, __Ref__ +13, __Will__ +15"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100, regeneration 20 (reduced by 4 for each missing limb); limb regrowth; __Immunities__  mental"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (reduced by 4 for each missing limb)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Limb Regrowth"
    desc: "  A healthy mammoth land star typically has five limbs. A creature can sever a limb by targeting it and dealing damage equal to the limb's Hit Points. The mammoth land star can regrow a missing limb over the course of 24 hours.\n\n[[Bestiary Effects/Effect_ Mammoth Land Star Limbs|Effect: Mammoth Land Star Limbs]]"

  - name: "Limbs"
    desc: "  **HP**(limb) 25, regrowth; **Immunities** mental"

  - name: "Regrowth"
    desc: "  Whenever a limb is severed, it must attempt a DC 5 Flat check. On a success, the limb will slowly begin to grow into a new mammoth land star over the course of a week, unless it is doused in acid or fire."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Feet"
    desc: "+20 (agile, reach 10 feet)\n__Damage__  1d4 + 6 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Limb Spines"
    desc: "+20 (reach 10 feet)\n__Damage__  2d8 + 6 piercing plus spiny-venom"

  - name: "Detach"
    desc: "`pf2:2` (move) **Requirements** The mammoth land star falls below half its total Hit Points\n* * *\n\n**Effect** The mammoth land star severs one of its own limbs as a distraction, then Strides three times. This movement doesn't trigger reactions."

  - name: "Digest"
    desc: "`pf2:1`  **Requirements** The mammoth land star has a target [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The mammoth land star extrudes its stomach onto its prey and digests it alive. The target takes 2d12+6 acid damage and is [[Conditions/Drained|Drained 1]]."

  - name: "Glide"
    desc: "`pf2:2` (move) The land star blows air through its feet to hover 1 foot in the air and Strides twice with a +5-foot circumstance bonus to Speed, ignoring uneven ground and difficult terrain below it."

  - name: "Pry"
    desc: "`pf2:1`  **Requirements** The mammoth land star has a target [[Conditions/Grabbed|Grabbed]] that is wearing armor\n* * *\n\n**Effect** The mammoth land star makes a feet Strike against a creature it has grabbed. If that Strike hits and the creature is wearing armor with Hardness 12 or lower, the armor is broken. This Strike doesn't further damage armor that's already broken."

  - name: "Spiny Venom"
    desc: " (incapacitation,poison) **Saving Throw** DC 26 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison and [[Conditions/Slowed|Slowed 1]]\n\n**Stage 2** 2d6 poison and [[Conditions/Slowed|Slowed 2]]\n\n**Stage 3** 2d8 poison and [[Conditions/Paralyzed|Paralyzed]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Mammoth Land Star
creatures:
  - 1: Mammoth Land Star
```




