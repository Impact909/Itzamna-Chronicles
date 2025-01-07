---
title: "Nydazuul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6ZxIq1ZbxvM1r5jm" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/qlippoth
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Nydazuul"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #184: The Ghouls Hunger"
name: "Nydazuul"
level: "Creature 11"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[qlippoth]]
trait_05: [[unholy]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Greater Darkvision, Scent (Imprecise) 30 Feet, Truesight"
languages: "Chthonian; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Athletics: +23, Intimidation: +20"
abilityMods: [6, 4, 6, -2, 3, 3]
speed: 40 feet,  climb 40 feet,  fly 40 feet
sourcebook: "_Pathfinder #184: The Ghouls Hunger_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +23, __Ref__ +21, __Will__ +20"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Immunities__  controlled,  fear effects; __Resistances__ mental 10, physical 10 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bite"
    desc: "+23 (magical, reach 10 feet, unholy)\n__Damage__  2d10 + 12 piercing plus rotting-curse 2d6 bleed plus rotting-curse 1d6 spirit plus rotting-curse"

  - name: "**Melee** `pf2:1` Sting"
    desc: "+23 (agile, finesse, magical, reach 15 feet, unholy)\n__Damage__  2d4 + 12 slashing 2d6 bleed 1d6 spirit"

  - name: "Occult Innate Spells"
    desc: "DC 31, attack +21; __5th __  _[[Spells/Translocate|Dimension Door (x3)]]_\n__Constant__  __(7th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Confusing Display"
    desc: "`pf2:2` (concentrate,emotion,fear,incapacitation,mental,occult,visual) The augnagar's writhing limbs and flesh seethe and squirm in a disorienting and unsettling manner. Creatures in a 30-foot emanation must attempt a DC 30 Will check save, after which they are temporarily immune to further Confusing Displays for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round.\n\n**Failure** The creature is [[Conditions/Stupefied|Stupefied 1]] and [[Conditions/Confused|Confused]] for 1 minute.\n\n**Critical Failure** As failure, but the creature can't attempt a flat check to recover from confusion whenever it takes damage from an attack or spell."

  - name: "Inhale Vitality"
    desc: "`pf2:2` (occult) **Frequency** once per day\n* * *\n\n**Effect** The augnagar inhales sharply, drawing life force out of creatures in a 50-foot cone. Creatures in the area take 11d6 void damage (DC 30 Fortitude check save, and the creature is fatigued on a failure). The augnagar becomes [[Conditions/Quickened|Quickened]] for 1 round on its next turn, and it can use the extra action only to Stride or Strike."

  - name: "Rotting Curse"
    desc: " (curse,disease,occult) **Saving Throw** DC 30 Fortitude check\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 2]] and the creature displays hideous, festering wounds exuding a horrific stench. Any creature within 30 feet of the victim must succeed at a DC 30 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] on a critical failure, for as long as it's sickened).\n\nWhile within the aura, affected creatures take a -2 circumstance penalty to saves against disease and to recover from the sickened condition. A creature that succeeds at its save is temporarily immune for 1 minute. The victim of the disease doesn't roll a save, but takes the failure effects automatically and can't reduce its sickened value below 1 (1 day)."
 
```

```encounter-table
name: Nydazuul
creatures:
  - 1: Nydazuul
```


Variant augnagar

The brutish and gluttonous augnagar live to feast- preferably on rotten flesh, and when possible, demon flesh. But to them, the greatest delicacy is the flesh of other augnagars. Augnagars have spiderlike legs with leathery membranes like a bat's wings, and three tails ending in hooked claws perfect for slicing flesh.
