---
title: "Seething Spirit"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9kssKt9QJmx0zkVD" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Seething Spirit"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Seething Spirit"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[spirit]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Dwarven, Jotun; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Deception: +20, Diplomacy: -5, Intimidation: +24, Stealth: +21"
abilityMods: [-5, 6, 0, 2, -2, 7]
speed:  fly 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +17, __Ref__ +23, __Will__ +21"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Weaknesses__ emotion 12; __Resistances__ all damage 10 (except force, ghost touch, mental, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "Taste Anger (Imprecise) 1 mile"
    desc: " (detection,occult) The spirit can taste anger and hatred from creatures experiencing those emotions within 1 mile (imprecise)."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Pulse of Rage"
    desc: " (aura,emotion,mental,occult) 20 feet. This aura emanates from any creature possessed by the seething spirit, and it's inactive while the spirit isn't possessing anyone.\n\nAny creature in the aura, including a creature possessed by the spirit, takes a -1 status penalty to AC, can't perform actions with the concentrate trait except for the [[Actions/Seek|Seek]] action and actions with the rage trait, and gains a +2 status bonus to melee damage rolls against the spirit's enemies.\n\nA creature can attempt a DC 30 Will check save when it enters the aura to avoid the effect. If the creature would need to attempt a save against the aura again within 24 hours, it automatically uses the same save result rather than attempting a new save.\n\n[[Bestiary Effects/Effect_ Pulse of Rage|Effect: Pulse of Rage]]"

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Vulnerable to Calm Emotions"
    desc: "  A seething spirit can't attempt to possess a creature affected by [[Spells/Calm|Calm]]. If creature possessed by a seething spirit fails a saving throw against _calm emotions_, the spirit is forced out.\n\nIf the spirit isn't possessing a creature and is targeted with _calm emotions_, the spirit takes 12 mental damage per rank of the spell instead of the normal spell effects."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ephemeral Claw"
    desc: "+22 (occult)\n__Damage__  3d12 + 7 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 32, attack +24; __6th __  _[[Spells/Paranoia|Paranoia]]_, _[[Spells/Clear Mind|Remove Fear]]_, _[[Spells/Suggestion|Suggestion (x3)]]_; __3rd __  _[[Spells/Mind Reading|Mind Reading (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will) (Self Only)]]_, _[[Spells/Ventriloquism|Ventriloquism (At Will)]]_\n__Constant__  __(6th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Furious Possession"
    desc: "`pf2:2`  The seething spirit attempts to possess an adjacent corporeal creature. This has the same effect as a [[Spells/Possession|Possession]] spell (DC 30 Will check), except since the spirit doesn't have a physical body, they're not [[Conditions/Unconscious|Unconscious]] and [[Conditions/Paralyzed|Paralyzed]] when the effect ends. The spirit can't Dismiss the possession.\n\nThe creature gains 12 temporary Hit Points that are lost when the possession ends. During the possession, the creature has the pulse of rage aura. Each time the possessed creature makes a melee Strike, the spirit can substitute their ephemeral claw attack modifier, damage amount, or both in place of the creature's own statistics.\n\n[[Bestiary Effects/Effect_ Furious Possession|Effect: Furious Possession]]"
 
```

```encounter-table
name: Seething Spirit
creatures:
  - 1: Seething Spirit
```



Hatred so powerful it lives beyond the grave-this sentiment animates the ephemeral crimson apparitions known as seething spirits. Single-minded in nature, they stoke the fires of anger and hate, capable of planning and strategy, but the one thing beyond their grasp is personal growth. Though similar to ghosts, seething spirits retain much less of their former living selves. Most of their soul has moved on, and only the fury remains. There's no way to set a seething spirit to rest: only violence can destroy it.

By possessing a creature and nurturing the seeds of resentment and rage already within its mind, a seething spirit can greatly alter the host's behavior and personality. When broached about such changes, a host might claim they're just finally "telling it like it is." Because a seething spirit can't voluntarily end its possession, it's essentially one with its victim until the victim's rage results in death. A seething spirit doesn't take pleasure in this death-they rapidly move on in search of a new rageful host.
