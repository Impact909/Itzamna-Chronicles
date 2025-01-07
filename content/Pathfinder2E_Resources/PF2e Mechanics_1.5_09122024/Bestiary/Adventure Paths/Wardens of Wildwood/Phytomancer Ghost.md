---
title: "Phytomancer Ghost"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5txJNzyQBJuQFoPP" 
tags:
  - pf2e/creature/type/ghost
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wood
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Phytomancer Ghost"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Phytomancer Ghost"
level: "Creature 13"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[ghost]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[wood]]
modifier: 23
perception:
  - name: "Perception"
    desc: "+23; Darkvision"
languages: "Arboreal, Muan"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Nature: +26, Stealth: +22, Plane of Wood Lore: +25"
abilityMods: [-5, 5, 5, 2, 7, 6]
speed:  fly 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +20, __Will__ +23"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, rejuvenation, void healing; __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Creature Family Ability Glossary/(Ghost) Rejuvenation|Rejuvenation]]"
    desc: " (divine) When a ghost is destroyed, it re-forms after 2d4 days within the location it's bound to, fully healed. A ghost can be permanently destroyed only if someone determines the reason for its existence and sets right whatever prevents the spirit from resting."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+25 (agile, finesse, magical)\n__Damage__  2d10 + 13 void"

  - name: "Primal Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Execute|Execute]]_, _[[Spells/Pollen Pods|Pollen Pods]]_; __6th __  _[[Spells/Lignify|Lignify]]_, _[[Spells/Tangling Creepers|Tangling Creepers]]_; __5th __  _[[Spells/Life-Draining Roots|Life-Draining Roots]]_, _[[Spells/Toxic Cloud|Toxic Cloud]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Tangle Vine|Tangle Vine]]_, _[[Spells/Timber|Timber]]_"

  - name: "[[Creature Family Ability Glossary/(Ghost) Frightful Moan|Frightful Moan]]"
    desc: "`pf2:1` (auditory,divine,emotion,fear,mental) The ghost laments its fate, forcing each living creature within 30 feet to attempt a DC 33 Will check save. On a failure, a creature becomes [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 3]] on a critical failure). On a success, a creature is temporarily immune to this ghost's frightful moan for 1 minute."

  - name: "Memory of Leaves"
    desc: "`pf2:1` (plant,primal,wood) The ghost mourns its verdant birthplace, creating a swirling cloud of phantom leaves as a 20-foot emanation until the end of its next turn. All creatures within the emanation become [[Conditions/Concealed|Concealed]], and all creatures outside the emanation become concealed to creatures within it. Creatures with the plant or wood traits ignore this concealment.\n\nThe ghost can't use Memory of Leaves again for 1d4 rounds."
 
```

```encounter-table
name: Phytomancer Ghost
creatures:
  - 1: Phytomancer Ghost
```




