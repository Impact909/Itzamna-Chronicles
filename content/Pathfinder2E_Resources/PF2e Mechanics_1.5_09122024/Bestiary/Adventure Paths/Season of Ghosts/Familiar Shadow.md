---
title: "Familiar Shadow"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.P0qPNJFkCcw0Tx0Z" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Familiar Shadow"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #198: No Breath to Cry"
name: "Familiar Shadow"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Stealth: +14"
abilityMods: [-5, 4, 0, -2, 2, 3]
speed:  fly 30 feet
sourcebook: "_Pathfinder #198: No Breath to Cry_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +14, __Will__ +12"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 5 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Light Vulnerability"
    desc: "  An object shedding magical light (such as from the [[Spells/Light|Light]] spell) is treated as magical when used to attack the shadow."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Hand"
    desc: "+15 (finesse, magical)\n__Damage__  2d6 + 3 void"

  - name: "Infest Shadow"
    desc: "  When a familiar shadow pulls free the shadow of the PC that they duplicate, it twists and writhes for a moment before it immediately slithers back around the character. The infested shadow seems to writhe and twist on its own, as if willfully ignoring the actions of the character to whom it's attached. The infested shadow has a habit of making distracting and embarrassing motions, and imparts a –2 status penalty to its attached PC's Deception, Diplomacy, and Stealth checks. If the PC is in a situation where they aren't casting a shadow (such as when they're in complete darkness or [[Conditions/Invisible|Invisible]]), these penalties are suppressed, but return as soon as their infested shadow does. If a PC with an infested shadow gains the dying condition, the shadow breaks free and becomes a shadow spawn (which functions the same as a shadow spawn created by a typical shadow). This shadow spawn won't attack the creature it spawned from, but any other targets are fair game. If the dying character recovers, their shadow spawn immediately dies and their shadow returns to normal—otherwise the only way to be rid of this strange curse is through the use of a spell like remove curse."

  - name: "Shadow Spawn"
    desc: "  When a creature's shadow is pulled free by Steal Shadow, it becomes a [[Monster Core/Shadow Spawn|Shadow Spawn]] under the command of the shadow that created it. This shadow spawn doesn't have Steal Shadow and is perpetually and incurably [[Conditions/Clumsy|Clumsy 2]]. If the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its [[Conditions/Enfeebled|Enfeeblement]], its shadow returns to it and the shadow spawn is extinguished."

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."

  - name: "Steal Shadow"
    desc: "`pf2:1` (divine) **Requirements** The shadow hit a living creature with a shadow hand Strike on its previous action.\n\nThis ability only functions against the PC who the shadow appears to duplicate.\n* * *\n\n**Effect** The shadow pulls at the target's shadow, making the creature [[Conditions/Enfeebled|Enfeebled 1]]. This is cumulative with other enfeebled conditions from shadows, to a maximum of enfeebled 4. If this increases a creature's enfeebled value to 3 or more, the target's shadow is separated from its body. Enfeebled from Steal Shadow decreases by 1 every hour."
 
```

```encounter-table
name: Familiar Shadow
creatures:
  - 1: Familiar Shadow
```



The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light. Those who parley with shadows, typically by keeping them at bay with a glowing weapon, may learn great secrets, for they are ideal spies.
