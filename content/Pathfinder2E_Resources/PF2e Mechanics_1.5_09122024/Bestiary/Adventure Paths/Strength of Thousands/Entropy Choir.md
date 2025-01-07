---
title: Entropy Choir
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #173: Doorway to the Red Star
aliases: "Actor.ixWXlkDh4LzGD5wr" 
level: 15
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #173: Doorway to the Red Star"
name: "Entropy Choir"
level: "Hazard 15"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 33
sourcebook: "_Pathfinder #173: Doorway to the Red Star_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +23, __Ref__ +25, __Will__ +29"
hp: 90
health:
  - name: ""
  - name: "HP"
    desc: "90; __Hardness__ 24; __Immunities__  object immunities,  critical hits,  void,  precision"
perception:
  - name: ""
  - name: "Stealth DC 33" 
    desc: "**Performance** +33 (master); creatures in the area automatically notice the eerily swaying shadows"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A choir of ghostly shadows fill the benches in this room, chanting a haunting and unearthly melody."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 40 Religion check (master) to exorcise the spirits and break the power binding them into a single entity, or DC 35 Performance check (expert) to counter the choir and nullify the destructive elements of its song"
attacks:
  - name: ""

  - name: "Call to Nothingness"
    desc: "`pf2:r` (auditory, divine, mental, sonic) **Trigger** A living creature moves more than 10 feet into area **A3**\n* * *\n\n**Effect** The eerie call of the entropy choir saps the will of living creatures. A living creature who fails a DC 36 Will check save becomes [[Conditions/Slowed|Slowed 1]] as long as they remain in area **A3**. The entropy choir then rolls initiative."

  - name: "Routine"
    desc: "(3 actions; auditory, divine, evocation, sonic) The choir continues to sing its grim dirge every round until it is disabled or destroyed. If there are any non‑slowed living creatures in area **A3** when its turn starts, it first uses Call to Nothingness as a single action.\n\nIt uses its remaining actions (or all three actions if there are slowed living creatures in the room already) to focus soul‑shattering choruses onto individual targets.\n\nThe choir can target any living creature in area **A3** with an action, but never more than once per round per creature. It prefers to attack slowed creatures over all others, but it targets non‑slowed creatures if they're the only viable targets. A targeted creature must attempt a DC 36 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target takes 5d6 sonic damage.\n\n**Failure** The target takes 10d6 sonic damage.\n\n**Critical Failure** The target takes 15d6 sonic damage and increases their [[Conditions/Drained|Drained]] condition by 1, to a maximum of drained 4."
  - name: "Reset"
    desc: "The entropy choir resets automatically after 24 hours, even if it has been disabled or destroyed. It fades away forever once Dwandek and other members of the cult to which it sings its praises are destroyed."
```

```encounter-table
name: Entropy Choir
creatures:
  - 1: Entropy Choir
```

