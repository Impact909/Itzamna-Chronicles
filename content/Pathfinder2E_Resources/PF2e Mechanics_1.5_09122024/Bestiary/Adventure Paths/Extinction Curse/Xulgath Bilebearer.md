---
title: "Xulgath Bilebearer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.CW13CYC4GBQCelsK" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Xulgath Bilebearer"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #151: The Show Must Go On"
name: "Xulgath Bilebearer"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +6, Deception: +5, Stealth: +8, Thievery: +8"
abilityMods: [2, 4, 2, 1, 0, -1]
speed: 25 feet
sourcebook: "_Pathfinder #151: The Show Must Go On_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +8, __Ref__ +10, __Will__ +4"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "2x [[Equipment/Dagger|Dagger]]"
abilities_mid:
  - name: ""
  - name: "Stench"
    desc: " (aura,olfactory) 30 feet. A creature entering the aura must attempt a DC 16 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure, the creature also takes a -5-foot status penalty to its Speeds for 1 round. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at its save is temporarily immune to all xulgaths' stench for 1 minute.\n\nA xulgath bilebearer can activate or deactivate its stench aura as a free action.\n\n[[Bestiary Effects/Effect_ Xulgath Stench|Effect: Xulgath Stench]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 ()\n__Damage__  2d4 + 4 piercing plus xulgath-bile"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d6 + 4 slashing plus grab"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+12 (agile, finesse, versatile s)\n__Damage__  1d4 + 4 piercing plus xulgath-bile"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+12 (agile, finesse, thrown 10 ft., versatile s)\n__Damage__  1d4 + 4 piercing plus xulgath-bile"

  - name: "Putrid Blast"
    desc: "`pf2:2` (olfactory,poison) **Frequency** once per minute\n* * *\n\n**Effect** All adjacent creatures must attempt a DC 18 Fortitude check save. On a failure, the creature is [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure) until the end of its next turn and takes a -2 circumstance penalty to Fortitude saves against xulgath bile for 1 minute.\n\n[[Bestiary Effects/Effect_ Putrid Blast|Effect: Putrid Blast]]"

  - name: "Xulgath Bile"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n\n**Maximum Duration** 1 hour\n\n**Stage 1** [[Conditions/Fatigued|Fatigued]] (1 minute).\n\n**Stage 2** [[Conditions/Fatigued|Fatigued]] and [[Conditions/Unconscious|Unconscious]] (1 minute)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Xulgath Bilebearer
creatures:
  - 1: Xulgath Bilebearer
```



While many xulgaths impose their will by strength or sheer numbers, some resort to more nefarious-and grotesque-means to take care of matters. The bilebearer takes its name from its eponymous bile, a putrid substance that oozes from gill-like folds in its colorful, bulging neck. Bilebearers coat their weapons with the viscous substance or secrete a concentrated dose that suffuses the air around them and disables foes.

A bilebearer's neck bulges with folds of scaled flesh that extend almost to the creature's shoulders, containing its namesake bile productions glands inside. These folds expand and contract with each breath, and each fold has a vertical line of muscled pores that gradually exudes the thick substance, providing a perpetual supply for coating weapons. Bilebearers' necks also contain inflatable bladders, which they can quickly pressurize to expel a blast of vaporized bile in a noxious, overwhelming cloud.

Bilebearers serve their clutches by kidnapping or slaying specific enemies. They frequently accompany their kin, particularly xulgath skulkers, to raid rival clutches or intercept foes. A bilebearer's mode of attack typically involves sneaking in, overwhelming any guards with a noxious blast of bile, and then turning their attention to the primary target. The xulgath either shreds the rapidly weakening victim on the spot or drags them away for future violence.
