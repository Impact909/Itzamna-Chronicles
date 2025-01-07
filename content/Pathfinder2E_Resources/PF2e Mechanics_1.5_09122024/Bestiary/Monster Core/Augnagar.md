---
title: "Augnagar"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HWG4JnjLmIkl8k79" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/qlippoth
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Augnagar"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Augnagar"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[fiend]]
trait_02: [[qlippoth]]
trait_03: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Scent (Imprecise) 30 Feet, Truesight"
languages: "Chthonian; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +28, Intimidation: +26"
abilityMods: [8, 5, 8, -2, 5, 4]
speed: 40 feet,  climb 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +28, __Ref__ +23, __Will__ +25"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225; __Immunities__  controlled,  fear effects; __Resistances__ mental 15, physical 15 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 (magical, reach 10 feet, unholy)\n__Damage__  3d12 + 14 piercing plus rotting-curse 3d6 bleed plus rotting-curse"

  - name: "**Melee** `pf2:1` Sting"
    desc: "+28 (agile, finesse, magical, reach 15 feet, unholy)\n__Damage__  3d8 + 14 slashing 3d6 bleed"

  - name: "Occult Innate Spells"
    desc: "DC 31, attack +23; __5th __  _[[Spells/Translocate|Translocate (x3)]]_\n__Constant__  __(7th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "Confusing Display"
    desc: "`pf2:2` (concentrate,emotion,fear,incapacitation,mental,occult,visual) The augnagar's writhing limbs and flesh seethe and squirm in a disorienting and unsettling manner. Creatures in a 30-foot emanation must attempt a DC 34 Will check save, after which they are temporarily immune to further Confusing Displays for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round.\n\n**Failure** The creature is stupefied 1 and [[Conditions/Confused|Confused]] for 1 minute.\n\n**Critical Failure** As failure, but the creature can't attempt a flat check to recover from confusion whenever it takes damage from an attack or spell."

  - name: "Inhale Vitality"
    desc: "`pf2:2` (occult,void) **Frequency** once per day\n* * *\n\n**Effect** The augnagar inhales sharply, drawing life force out of creatures in a 50-foot cone. Creatures in the area take 14d6 void damage with a DC 34 Fortitude check save. A creature that fails its save is also [[Conditions/Fatigued|Fatigued]].\n\nIf any creatures take damage from this activity, the augnagar becomes [[Conditions/Quickened|Quickened]] for 1 round, and it can use the extra action only to Stride or Strike."

  - name: "Rotting Curse"
    desc: " (curse,disease,occult) **Saving Throw** DC 32 Fortitude check\n* * *\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 day)\n\n**Stage 2** drained 2 and the creature displays hideous, festering wounds exuding a horrific stench. When the victim takes piercing or slashing damage, creatures within 30 feet must succeed at a DC 32 Fortitude check save or become [[Conditions/Sickened|Sickened 1]]. The victim automatically fails this save (1 day)."
 
```

```encounter-table
name: Augnagar
creatures:
  - 1: Augnagar
```



The brutish and gluttonous augnagar live to feast—preferably on rotten flesh and, when possible, demon flesh. But to them, the greatest delicacy is the flesh of other augnagars. Augnagars have swollen, spiderlike legs with leathery membranes like a bat's wings, and three tails ending in hooked stings perfect for slicing flesh.

An augnagar that gorges sufficiently, especially on other augnagars, can grow so massive it can't even move, thrashing and festering where it lies. It eventually flies into a frenzy of self-cannibalism as it rips apart its own flesh to feast on. From the ruinous remains emerges a thulgant—a smaller but more powerful qlippoth.

* * *

Long before the creatures known as demons came to be the dominant force in the Outer Rifts, qlippoth ruled the innumerable cracks of the Outer Sphere. These inimical creatures are a form of primordial and alien evil that predates mortal life, and most immortal life as well. Since the rise of mortal sin and the associated expansion of demonic life through the Outer Rifts, qlippoth have been driven to their deepest reaches, and they seethe with rancor at the loss of their realms. Yet, rather than directly oppose demons, qlippoth instead turn to the source—mortal sin—and wage an endless war to eradicate all creatures capable of sinful acts so that the demonic tide might be turned back. To ensure they do not bolster their foe's ranks, they enact horrific transformations on their targets, converting their victims into beings incapable of discerning right from wrong; this renders them unable to be judged by Pharasma's courts and thus incapable of becoming fiends. Most mortals consider the ministrations of a qlippoth to be far worse than any fate awaiting them in the afterlife.
