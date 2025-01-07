---
title: "Hundun Chaos Mage"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kCo8fhYYmVh0AcFy" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Hundun Chaos Mage"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Hundun Chaos Mage"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Motion Sense (Precise) 100 Feet"
languages: "Aklo, Chthonian, Protean; can&#x27;t speak any language, telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +37, Intimidation: +38, Occultism: +34"
abilityMods: [9, 6, 7, 4, 6, 8]
speed: 50 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +27, __Ref__ +30, __Will__ +33; +1 status to all saves vs. magic"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  auditory,  cold,  mental,  poison,  visual; __Resistances__ fire 20, physical 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Motion Sense 100 feet"
    desc: "  A hundun chaos mage can sense nearby motion through vibration and air movement."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Entropic Feedback"
    desc: "`pf2:r`  **Trigger** A creature attempts to target the hundun with a mental effect\n* * *\n\n**Effect** The triggering creature is subject to the utter chaos of the hundun's mind and must attempt a DC 40 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 10d6 mental damage.\n\n**Failure** The creature takes 10d6 mental damage, is [[Conditions/Drained|Drained 1]], and is [[Conditions/Stupefied|Stupefied 1]] for 1 minute.\n\n**Critical Failure** As failure, but the creature is [[Conditions/Drained|Drained 2]] and [[Conditions/Stupefied|Stupefied 2]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+33 (agile, finesse, magical, reach 10 feet)\n__Damage__  4d8 + 12 bludgeoning 1d6 void"

  - name: "Occult Innate Spells"
    desc: "DC 40, attack +35; __9th __ (3 slots) _[[Spells/Disintegrate|Disintegrate]]_, _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Harm|Harm (x3)]]_; __8th __ (3 slots) _[[Spells/Divine Wrath|Divine Wrath]]_; __7th __ (1 slots) _[[Spells/Interplanar Teleport|Plane Shift (At Will)]]_; __4th __ (1 slots) _[[Spells/Translocate|Dimension Door (At Will)]]_; __1st __ (1 slots) _[[Spells/Detect Alignment|Detect Alignment (At Will) (Lawful Only)]]_\n__Constant__  __(4th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Activate Attractor"
    desc: "`pf2:1` (mental,occult) The hundun releases its staff-like attractor, which hovers in place. The hundun can use an action, which has the concentrate trait, to move the attractor up to 60 feet, to a maximum of 300 feet from the hundun. It can also use an action, which has the concentrate trait, to recall the attractor, which flies to the hundun and immediately deactivates.\n\nCreatures within 40 feet of the attractor must attempt a DC 40 Will check save if they're within the area when the attractor is activated or as soon as they enter the area while it's active. Once a creature has attempted the save, it uses the same result for the rest of that activation of the attractor.\n\nAny restrictions on a creature's movement apply only if it voluntarily moves away from the attractor. For example, if the attractor moves closer to a creature, the creature doesn't then need to move away.\n\nChaotic creatures are immune to the effects of the attractor.\n\nThe attractor can't be harmed by physical attacks but is destroyed by [[Spells/Disintegrate|Disintegrate]], [[Spells/Disjunction|Disjunction]], a [[Equipment/Rod of Cancellation|Rod of Cancellation]], a [[Equipment/Sphere of Annihilation|Sphere of Annihilation]], and other similarly powerful effects.\n\nThe attractor has an AC of 40 and a counteract DC of 37. A hundun can rebuild a destroyed attractor after 1d8 hours of uninterrupted meditation. If the hundun is slain, its attractor disappears.\n* * *\n\n**Critical Success** The creature's movement isn't restricted.\n\n**Success** The creature treats each square in the area as difficult terrain when moving away from the attractor.\n\n**Failure** The creature can't move away from the attractor within the area."

  - name: "Flurry of Blows"
    desc: "`pf2:1` (flourish) The hundun makes two Strikes with its fist. If both hit the same creature, combine their damage for the purpose of resistances and weaknesses."
 
```

```encounter-table
name: Hundun Chaos Mage
creatures:
  - 1: Hundun Chaos Mage
```




