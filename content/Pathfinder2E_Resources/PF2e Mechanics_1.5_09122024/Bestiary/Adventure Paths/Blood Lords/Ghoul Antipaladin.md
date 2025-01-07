---
title: "Ghoul Antipaladin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.80w1MgQfBpv9K0Ap" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Ghoul Antipaladin"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Ghoul Antipaladin"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[ghoul]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +20, Intimidation: +20, Religion: +18, Survival: +18, Kabriri Lore: +18"
abilityMods: [6, 4, 6, 1, 4, 4]
speed: 20 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 29
armorclass:
  - name: AC
    desc: "29 31 with shield raised; __Fort__ +21, __Ref__ +15, __Will__ +18"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Flail|Flail]], [[Equipment/Heavy Crossbow|Heavy Crossbow]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Full Plate|Full Plate]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "Destructive Vengeance"
    desc: "`pf2:r` (unholy) **Trigger** The ghoul antipaladin takes damage from an enemy within 15 feet\n* * *\n\n**Effect** The ghoul antipaladin increases the amount of damage they take by 3d6, and they deal 3d6 damage to the triggering enemy, choosing 3d6 spirit or 3d6 void damage to deal to the enemy each time the antipaladin uses this reaction. In addition, the antipaladin deals 4 extra damage of the chosen type with their Strikes against the triggering creature until the end of the antipaladin's turn. An enemy damaged from the ghoul antipaladin's Destructive Vengeance also takes 4 persistent spirit damage; this applies only to the damage the reaction itself deals to the triggering creature, not the damage the antipaladin deals with subsequent Strikes."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+19 ()\n__Damage__  2d8 + 11 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile)\n__Damage__  2d6 + 9 slashing plus ghoul-paralysis"

  - name: "**Melee** `pf2:1` Flail"
    desc: "+19 (disarm, sweep, trip)\n__Damage__  2d10 + 13 bludgeoning"

  - name: "**Ranged** `pf2:1` Heavy Crossbow"
    desc: "+19 (range increment 120 feet, reload 2)\n__Damage__  2d8 + 11 piercing"

  - name: "Divine Focus Spells"
    desc: "1 Focus Point, DC 25, attack +17; __5th __  _[[Spells/Touch of the Void|Touch of Corruption]]_"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul antipaladin is adjacent to the corpse of a creature that died within the last hour\n* * *\n\n**Effect** The ghoul antipaladin devours a chunk of the corpse and regains 4d6 healing Hit Points. It can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 27 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living, non-elf creature hit by a ghoul antipaladin's attack must succeed at a DC 25 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. The creature can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghoul antipaladin jumps up to half its Speed. This movement doesn't trigger reactions."
 
```

```encounter-table
name: Ghoul Antipaladin
creatures:
  - 1: Ghoul Antipaladin
```



The church of Kabriri selects only the most devoted and deadly ghouls to protect their libraries of secret-filled tomes.
