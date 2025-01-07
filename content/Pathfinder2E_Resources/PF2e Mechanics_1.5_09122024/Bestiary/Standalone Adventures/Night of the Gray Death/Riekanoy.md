---
title: "Riekanoy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TIuUAWP7kAdetWvK" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Riekanoy"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Night of the Gray Death"
name: "Riekanoy"
level: "Creature 19"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[evil]]
trait_03: [[fey]]
trait_04: [[water]]
modifier: 31
perception:
  - name: "Perception"
    desc: "+31; Low-Light Vision, Truesight"
languages: "Common, Fey, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +31, Deception: +35, Nature: +33, Performance: +37, Stealth: +35, Survival: +33"
abilityMods: [6, 10, 2, 3, 6, 10]
speed: 25 feet,  swim 50 feet
sourcebook: "_Pathfinder Adventure: Night of the Gray Death_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +28, __Ref__ +37, __Will__ +32"
hp: 410
health:
  - name: ""
  - name: HP
    desc: "410; __Weaknesses__ cold iron 20; __Resistances__ fire 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Sinuous Initiative"
    desc: "  A riekanoy's swaying motions propel it into the fray with grace. While a riekanoy can act and isn't [[Conditions/Immobilized|Immobilized]], it can roll Performance for initiative."

  - name: "Water Walk"
    desc: "  Riekanoy is under the effects of 9th-rank [[Spells/Water Walk|Water Walk]] at all times."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hair"
    desc: "+24 (agile, finesse, reach, reach 15 feet)\n__Damage__  4d10 + 12 bludgeoning plus improved-grab"

  - name: "Primal Innate Spells"
    desc: "DC 41, attack +33; __9th __ (2 slots) _[[Spells/Hydraulic Torrent|Hydraulic Torrent]]_, _[[Spells/Nature's Enmity|Nature's Enmity]]_; __8th __ (2 slots) _[[Spells/Charm|Charm (At Will)]]_, _[[Spells/Fire Seeds|Fire Seeds]]_; __6th __ (3 slots) _[[Spells/Cursed Metamorphosis|Baleful Polymorph (Aquatic Animals Only)]]_; __5th __  _[[Spells/Control Water|Control Water (At Will)]]_; __2nd __ (2 slots) _[[Spells/Invisibility|Invisibility (At Will)]]_, _[[Spells/Mist|Obscuring Mist (At Will)]]_\n__Constant__  __(9th)__ _[[Spells/Truesight|True Seeing]]_, _[[Spells/Water Walk|Water Walk]]_"

  - name: "Beckoning Dance"
    desc: "`pf2:1` (concentrate,incapacitation,mental,primal,visual) The riekanoy sways in a compelling fashion. Each non-fey creature within a 300-foot emanation that can see the riekanoy must attempt a DC 38 Will check save. The effect lasts for 1 round, but if the riekanoy uses Beckoning Dance again on subsequent rounds, the duration extends by 1 round for all affected creatures. Once a creature succeeds at any save against Beckoning Dance, that creature is temporarily immune for 24 hours.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]] and must spend each of its actions to move closer to the riekanoy, avoiding obvious dangers. If a beckoned creature is adjacent to the riekanoy, it stays still and doesn't act. If attacked by the riekanoy, the creature is freed from captivation at the end of the riekanoy's turn.\n\n**Critical Failure** As failure, but if attacked by the riekanoy, the creature can attempt a new save only at the start of its next turn, rather than being freed at the end of the riekanoy's turn."

  - name: "Constrict"
    desc: "`pf2:1`  3d10+12 bludgeoning, DC 41 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Entangling Hair"
    desc: "  A riekanoy can have up to eight creatures [[Conditions/Grabbed|Grabbed]] within their hair at a time."

  - name: "Waving Hair"
    desc: "`pf2:1`  The riekanoy attempts an Acrobatics check against each [[Conditions/Grabbed|Grabbed]] creature's Reflex DC. The riekanoy moves each creature they succeed against up to 10 feet and each creature they critically succeed against up to 20 feet. This movement must all be within reach of its hair."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Riekanoy
creatures:
  - 1: Riekanoy
```




