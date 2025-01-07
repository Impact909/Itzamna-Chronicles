---
title: "Leaf Leshy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LmIpldsoOazdMlKs" 
tags:
  - pf2e/creature/type/leshy
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Leaf Leshy"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Leaf Leshy"
level: "Creature 0"

alignment: ""
size: "Small"
trait_01: [[leshy]]
trait_02: [[plant]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Low-Light Vision"
languages: "Common, Fey; Speak with Plants (Trees Only)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +4, Nature: +4, Stealth: +4"
abilityMods: [-1, 2, 2, -2, 2, 1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +6, __Will__ +4"
hp: 15
health:
  - name: ""
  - name: HP
    desc: "15; __Weaknesses__ fire 2"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|Longspear]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Verdant Burst"
    desc: " (healing,primal,vitality) When a leaf leshy dies, a burst of primal energy explodes from their body, restoring 1d4 Hit Points to each plant creature in a 30-foot emanation. This area is filled with tree saplings, becoming difficult terrain.\n\nIf the terrain is not a viable environment for these trees, they wither after 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longspear"
    desc: "+3 (reach 10 feet)\n__Damage__  1d8 - 1 piercing"

  - name: "**Ranged** `pf2:1` Seedpod"
    desc: "+6 (range increment 30 feet)\n__Damage__  1d6 bludgeoning plus deafening-blow"

  - name: "Primal Innate Spells"
    desc: "DC 14, attack +6; __3rd __  _[[Spells/Speak with Plants|Speak with Plants (Constant, Trees Only)]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The leaf leshy transforms into a Small tree. This ability otherwise uses the effects of [[Spells/One with Plants|One with Plants]].\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Deafening Blow"
    desc: "  When a leaf leshy hits with their seedpod Strike, the pod explodes loudly. The target must attempt a DC 16 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected and temporarily immune for 24 hours.\n\n**Success** The target is unaffected.\n\n**Failure** The target is [[Conditions/Deafened|Deafened]] for 1 round.\n\n**Critical Failure** The target is deafened for 1 minute."

  - name: "Glide"
    desc: "`pf2:1` (move) The leshy glides gently through the air, moving 5 feet toward the ground and up to 25 feet forward. As long as the leshy spends at least 1 action gliding each round, they remain in the air at the end of each turn. For the purpose of determining damage from falls, a leaf leshy always treats falls as if they were 20 feet shorter."
 
```

```encounter-table
name: Leaf Leshy
creatures:
  - 1: Leaf Leshy
```



Leaf leshies are diminutive protectors of forests clad in armor and hats made of fruit, flowers, or leaves. They enjoy mock battles but act cautiously in real ones.

* * *

Leshies are intelligent plant creatures who guard areas of primeval wilderness or earthly power. Originally created by powerful fey, they manifest when a skilled practitioner of primal magic—typically a druid—combines a nature spirit with a body carefully grown and crafted from local vegetation. The rites and materials required to create a leshy vary depending on the type of leshy. They are typically given life in an area of great natural significance, such as an arboreal's grove, a druidic circle, a fairy ring, or a great natural wonder.
