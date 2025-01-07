---
title: "Fungus Leshy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WkcPjO3ugpChwRfO" 
tags:
  - pf2e/creature/type/fungus
  - pf2e/creature/type/leshy
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Fungus Leshy"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Fungus Leshy"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[fungus]]
trait_02: [[leshy]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Common, Fey; Speak with Plants (Fungi Only)"
skills:
  - name: "Skills"
    desc: "Athletics: +6, Nature: +6, Stealth: +8"
abilityMods: [2, 4, 2, -1, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +8, __Ref__ +10, __Will__ +6"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Verdant Burst"
    desc: " (healing,primal,vitality) When a fungus leshy dies, a burst of primal energy explodes from its body, restoring 2d8 healing Hit Points to each fungi creature in a 30-foot emanation. This area is filled with fungi, becoming difficult terrain.\n\nIf the terrain is not a viable environment for this fungi, they wither after 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+10 (agile, finesse)\n__Damage__  1d6 + 2 bludgeoning"

  - name: "**Ranged** `pf2:1` Spore Pod"
    desc: "+10 (range increment 30 feet)\n__Damage__  1d6 + 2 bludgeoning plus spores"

  - name: "Primal Innate Spells"
    desc: "DC 16, attack +8; __3rd __  _[[Spells/Speak with Plants|Speak with Plants (Constant, Fungi Only)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The fungus leshy transforms into a giant mushroom or patch of fungi. This ability otherwise uses the effects of [[Spells/One with Plants|One with Plants]].\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Spore Cloud"
    desc: "`pf2:2` (poison) A fungus leshy can unleash a cloud of spores that irritates the eyes and throats of non-fungus creatures in a 15-foot emanation. Each creature must succeed at a DC 16 Fortitude check save or take 1 persistent poison damage.\n\nA creature has its vision reduced as long as the persistent damage continues and can see only within 20 feet."

  - name: "Spores"
    desc: "  A creature that takes damage from a fungus leshy's spore pod Strike must attempt a saving throw with the same DC (DC 16 Fortitude check) and effect as its Spore Cloud ability"
 
```

```encounter-table
name: Fungus Leshy
creatures:
  - 1: Fungus Leshy
```



Fungus leshies guard caves, bogs, and damp, dark places. Their fungus gardens are bizarre by most standards, but fungus leshies are extremely proud of their works.

* * *

Leshies are intelligent plant creatures who guard areas of primeval wilderness or earthly power. Originally created by powerful fey, they manifest when a skilled practitioner of primal magic—typically a druid—combines a nature spirit with a body carefully grown and crafted from local vegetation. The rites and materials required to create a leshy vary depending on the type of leshy. They are typically given life in an area of great natural significance, such as an arboreal's grove, a druidic circle, a fairy ring, or a great natural wonder.
