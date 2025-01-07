---
title: "Painted Stag"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.VyBFgYu708YOEHCF" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Painted Stag"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Painted Stag"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[wood]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +23, Nature: +18"
abilityMods: [7, 3, 5, 2, 1, 4]
speed: 45 feet,  climb 60 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +12, __Will__ +21"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, regeneration 10 (deactivated by fire); __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ axe vulnerability 10, fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 10 (Deactivated by Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Antler"
    desc: "+20 ()\n__Damage__  2d12 + 7 piercing plus grab"

  - name: "**Melee** `pf2:1` Hooves"
    desc: "+20 ()\n__Damage__  2d10 + 7 bludgeoning"

  - name: "Mauler"
    desc: "  A painted stag gains a +5 circumstance bonus to damage rolls against creatures it has grabbed."

  - name: "Painted Dance"
    desc: "`pf2:2` (auditory,mental,plant,primal,visual) The stag shakes the wooden plating along its body in a cacophonous clatter that sets its painted patterns dancing. All creatures within 60 feet of the painted stag who can see or hear it must attempt a DC 28 Will check save; a creature [[Conditions/Grabbed|Grabbed]] by the stag takes a –4 circumstance penalty to its save. Regardless of the result of its save, each creature is temporarily immune for 1 hour.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Fascinated|Fascinated]] by the painted stag for 1 round.\n\n**Failure** The creature is [[Conditions/Stunned|Stunned 2]] and fascinated by the painted stag for as long as it's stunned.\n\n**Critical Failure** As failure, except [[Conditions/Stunned|Stunned 4]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Painted Stag
creatures:
  - 1: Painted Stag
```




