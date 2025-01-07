---
title: "Verdurous Ooze"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.As0bcGjGLfwXjCfz" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Verdurous Ooze"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Verdurous Ooze"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[ooze]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Motion Sense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15, Stealth: +4"
abilityMods: [5, -4, 5, -5, 0, -5]
speed: 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 12
armorclass:
  - name: AC
    desc: "12; __Fort__ +17, __Ref__ +8, __Will__ +10"
hp: 157
health:
  - name: ""
  - name: HP
    desc: "157; __Immunities__  acid,  critical hits,  piercing,  precision,  slashing,  unconscious,  visual,  mental"
abilities_top:
  - name: ""

  - name: "Motion Sense 60 feet"
    desc: "  A verdurous ooze can sense nearby creatures through vibration and air or water movement."

abilities_mid:
  - name: ""
  - name: "Corrosive Surface"
    desc: "  A creature that hits a verdurous ooze with a metal weapon or unarmed attack must attempt a DC 21 Reflex check save. On a failure, the weapon or creature takes 2d4 acid damage (after dealing damage to the ooze as normal). Thrown weapons take this damage automatically with no save."

  - name: "Enliven Foliage"
    desc: " (aura,primal) 20 feet. The verdurous ooze constantly emits supernatural vapors that cause nearby plants to grow rapidly and writhe and grasp at anything and everything within the emanation. This area becomes difficult terrain for non-verdurous ooze creatures. When a creature starts its turn in this aura, it must succeed at a DC 21 Reflex check save or take a -10-foot circumstance penalty to its Speeds until it leaves the emanation."

  - name: "Split"
    desc: "  When a verdurous ooze that has 10 or more HP is hit by an attack that would deal piercing or slashing damage, it splits into two identical oozes, each with half the original's HP. One ooze is in the same space as the original, and the other is in an adjacent, unoccupied space. If no adjacent space is unoccupied, it automatically pushes creatures and objects out of the way to fill a space (the GM decides if an object or creature is too big or heavy to push)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+15 ()\n__Damage__  2d6 + 7 bludgeoning plus grab 1d6 acid plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6 bludgeoning plus 1d6 acid, DC 24 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Sleep Gas"
    desc: "`pf2:2` (incapacitation,mental,poison,sleep) The verdurous ooze adjusts its aura of supernatural vapors to affect living creatures within a 20-foot emanation, forcing them to attempt a DC 24 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and becomes temporarily immune to Sleep Gas for 24 hours.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round.\n\n**Failure** The creature falls [[Conditions/Unconscious|Unconscious]]. If it's still unconscious after 1 minute, it wakes up automatically.\n\n**Critical Failure** The creature falls [[Conditions/Unconscious|Unconscious]]. If it's still unconscious after 1 hour, it wakes up automatically."

  - name: "Verdurous Ooze Acid"
    desc: "  A verdurous ooze's acid damages only metal and flesh-not bone, stone, or other materials."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Verdurous Ooze
creatures:
  - 1: Verdurous Ooze
```



Verdurous oozes are found in temperate forests, warm jungles, or other places where plant life grows in abundance. Unlike many types of oozes, verdurous oozes are not particularly good climbers and have been known to get trapped in natural or artificial chasms. Warlords and wizards sometimes make use of that fact and keep verdurous oozes as guardians in pits around the walls of their fortresses or towers.
