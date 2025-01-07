---
title: "Phytohydra"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OhLDelknLuObDoin" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/plant
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Phytohydra"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Phytohydra"
level: "Creature 12"

alignment: ""
size: "huge"
trait_01: [[elemental]]
trait_02: [[plant]]
trait_03: [[wood]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; "
languages: "Arboreal, Muan; (can&#x27;t speak any languages)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +25"
abilityMods: [7, 3, 5, -1, 4, 2]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +25, __Ref__ +19, __Will__ +22"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, phytohydra regeneration; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Phytohydra Regeneration"
    desc: "  The phytohydra has regeneration equal to 5 × the number of heads it has. If a phytohydra's body is missing any heads and the remaining stumps haven't been cauterized, the phytohydra attempts a DC 35 Fortitude check save after it regains Hit Points from regeneration. On a success, one unsealed stump regrows two heads; on a critical success, two unsealed stumps regrow into two heads each. The phytohydra can never grow more than double the number of heads it ordinarily has. The phytohydra's regeneration only fully deactivates if all its heads are severed and all stumps are sealed, at which point it dies."

  - name: "Coppice Regrowth"
    desc: "  A phytohydra ordinarily has five heads. A creature can attempt to sever one of the heads by specifically targeting it and dealing damage equal to the head's Hit Points. A head that isn't completely severed returns to full Hit Points at the end of any creature's turn.\n\nA phytohydra can regrow a severed head using phytohydra regeneration. A creature can prevent this regrowth by dealing fire damage to the stump, sealing it. Single-target fire effects need to be targeted at a specific stump, but effects that deal splash damage or affect areas covering the hydra's whole space seal all stumps if they deal fire damage. If the attack that severs a head deals any fire damage or was dealt by an axe, the stump is sealed instantly. If all five heads are sealed, the phytohydra dies.\n* * *\n\n**Phytohydra Head**\n\n*   **Hit Points** 30\n    \n*   **Immunities** Area Damage, Bleed, Paralyzed, Poison, Sleep\n    \n*   **Weaknesses** Fire 10, Slashing 5  \n    \n\n[[Bestiary Effects/Effect_ Phytohydra Heads|Effect: Phytohydra Heads]]"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (See Reactive Heads)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Branch"
    desc: "+25 (reach 10 feet)\n__Damage__  4d6 + 11 bludgeoning plus push"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+25 (reach 10 feet)\n__Damage__  4d6 + 13 piercing"

  - name: "Focused Assault"
    desc: "`pf2:2`  The phytohydra attacks a single target with its many heads. The phytohydra Strikes with its branches or its fangs. On a successful attack, the phytohydra deals damage from its branches or fangs Strike to the target, plus an additional 2d6 damage for every head it has beyond the first. On a failure (but not a critical failure), the phytohydra deals the damage from one branch or fangs Strike to the target creature. This Strike counts as a number of attacks equal to the number of heads the phytohydra has toward its multiple attack penalty."

  - name: "Reactive Heads"
    desc: "  A phytohydra gains an extra reaction per round for each of its heads beyond the first, which it can use only to make Reactive Strikes. It can't use more than 1 reaction on the same triggering action, even if a creature leaves several squares within its reach, and the phytohydra must use a different head for each Reactive Strike it makes. Whenever one of the phytohydra's heads is severed, the phytohydra loses one of its extra reactions per round."

  - name: "Splinter Breath"
    desc: "`pf2:2`  The phytohydra spews splinters in a 60-foot cone that deals 4d6 piercing damage to all creatures in the area (DC 32 Reflex check save). The damage increases by 2d6 for each head the phytohydra has.\n\nThe phytohydra can't use Splinter Breath again for 1d4 rounds."

  - name: "Storm of Branches"
    desc: "`pf2:2`  The phytohydra makes a number of Strikes up to its number of heads, each against a different target. These attacks count toward the phytohydra's multiple attack penalty, but the multiple attack penalty doesn't increase until after the phytohydra makes all its attacks."

  - name: "[[Bestiary Ability Glossary/Push|Push 10 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Phytohydra
creatures:
  - 1: Phytohydra
```



The fresh shoots that sprout from especially grievous cuts sometimes develop minds of their own, eventually budding off from the injured plant to create a phytohydra.

* * *

Wood elementals are nearly as varied as plant life itself. The following are particularly powerful elementals formed when immense plants experience environmental stress.
