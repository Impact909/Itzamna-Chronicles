---
title: "Virtuosic Lyrebird"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vVbyCaQEtzhRwB6I" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Virtuosic Lyrebird"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Virtuosic Lyrebird"
level: "Creature 6"

alignment: ""
size: "tiny"
trait_01: [[beast]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; "
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Arcana: +14, Performance: +16, Stealth: +12"
abilityMods: [4, 5, 2, 3, 2, 4]
speed: 15 feet,  fly 60 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +9, __Ref__ +17, __Will__ +14"
hp: 65
health:
  - name: ""
  - name: HP
    desc: "65"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Counter-Melody"
    desc: "`pf2:r`  **Trigger** An opponent within 60 feet Casts a Spell\n* * *\n\n**Effect** The virtuosic lyrebird makes a counteract check against the triggering spell (+14 counteract modifier)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+12 (finesse)\n__Damage__  2d8 + 4 piercing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+12 (agile, finesse)\n__Damage__  2d6 + 4 piercing"

  - name: "Arcane Spontaneous Spells"
    desc: "DC 24, attack +16; __3rd __ (2 slots) _[[Spells/Force Barrage|Force Barrage]]_, _[[Spells/Hypnotize|Hypnotize]]_; __2nd __ (2 slots) _[[Spells/Breathe Fire|Breathe Fire]]_, _[[Spells/Shatter|Shatter]]_; __1st __ (3 slots) _[[Spells/Command|Command]]_, _[[Spells/Fear|Fear]]_, _[[Spells/Gust of Wind|Gust of Wind]]_\n__Cantrips__  __(3rd)__ _[[Spells/Bullhorn|Bullhorn]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Figment|Figment]]_, _[[Spells/Ignition|Ignition]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Arcane Harmony"
    desc: "`pf2:1` (arcane,auditory) **Effect** The virtuosic lyrebird sings a subtle trill that others can use to embellish their magic. The next virtuosic lyrebird to Cast a Spell within 60 feet of the first lyrebird that used Arcane Harmony chooses one of the following two benefits, after which the Arcane Harmony ends.\n\n*   The spell gains a +2 status bonus to damage per spell rank.\n*   One target of the spell takes a –2 status penalty to saves against the spell."

  - name: "Spell Mimicry"
    desc: "  **Frequency** once per day\n\n**Requirements** A creature Casts a Spell of 3rd rank or lower since the end of the virtuosic lyrebird' s last turn, and the virtuosic lyrebird heard the incantation for the spell\n* * *\n\n**Effect** The virtuosic lyrebird learns the spell enough to mimic and cast it this turn, using as many actions as the original spell took."

  - name: "Spellsong Casting"
    desc: "  The virtuosic lyrebird's exquisite vocal control lets it cast spells purely through its song. While it must be able to vocalize to Cast a Spell, it doesn't need to gesture, removing the manipulate trait from any spell that it casts. If it Casts a Spell with the linguistic trait (usually with its Spell Mimicry), it can Cast that Spell in Common, even though the bird doesn't truly understand the language."
 
```

```encounter-table
name: Virtuosic Lyrebird
creatures:
  - 1: Virtuosic Lyrebird
```




