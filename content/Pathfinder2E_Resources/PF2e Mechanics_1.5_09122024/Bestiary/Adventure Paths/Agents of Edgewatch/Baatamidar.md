---
title: "Baatamidar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.p1893OM4HazcfPQR" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/21
statblock: inline
name: "Baatamidar"
level: 21
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Baatamidar"
level: "Creature 21"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[monitor]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; Darkvision, Truesight"
languages: "Chthonian, Diabolic, Empyrean, Protean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +38, Arcana: +37, Athletics: +35, Diplomacy: +35, Intimidation: +37, Occultism: +37, Religion: +37, Stealth: +38"
abilityMods: [6, 9, 5, 6, 10, 6]
speed:  fly 70 feet,  swim 50 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +32, __Ref__ +36, __Will__ +39"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350, regeneration 30 (deactivated by lawful); __Immunities__  acid,  paralyzed; __Resistances__ precision 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 30 (Deactivated by Lawful)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Unrelativity Field"
    desc: " (arcane,aura,incapacitation,mental) 1 mile. Creatures who start their turn in the aura must succeed at a DC 48 Will check save or become unable to understand any communication (including telepathy), distinguish social rank or authority, or differentiate the relative value of objects or services. This persists for as long as the creature is in the aura.\n\nCreatures who succeed at the save are temporarily immune for 1 hour (24 hours on a critical success). Proteans are immune to the unrelativity field.\n\nThe baatamidar can suppress this aura or activate it again as a free action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+36 (finesse, magical, reach 15 feet)\n__Damage__  4d8 + 14 bludgeoning plus improved-grab 2d6 spirit plus improved-grab"

  - name: "Arcane Innate Spells"
    desc: "DC 44, attack +36; __10th __ (1 slots) _[[Spells/Cataclysm|Cataclysm]]_; __9th __ (1 slots) _[[Spells/Prismatic Sphere|Prismatic Sphere]]_; __8th __ (2 slots) _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Hidden Mind|Mind Blank (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Detect Alignment|Detect Alignment]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Mind-Numbing Grasp"
    desc: " (arcane,incapacitation,mental) The baatamidar's tentacles leech away thought. A creature that starts its turn grabbed by the baatamidar must attempt a DC 41 Will check save.\n* * *\n\n**Critical Success** Unaffected.\n\n**Success** [[Conditions/Stupefied|Stupefied 1]] for 1 round.\n\n**Failure** [[Conditions/Stupefied|Stupefied 3]] for 1 minute.\n\n**Critical Failure** [[Conditions/Stupefied|Stupefied 3]] for an unlimited duration."

  - name: "Writhing Arms"
    desc: "`pf2:2`  The baatamidar makes up to four tentacle Strikes, each against a different target. Each attack counts separately for the baatamidar's multiple attack penalty, but the penalty doesn't increase until the baatamidar has made all the attacks.\n\nIf the baatamidar subsequently uses the Improved Grab action, it can Grab any number of creatures it hit with Writhing Arms."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Baatamidar
creatures:
  - 1: Baatamidar
```



Baatamidars are drawn to destroy planar communities on the fringes where the Outer Planes touch the chaos of the Maelstrom. They resemble floating blobs of undulating, prismatic ooze with four quivering tentacles and dribbles of oily slime that always drip upwards.
