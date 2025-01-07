---
title: "Drow Warden"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wJgxCM9TjFQ2Hmah" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/drow
  - pf2e/creature/type/elf
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Drow Warden"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #165: Eyes of Empty Death"
name: "Drow Warden"
level: "Creature 4"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[drow]]
trait_03: [[elf]]
trait_04: [[humanoid]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Elven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Intimidation: +8, Stealth: +9, Survival: +11"
abilityMods: [4, 3, 1, 0, 3, 0]
speed: 30 feet
sourcebook: "_Pathfinder #165: Eyes of Empty Death_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +11, __Will__ +9; +1 status to all saves vs. magic, +2 status to all saves vs. mental"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  sleep"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Elven Curve Blade|Elven Curve Blade]], [[Equipment/Hand Crossbow|Hand Crossbow]], [[Equipment/Chain Mail|Chain Mail]], 10x [[Equipment/Bolts|Bolts]], 3x [[Equipment/Lethargy Poison|Lethargy Poison]]"
  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Elven Curve Blade"
    desc: "+14 (forceful)\n__Damage__  1d8 + 6 slashing plus hampering-slash"

  - name: "**Ranged** `pf2:1` Hand Crossbow"
    desc: "+13 (range increment 60 feet, reload 1)\n__Damage__  1d6 + 2 piercing plus lethargy-poison"

  - name: "Divine Innate Spells"
    desc: "DC 19, attack +11; __2nd __  _[[Spells/Darkness|Darkness (At Will)]]_, _[[Spells/Faerie Fire|Faerie Fire (At Will)]]_\n__Cantrips__  __(2nd)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_"

  - name: "Hampering Slash"
    desc: "  A target damaged by the warden's melee Strike must succeed at a DC 21 Fortitude check save or be [[Conditions/Slowed|Slowed 1]] until the end of the warden's next turn."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  A warden deals an extra 1d6 damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Drow Warden
creatures:
  - 1: Drow Warden
```



Wardens watch over drow encampments and often work in small groups.

* * *

Drow have a reputation for evil due to demon worship in their major settlements. However, like members of any ancestry, drow can have any alignment, especially when removed from the demon lords' sinister influence.
