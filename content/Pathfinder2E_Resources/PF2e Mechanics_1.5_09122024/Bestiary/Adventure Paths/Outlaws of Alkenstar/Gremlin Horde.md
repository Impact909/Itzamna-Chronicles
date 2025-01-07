---
title: Gremlin Horde
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - pf2eHazard
  - complex
source: Pathfinder #180: The Smoking Gun
aliases: "Actor.cvrRrC7G6bw1MI6B" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Gremlin Horde"
level: "Hazard 6"

trait_06: "Complex"
trait_01: [[magical]]
modifier: 18
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +11, __Ref__ +17, "
hp: 66
health:
  - name: ""
  - name: "HP"
    desc: "66; __Hardness__ 15; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 18" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three gangs of gremlins hide within the spiral centurion, cackling with glee and hurling blasts of hex magic. The hazard occupies the same space as the spiral centurion, moving with it."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Arcana check, DC 25 Occultism check, or DC 25 Religion check (trained) to devise counter-hex symbols that frighten and scatter a gremlin gang, or DC 28 Acrobatics check or DC 28 Stealth check (expert) to capture and scatter a gremlin gang"
attacks:
  - name: ""

  - name: "Hexed Calamity"
    desc: "`pf2:r` **Trigger** A creature comes within 30 feet of the gremlin horde\n* * *\n\n**Effect** Every firearm within 30 feet misfires. If a creature is holding the firearm, they can attempt a DC 27 Will check save, negating this effect on a success. The hazard rolls initiative."

  - name: "Hardness 15 (While Inside the Centurion)"
    desc: "passive "

  - name: "Routine"
    desc: "(3 actions; misfortune) The gremlin horde hurls one tinkering curse with each action, targeting an item within 60 feet wielded or worn by a creature. The creature must attempt a DC 27 Will check save. The gremlin horde loses 1 action for each gremlin gang that's scattered.\n* * *\n\n**Critical Success** The hex bounces back to affect the gremlin horde. For 1 round, all creatures gain a +1 status bonus to checks to disable this hazard.\n\n**Success** The item is unaffected.\n\n**Failure** The item becomes unreliable for 1 round. If a creature attempts to Activate the item or Interact with it, it must succeed at a DC 5 Flat check or the action is wasted. If the item doesn't have an active use (such a mundane cloak), the creature wearing the item must instead immediately succeed at a DC 5 Flat check or become tangled with the item and fall [[Conditions/Prone|Prone]].\n\n**Critical Failure** As failure, but the creature wielding or wearing the item also becomes [[Conditions/Clumsy|Clumsy 2]]."
  - name: "Reset"
    desc: "If not captured or killed, the scattered gremlin gangs regroup after 1d4 hours."
```

```encounter-table
name: Gremlin Horde
creatures:
  - 1: Gremlin Horde
```

