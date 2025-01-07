---
title: "Siora Fallowglade"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cFsMBQdry6ZmYiiY" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Siora Fallowglade"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Siora Fallowglade"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[incorporeal]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Stealth: +20"
abilityMods: [-5, 5, 0, 0, 2, 4]
speed:  fly 30 feet
sourcebook: "_Pathfinder #164: Hands of the Devil_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +11, __Ref__ +18, __Will__ +15"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Light Vulnerability"
    desc: "  An object shedding magical light (such as from the [[Spells/Light|Light]] spell) is treated as magical when used to attack the shadow."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Hand"
    desc: "+18 (finesse, magical)\n__Damage__  2d10 + 6 void"

  - name: "Divine Innate Spells"
    desc: "DC 25, attack +17; __2nd __  _[[Spells/Darkness|Darkness (At Will)]]_"

  - name: "Mark for Death"
    desc: "`pf2:2`  **Requirements** Siora can see the target she intends to mark\n* * *\n\n**Effect** Siora designates a single target as her mark. She gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seek]] her target, and her spectral hand Strikes against her target gain the deadly d8 weapon trait."

  - name: "Shadow Spawn"
    desc: "  When a creature's shadow is pulled free by Steal Shadow, it becomes a [[Monster Core/Shadow Spawn|Shadow Spawn]] under the command of the shadow that created it. This shadow spawn doesn't have Steal Shadow. If the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its [[Conditions/Enfeebled|Enfeeblement]], its shadow returns to it and the shadow spawn is extinguished."

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."

  - name: "Steal Shadow"
    desc: "`pf2:1` (divine) **Requirement** The shadow hit a living creature with a shadow hand Strike on its previous action.\n* * *\n\n**Effect** The shadow pulls at the target's shadow, making the creature [[Conditions/Enfeebled|Enfeebled 2]] (or [[Conditions/Enfeebled|Enfeebled 3]] on a critical hit). This is cumulative with other enfeebled conditions from shadows, to a maximum of enfeebled 4. If this increases a creature's enfeebled value to 3 or more, the target's shadow is separated from its body. Enfeebled from Steal Shadow decreases by 1 every hour."
 
```

```encounter-table
name: Siora Fallowglade
creatures:
  - 1: Siora Fallowglade
```


Female greater shadow

Shadows that spend long amounts of time on the Shadow Plane and absorb its magic become greater shadows.

* * *

The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light. Those who parley with shadows, typically by keeping them at bay with a glowing weapon, may learn great secrets, for they are ideal spies.
