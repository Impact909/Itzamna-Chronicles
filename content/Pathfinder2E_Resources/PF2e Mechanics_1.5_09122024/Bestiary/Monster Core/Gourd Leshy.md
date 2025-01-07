---
title: "Gourd Leshy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.V3jeLSi4qBegj2i7" 
tags:
  - pf2e/creature/type/leshy
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Gourd Leshy"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Gourd Leshy"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[leshy]]
trait_02: [[plant]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Low-Light Vision"
languages: "Common, Fey; Speak with Plants (Gourds Only)"
skills:
  - name: "Skills"
    desc: "Nature: +5, Stealth: +7"
abilityMods: [2, 4, 2, -1, 2, 0]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +5, __Ref__ +9, __Will__ +7"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""

  - name: "Keepsake"
    desc: " (primal) The leshy can store an item of light Bulk or less in their head, concealing it as [[Spells/Veil of Privacy|Veil of Privacy]]. If stored for 24 hours, the item benefits from [[Spells/Mending|Mending]]."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Verdant Burst"
    desc: " (healing,primal,vitality) When a gourd leshy dies, a burst of primal energy explodes from their body, restoring 1d8 Hit Points to each plant creature in a 30-foot emanation. This area is filled with gourds, becoming difficult terrain.\n\nIf the terrain is not a viable environment for these gourds, they wither after 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 (agile, finesse)\n__Damage__  1d4 + 2 bludgeoning plus ensnare"

  - name: "**Ranged** `pf2:1` Seed"
    desc: "+9 (range increment 30 feet)\n__Damage__  1d6 + 2 bludgeoning plus ensnare"

  - name: "Primal Innate Spells"
    desc: "DC 15, attack +7; __3rd __  _[[Spells/Speak with Plants|Speak with Plants (Constant, Gourds Only)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The gourd leshy transforms into a Small gourd-bearing plant. This ability otherwise uses the effects of [[Spells/One with Plants|One with Plants]].\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Ensnare"
    desc: "  When the gourd leshy damages a creature with a fist or seed Strike, vines lash out from the leshy (or seed) and wrap around the target's limbs.\n\nThe target must attempt a DC 17 Reflex check save. On a failure, the target takes a –10-foot status penalty to its Speed for 1 round; on a critical failure, the target is [[Conditions/Immobilized|Immobilized]] for 1 round and the penalty to Speed lasts for 1 minute.\n\n[[Bestiary Effects/Effect_ Ensnare|Effect: Ensnare]]"
 
```

```encounter-table
name: Gourd Leshy
creatures:
  - 1: Gourd Leshy
```



Gourd leshies are guardians of fields, gardens, and farms. Many villages benefit from the protection of a gourd leshy, even if they are unaware of it.

* * *

Leshies are intelligent plant creatures who guard areas of primeval wilderness or earthly power. Originally created by powerful fey, they manifest when a skilled practitioner of primal magic—typically a druid—combines a nature spirit with a body carefully grown and crafted from local vegetation. The rites and materials required to create a leshy vary depending on the type of leshy. They are typically given life in an area of great natural significance, such as an arboreal's grove, a druidic circle, a fairy ring, or a great natural wonder.
