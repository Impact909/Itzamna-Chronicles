---
title: "Prismhydra"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xFU5q29cXuNW9Gh5" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Prismhydra"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Prismhydra"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Scent (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +33, Stealth: +27, Survival: +29"
abilityMods: [9, 6, 8, -3, 2, -1]
speed: 35 feet,  swim 35 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 30
armorclass:
  - name: AC
    desc: "30 all-around vision; __Fort__ +28, __Ref__ +26, __Will__ +24"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290, hydra regeneration"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Hydra Regeneration"
    desc: "  The hydra has regeneration equal to 3 × the number of heads it has. If a hydra's body is missing any heads and the remaining stumps have not been cauterized, the hydra attempts a DC 39 Fortitude check save after it regains Hit Points from regeneration. On a success, one uncauterized stump regrows two heads; on a critical success, two uncauterized stumps regrow into two heads each. The hydra can never grow more than double the number of heads it ordinarily has. The hydra's regeneration only fully deactivates if all its heads are severed and all stumps are cauterized, at which point it dies."

  - name: "Prismatic Backlash"
    desc: "`pf2:r`  **Trigger** A creature successfully cauterizes one of the prismhydra's stumps\n* * *\n\n**Effect** The unstable prismatic energies in the prismhydra's body surge forth. Each creature adjacent to the prismhydra is exposed to its chromatic explosion."

  - name: "Prismatic Head Regrowth"
    desc: "  A prismhydra ordinarily has eight heads. A creature can attempt to sever one of the hydra's heads by specifically targeting it and dealing damage equal to the head's Hit Points. A head that is not completely severed returns to full Hit Points at the end of any creature's turn. A hydra can regrow a severed head using hydra regeneration.\n\nEach head requires a different type of damage to cauterize; typically, two heads each are vulnerable to acid, cold, electricity, and fire damage, but other combinations or more exotic vulnerabilities are possible. When a prismhydra successfully regrows heads, all the heads regrown have the same vulnerability, which must be the same as the vulnerability of one of the prismhydra's unsevered heads.\n\nIf all eight heads are cauterized, the hydra dies.\n\n[[Bestiary Effects/Effect_ Hydra Heads|Effect: Hydra Heads]]"

  - name: "Prismhydra Heads"
    desc: "  **HP** (head) 36, prismatic head regrowth\n\n**Immunities** area damage\n\n**Weaknesses** slashing 15"

  - name: "Reactive Heads"
    desc: "  A hydra gains an extra reaction per round for each of its heads beyond the first, which it can use only to make Reactive Strikes. It can't use more than 1 reaction on the same triggering action, even if a creature leaves several squares within its reach, and the hydra must use a different head for each Reactive Strike it makes. Whenever one of the hydra's heads is severed, the hydra loses 1 of its extra reactions per round."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+31 (reach 15 feet)\n__Damage__  3d12 + 14 piercing plus chromatic-explosion"

  - name: "**Ranged** `pf2:1` Spittle"
    desc: "+28 (acid, range increment 60 feet)\n__Damage__  1d12 acid plus chromatic-explosion"

  - name: "Chromatic Explosion"
    desc: "  A prismhydra's heads are replete with arcane energy. Whenever the prismhydra successfully Strikes an opponent with its spittle, or when an opponent cauterizes one of the prismhydra's heads, the opponent takes 6d6 damage of the type matching the head's vulnerability (typically acid, cold, fire, or electricity), with a DC 37 Reflex check save."
 
```

```encounter-table
name: Prismhydra
creatures:
  - 1: Prismhydra
```




