---
title: "Gorumite Veteran"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.TkW3jUO32YJTT4DO" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Gorumite Veteran"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Prey for Death"
name: "Gorumite Veteran"
level: "Creature 12"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; "
languages: "Common, Skald"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Crafting: +16, Intimidation: +20, Medicine: +21, Warfare Lore: +20"
abilityMods: [7, 4, 6, 2, 4, 3]
speed: 20 feet
sourcebook: "_Pathfinder Adventure: Prey for Death_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +23, __Ref__ +21, __Will__ +19; +2 circumstance vs. fear"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greatsword|+1 Striking Wounding Greatsword]], 3x [[Equipment/Javelin|Javelin]], [[Equipment/Full Plate|+1 Resilient Full Plate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greatsword"
    desc: "+26 (magical, versatile p)\n__Damage__  1d6 bleed 2d12 + 11 slashing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+26 (thrown 30 ft.)\n__Damage__  1d6 + 11 piercing"

  - name: "Consecrated"
    desc: "  As long as the [[Spells/Consecrate|Consecrate]] ritual effects persist in Crownhold, a Gorumite veteran gains a +1 status bonus to attack rolls, skill checks, saving throws, and Perception checks; these bonuses are not calculated into the stat block."

  - name: "Greatsword Critical Specialization"
    desc: "  On a critical hit with a greatsword, the target of the critical hit is knocked off-balance and becomes [[Conditions/Off-Guard|Off-Guard]] until the start of the Gorumite veteran's next turn."

  - name: "Heavy Swing"
    desc: "`pf2:2`  The Gorumite veteran Strikes with their greatsword, dealing 4d12+22 slashing damage plus 1d6 persistent bleed. This counts as two attacks when calculating their multiple attack penalty."

  - name: "Pinning Throw"
    desc: "`pf2:2`  The Gorumite veteran attempts a ranged Strike with their javelin, dealing 3d6+22 piercing damage. If the target is adjacent to a solid surface, they become stuck to that surface by the javelin. The target is [[Conditions/Immobilized|Immobilized]] until they [[Actions/Escape|Escape]] (DC 33). The creature doesn't become stuck if it is incorporeal, is liquid (like a water elemental or some oozes), or could otherwise escape without effort."
 
```

```encounter-table
name: Gorumite Veteran
creatures:
  - 1: Gorumite Veteran
```


Human fighter


