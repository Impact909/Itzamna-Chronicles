---
title: "Greater Shadow"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MSDAob0MAxbiZ5IQ" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Greater Shadow"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Greater Shadow"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[undead]]
trait_03: [[unholy]]
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
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +11, __Ref__ +18, __Will__ +15"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 10 (except force, ghost touch, vitality, or spirit; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Light Vulnerability"
    desc: "  Attacks against the shadow are treated as magical if made by a creature who is in magical light or with an object that is in magical light (such as from the [[Spells/Light|Light]] spell)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shadow Hand"
    desc: "+18 (finesse, magical)\n__Damage__  2d10 + 6 void"

  - name: "Divine Innate Spells"
    desc: "DC 25, attack +17; __2nd __  _[[Spells/Darkness|Darkness]]_"

  - name: "Shadow Spawn"
    desc: "  When a creature's shadow is pulled free by Steal Shadow, it becomes a shadow spawn under the command of the shadow that created it. This [[Monster Core/Shadow Spawn|Shadow Spawn]] doesn't have Steal Shadow. If the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its enfeeblement, its shadow returns to it and the shadow spawn is extinguished."

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."

  - name: "Steal Shadow"
    desc: "`pf2:1` (divine) **Requirements** The shadow hit a living creature with a shadow hand Strike on its previous action\n* * *\n\n**Effect** The shadow pulls at the target's shadow, making the creature [[Conditions/Enfeebled|Enfeebled 2]] ([[Conditions/Enfeebled|Enfeebled 3]] on a critical hit). This is cumulative with other enfeebled conditions from shadows, to a maximum of [[Conditions/Enfeebled|Enfeebled 4]]. If this increases a creature's enfeebled value to 3 or more, the target's shadow is separated from its body (see shadow spawn). The enfeebled value from [[Actions/Steal|Steal]] Shadow decreases by 1 every hour."
 
```

```encounter-table
name: Greater Shadow
creatures:
  - 1: Greater Shadow
```



Shadows that spend long amounts of time on the Netherworld and absorb its magic become greater shadows.

* * *

The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light.
