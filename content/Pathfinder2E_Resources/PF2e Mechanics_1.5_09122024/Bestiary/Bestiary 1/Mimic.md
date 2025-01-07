---
title: "Mimic"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.L2lk3S2X5JDrpNyU" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Mimic"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Mimic"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Deception: +8, Dwelling Lore (applies only to the dungeon it lives in): +10"
abilityMods: [4, 1, 3, 0, 1, 0]
speed: 10 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +11, __Ref__ +9, __Will__ +9"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Adhesive"
    desc: "  The mimic is coated in an adhesive slime. Any creature that hits the mimic, is hit by the mimic, or otherwise touches the mimic must succeed at a DC 23 Reflex check save or become [[Conditions/Grabbed|Grabbed]] (Escape DC 23). A weapon that hits the mimic is stuck to the mimic and can be removed with a successful DC 23 Athletics check check (made as a single action).\n\nA mimic can have any number of objects or creatures stuck to it at a time. The mimic can release a stuck creature or object by using a single action, and the adhesive dissolves 1 minute after the mimic dies, releasing all stuck objects and creatures."

  - name: "Object Lesson"
    desc: "`pf2:r`  **Trigger** A creature touches or physically interacts with the mimic while the mimic is transformed using Mimic Object.\n* * *\n\n**Effect** The triggering creature is automatically stuck by the mimic's adhesive (it receives no save). The mimic then makes a pseudopod Strike against any creature adjacent to the mimic.\n\nObject Lesson can't be used again until the mimic escapes and takes on a new disguise."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pseudopod"
    desc: "+14 ()\n__Damage__  2d8 + 4 bludgeoning plus adhesive"

  - name: "Mimic Object"
    desc: "`pf2:1` (concentrate,polymorph) The mimic assumes the shape of any Medium object. This doesn't change the mimic's texture or overall size but can alter its coloration and visual appearance. It has an automatic result of 28 on Deception checks and DCs to pass as the object that it's mimicking."
 
```

```encounter-table
name: Mimic
creatures:
  - 1: Mimic
```



Thought to be the result of a failed experiment meant to animate objects or a sinister alghollthu creation, mimics are clever monsters that can take the form of common manufactured objects. Mimics are ambush predators and voracious eaters, surprising their prey through their uncanny ability to mimic the form of common furniture and miscellany. They remain disguised until unsuspecting adventurers happen by, then they lash out in ambush.

Mimics possess complex alien minds, and while often cruel and self-serving, they also enjoy conversation with their prey from time to time. For unknown reasons, they are especially interested in humanoids. Mimics have a strong dislike for others of their kind and tend to live alone. A mimic can remain in its alternate form for an extremely long period of time, sometimes remaining disguised in a dungeon chamber for decades. Regardless of how long it waits, the mimic remains vigilant and alert, ready to strike at any moment.
