---
title: "Destrachan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jm6SrJaJru5zfcvD" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Destrachan"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Destrachan"
level: "Creature 8"

alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Echolocation 120 Feet"
languages: "Destrachan, Sakvroth; can speak only destrachan"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Stealth: +15, Survival: +18"
abilityMods: [6, 3, 4, 3, 6, 3]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +13, __Will__ +18; +4 status to all saves vs. sonic"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  blinded,  visual; __Resistances__ sonic 15"
abilities_top:
  - name: ""

  - name: "Echolocation 120 feet"
    desc: "  A destrachan can use its hearing as a precise sense at the listed range."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 ()\n__Damage__  2d8 + 10 piercing 1d8 sonic"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile)\n__Damage__  2d8 + 10 slashing"

  - name: "Destructive Harmonics"
    desc: "`pf2:2` (auditory,occult,sonic) The destrachan emits a harsh sonic cry that deals 9d6 sonic damage (DC 26 Reflex check save) in either a 60-foot cone or a 30-foot burst.\n\nIt can't use Destructive Harmonics again for 1d4 rounds."

  - name: "Painful Harmonics"
    desc: "`pf2:2` (auditory,incapacitation,occult) The destrachan emits a sonic cry in either a 60-foot cone or a 30-foot burst. This discordant ululation resonates along the nerves and bones of living creatures in the area, manifesting as waves of incapacitating pain washing over the victims. Each living creature in the area must attempt a DC 26 Fortitude check save.\n\nThe destrachan can't use Painful Harmonics again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Deafened|Deafened]] for 3 rounds and [[Conditions/Stunned|Stunned 2]].\n\n**Critical Failure** The creature is deafened for 1 minute and [[Conditions/Stunned|Stunned 3]]."

  - name: "Shattering Harmonics"
    desc: "`pf2:2` (occult,sonic) The destrachan focuses its harmonics against a single item within 60 feet that is made of crystal, metal, stone, or wood. The target object takes 7d8 sonic damage. If the item is attended, its bearer can attempt a DC 26 Reflex check save for the item.\n\nThe destrachan can't use Shattering Harmonics again for 1d4 rounds."
 
```

```encounter-table
name: Destrachan
creatures:
  - 1: Destrachan
```



This underground reptilian horror walks on two powerful hind legs. Its forelimbs are armed with sharp curving claws, and its toothy, eyeless, tubular head has three hypersensitive frilled ears that turn toward any sound made in its vicinity. This cruel monster's true weapon, however, is an amplified version of the sonic cry that it uses to navigate, communicate, and hunt. It communicates with others of its kind through a complex series of clicks, shrieks, and whistles, but it is intelligent enough to understand other languages. Most destrachans understand at least one other language-usually Sakvroth-and can often be reasoned with.

An obligate carnivore, the destrachan relishes fresh meat but won't hesitate to make a meal of carrion it finds in its path. When traveling in packs, the creatures take great delight in stalking travelers through miles of tunnels before attacking and subduing them, then devouring them alive.
