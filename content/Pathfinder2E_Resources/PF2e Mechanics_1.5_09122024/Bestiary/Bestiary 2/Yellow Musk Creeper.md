---
title: "Yellow Musk Creeper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.L5j9RcwJWc7IZHmy" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Yellow Musk Creeper"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Yellow Musk Creeper"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[plant]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Tremorsense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Stealth: +6"
abilityMods: [3, 2, 4, -5, 0, -1]
speed: 5 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +6, __Will__ +4"
hp: 34
health:
  - name: ""
  - name: HP
    desc: "34; __Immunities__  mental; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+9 (reach 10 feet)\n__Damage__  1d10 + 3 piercing"

  - name: "Bore into Brain"
    desc: "`pf2:3` (manipulate,mental) The creeper bores dozens of tendrils into the brain of a Small, Medium, or Large humanoid creature that's [[Conditions/Unconscious|Unconscious]], willing, or [[Conditions/Fascinated|Fascinated]] by Spray Pollen, and within reach of the creeper's tendrils.\n\nThe creature must succeed at a DC 18 Fortitude check save or become [[Conditions/Stupefied|Stupefied 1]] ([[Conditions/Stupefied|Stupefied 2]] on a critical failure).\n\nSubsequent failed saves against Bore into Brain increase the stupefied value. If the creature reaches stupefied 5, it is turned into a yellow musk thrall. Boring into a creature's brain doesn't end fascination caused by Spray Pollen."

  - name: "Spray Pollen"
    desc: "`pf2:2` (incapacitation,mental,poison) The yellow musk creeper blasts yellow pollen in either a 30-foot line or a 15-foot cone. Each creature in the emanation must attempt a DC 20 Will check save.\n\nOnce a creature succeeds at any save against Spray Pollen, it becomes temporarily immune for 24 hours.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]]. For as long as it is fascinated, it must spend each of its actions to move closer to the yellow musk creeper as expediently as possible, while avoiding obvious dangers. If the creature is adjacent to the yellow musk creeper, it stays still and doesn't act. If anyone takes a hostile action against the creature or its allies, the effect ends. Otherwise, the creature can attempt a new save at the end of each of its turns. On a success, the effects end.\n\n**Critical Failure** As failure, but the condition doesn't end automatically if anyone takes a hostile action against the creature or its allies."
 
```

```encounter-table
name: Yellow Musk Creeper
creatures:
  - 1: Yellow Musk Creeper
```



Made up of thick, green vines with numerous yellow flowers, the yellow musk creeper grows at places where the ground is enriched with spilled blood and corpses, like battlefields and graveyards. An ideal environment for the yellow musk creeper isn't inhabited, but draws occasional humanoid visitors the plant can transform into thralls. The yellow musk creeper enraptures creatures with its bright yellow pollen to bring them close. It then physically alters their brains with its tendrils, implanting a seed in each to turn the creatures into mindless thralls. The yellow musk creeper might try to take over a sleeping creature, but it lacks the faculties to sneak up on anyone, and is likely to wake victims before it can drag itself close enough.

The plant's pollen can spread far on the wind but quickly becomes too diffuse to cause harm. Wilderness scouts learn to sniff out the distinctive musky scent of the pollen, which stays potent even in harmless quantities. A sprouting creeper is also easy to detect, since it grows from the rotting, messy corpse of a thrall creature.
