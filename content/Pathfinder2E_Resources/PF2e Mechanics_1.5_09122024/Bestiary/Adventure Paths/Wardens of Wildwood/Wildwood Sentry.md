---
title: "Wildwood Sentry"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W7ceDuOfIewLrZc6" 
tags:
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Wildwood Sentry"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #203: Shepherd of Decay"
name: "Wildwood Sentry"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[human]]
trait_02: [[humanoid]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; "
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Medicine: +18, Nature: +20, Stealth: +20, Survival: +20, Forest Lore: +16"
abilityMods: [4, 4, 2, 1, 4, 0]
speed: 25 feet
sourcebook: "_Pathfinder #203: Shepherd of Decay_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +18, __Ref__ +20, __Will__ +18"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Battle Axe|Battle Axe]], [[Equipment/Dagger|Dagger]], [[Equipment/Composite Longbow|+1 Composite Longbow]], [[Equipment/Leather Armor|Leather Armor]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "Forager"
    desc: "  While using Survival to Subsist, if the sentry rolls a failure or a critical failure, they get a success instead. If the sentry rolls a success, they can provide food for 16 additional creatures that eat about as much as a human, or 32 creatures on a critical success."

  - name: "Forest Walker"
    desc: "  The sentry ignores the effects of difficult terrain from a forest environment. They can [[Actions/Sneak|Sneak]] through underbrush without the need to attempt a Stealth check as long as the sentry moves no more than 5 feet at a time and isn't within 10 feet of an enemy at any point during their movement."

abilities_mid:
  - name: ""
  - name: "Sentry's Warning"
    desc: "`pf2:r`  **Trigger** The sentry is about to roll Perception or Survival to determine their initiative;\n* * *\n\n**Effect** The sentry visually or audibly warns allies, granting them a +1 circumstance bonus to their initiative rolls. Depending on how the sentry warns allies, this action has the auditory or visual trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+21 (agile, finesse, versatile s)\n__Damage__  1d4 + 12 piercing"

  - name: "**Melee** `pf2:1` Battle Axe"
    desc: "+21 (sweep)\n__Damage__  1d8 + 12 slashing"

  - name: "**Ranged** `pf2:1` Composite Longbow"
    desc: "+22 (deadly d10, magical, propulsive, range increment 100 feet, reload 0, volley 30 ft.)\n__Damage__  1d8 + 11 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +17; __3rd __  _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Earthbind|Earthbind]]_; __2nd __  _[[Spells/Revealing Light|Revealing Light]]_, _[[Spells/Speak with Animals|Speak with Animals (At Will)]]_\n__Cantrips__  __(3rd)__ _[[Spells/Know the Way|Know the Way]]_, _[[Spells/Sigil|Sigil]]_"

  - name: "Hunt Prey"
    desc: "`pf2:1` (concentrate) The sentry designates a single creature they can see and hear, or one they're Tracking, as their prey. The sentry gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] the prey and to Survival checks to [[Actions/Track|Track]] the prey.\n\nThe first time the sentry hits the designated prey in a round, they deal an additional 1d8 precision damage. The sentry also ignores the penalty for making ranged attacks within their second range increment against the prey they're hunting.\n\nThese effects last until the sentry uses Hunt Prey again."

  - name: "Protector of Arenway"
    desc: "  The sentry can only cast its primal innate spells while on the Isle of Arenway."
 
```

```encounter-table
name: Wildwood Sentry
creatures:
  - 1: Wildwood Sentry
```




