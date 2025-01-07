---
title: "Anguish Siktempora"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.UpTIXs2A1ZaBzsT5" 
tags:
  - pf2e/creature/type/siktempora
  - pf2e/creature/type/time
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Anguish Siktempora"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Anguish Siktempora"
level: "Creature 13"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[siktempora]]
trait_02: [[time]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision"
languages: "Aklo; Can&#x27;t Speak any Language, Telepathy 300 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +27, Deception: +24, Intimidation: +24, Dimension of Time Lore: +26"
abilityMods: [8, 5, 5, 5, 7, 5]
speed: 10 feet,  fly 40 feet
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +24, __Ref__ +22, __Will__ +26"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, regeneration 40 (deactivated by mental, orichalcum, or spirit); __Immunities__  disease,  emotion,  poison"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 300 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Temporal Sense"
    desc: "  A siktempora can always roll Dimension of Time Lore for initiative. When it does, it gains a +2 circumstance bonus to the roll."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 40 (Deactivated by Mental, Orichalcum, or Spirit)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Foster Fear"
    desc: "  Creatures with the frightened condition are always [[Conditions/Off-Guard|Off-Guard]] to the anguish siktempora."

  - name: "Uncanny Pounce"
    desc: "`pf2:0`  **Trigger** The anguish siktempora rolls Dimension of Time Lore for initiative\n* * *\n\n**Effect** The siktempora Strides once and makes a jaws Strike, in either order."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 ()\n__Damage__  3d6 + 14 bludgeoning 2d6 sonic"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile)\n__Damage__  3d8 + 14 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Flicker|Flicker]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_\n__Constant__  __(7th)__ _[[Spells/Fly|Fly]]_"

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."

  - name: "Scream of Despair"
    desc: "`pf2:2` (emotion,mental,occult,sonic) The anguish siktempora emits a terrible scream in a 30-foot emanation. Creatures in the area must attempt a DC 33 Will check save. The anguish siktempora can't use Scream of Despair for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 2d6 mental damage, 2d6 sonic damage, and is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature takes 6d6 mental damage, 6d6 sonic damage, and is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** As failure, but [[Conditions/Frightened|Frightened 3]] and the creature gains weakness to mental 15 (this weakness applies to this Scream of Despair)."

  - name: "Wracking Despair"
    desc: "`pf2:1` (emotion,mental,occult) **Frequency** once per round\n* * *\n\n**Effect** The anguish siktempora projects their crippling despair into the mind of a [[Conditions/Frightened|Frightened]] creature they can see within range of their telepathy. The frightened creature takes 6d6 mental damage (DC 30 Will check save)."
 
```

```encounter-table
name: Anguish Siktempora
creatures:
  - 1: Anguish Siktempora
```




