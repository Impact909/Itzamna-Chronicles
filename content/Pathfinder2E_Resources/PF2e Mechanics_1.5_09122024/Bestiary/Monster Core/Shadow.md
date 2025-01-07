---
title: "Shadow"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.cVBOLOREgF6IklDQ" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Shadow"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Shadow"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[undead]]
trait_03: [[unholy]]
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
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +14, __Will__ +12"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious,  bleed; __Resistances__ all damage 5 (except force, ghost touch, vitality, or spirit; double resistance vs. non-magical)"
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
    desc: "+15 (finesse, magical)\n__Damage__  2d6 + 3 void"

  - name: "Shadow Spawn"
    desc: "  When a creature's shadow is pulled free by Steal Shadow, it becomes a shadow spawn under the command of the shadow that created it. This [[Monster Core/Shadow Spawn|Shadow Spawn]] doesn't have Steal Shadow and is perpetually and incurably [[Conditions/Clumsy|Clumsy 2]].\n\nIf the creature the shadow spawn was pulled from dies, the shadow spawn becomes a full-fledged, autonomous shadow. If the creature recovers from its enfeeblement, its shadow returns to it and the shadow spawn is extinguished."

  - name: "Slink in Shadows"
    desc: "  The shadow can [[Actions/Hide|Hide]] or end its [[Actions/Sneak|Sneak]] in a creature's or object's shadow."

  - name: "Steal Shadow"
    desc: "`pf2:1` (divine) **Requirements** The shadow hit a living creature with a shadow hand Strike on its previous action\n* * *\n\n**Effect** The shadow pulls at the target's shadow, making the creature [[Conditions/Enfeebled|Enfeebled 1]]. This is cumulative with other enfeebled conditions from shadows, to a maximum of [[Conditions/Enfeebled|Enfeebled 4]]. If this increases a creature's enfeebled value to 3 or more, the target's shadow is separated from its body (see shadow spawn). The enfeebled value from Steal Shadow decreases by 1 every hour."
 
```

```encounter-table
name: Shadow
creatures:
  - 1: Shadow
```



The mysterious undead known as shadows lurk in dark places and feed on those who stray too far from the light.
