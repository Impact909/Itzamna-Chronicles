---
title: "Augur"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Lm8k5aDf10CK9lYF" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Augur"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Augur"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Greater Darkvision"
languages: "Common, Diabolic, Shadowtongue; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Deception: +6, Intimidation: +7, Religion: +4, Stealth: +8, Torture Lore: +7"
abilityMods: [-1, 3, 1, 2, 1, -1]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +4, __Ref__ +10, __Will__ +7"
hp: 14
health:
  - name: ""
  - name: HP
    desc: "14, regeneration 2 (deactivated by holy or silver); __Immunities__  cold; __Weaknesses__ holy 5, silver 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 2 (Deactivated by Holy or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Feel the Blades"
    desc: " (aura,divine,fear,mental,visual) 30 feet. When a creature ends its turn in the aura, it feels the sharp barbs of the augur's blades on its skin. The creature must succeed at a DC 17 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Blade"
    desc: "+8 (agile, finesse, magical, unholy, versatile p)\n__Damage__  1d4 - 1 slashing 1d4 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +7; __4th __  _[[Spells/Read Omens|Read Omens]]_; __2nd __  _[[Spells/Augury|Augury (x2)]]_; __1st __  _[[Spells/Harm|Harm (x3)]]_\n__Cantrips__  __(1st)__ _[[Spells/Telekinetic Hand|Mage Hand]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,mental,visual) The augur stares at a creature they can see within 30 feet. The target must immediately attempt a Will save against Feel the Blades. After attempting this save, the creature is then temporarily immune until the start of the augur's next turn."

  - name: "Whirling Slice"
    desc: "`pf2:2`  The augur Flies or Strides, whirling as they move. The augur deals the damage of their blade Strike to each creature whose space they enter (DC 16 Reflex check save). Each creature is affected only once, even if the augur moves through its space multiple times."
 
```

```encounter-table
name: Augur
creatures:
  - 1: Augur
```



These spherical knots of sinewy muscle, serrated blades, and bloody metal are the most common velstracs on the Shadow Plane. Each augur has only a single eye, from which they can see the horrors inflicted by other velstracs, who train the augur to expect and appreciate pain. Augurs are 1 foot in diameter and weigh 30 pounds.
