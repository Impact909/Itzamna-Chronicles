---
title: "Pine Pangolin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9NfH4RkSiw6khQS7" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Pine Pangolin"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Pine Pangolin"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[wood]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17, Nature: +15, Survival: +18"
abilityMods: [4, 0, 5, 1, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +10, __Will__ +18"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  poison,  paralyzed,  sleep,  bleed; __Weaknesses__ axe vulnerability 5, fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 (agile)\n__Damage__  2d12 + 3 piercing"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+17 ()\n__Damage__  2d8 + 3 bludgeoning plus grab"

  - name: "Roll Up"
    desc: "`pf2:1` (move) The pine pangolin falls [[Conditions/Prone|Prone]], closes up its scales, and rolls into a ball. While Rolled Up, the pangolin gains resistance 10 to physical damage and total immunity to falling damage from heights of 50 feet or less. The only action the pine pangolin can take is to Stand, and the effects of Roll Up end once the pangolin Stands."

  - name: "Secrete Tar"
    desc: "`pf2:1` (plant) The pine pangolin secretes a brown, sticky tar within a 5-foot emanation, making those squares difficult terrain for 1 minute. Each creature that enters or starts its turn in a tarred square must succeed at a DC 25 Fortitude check save or become [[Conditions/Immobilized|Immobilized]] until it Escapes. On a critical failure, the creature falls [[Conditions/Prone|Prone]]; prone creatures take a –2 circumstance penalty to their checks to [[Actions/Escape|Escape]] the tar. The pine pangolin is immune to the effects of its own tar."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Pine Pangolin
creatures:
  - 1: Pine Pangolin
```



These creatures sleep while hanging upside down by their partially curled tails and rely on their thick wooden scales to protect them from danger. One such danger the scales negate is the falling damage from deliberately rolling up and dropping onto the head of an unsuspecting opponent, which is one of their favorite combat strategies. Beneath their scales, pine pangolin bodies secrete a thick, sticky tar that serves as a secondary line of defense.
