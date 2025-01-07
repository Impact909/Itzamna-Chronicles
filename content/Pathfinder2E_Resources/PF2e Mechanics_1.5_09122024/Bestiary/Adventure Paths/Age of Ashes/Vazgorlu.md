---
title: "Vazgorlu"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kfhAmhJTp7m5uXPE" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/astral
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Vazgorlu"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #150: Broken Promises"
name: "Vazgorlu"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[astral]]
trait_03: [[evil]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision"
languages: "Aklo, Chthonian, Daemonic, Diabolic, Empyrean, Protean, Requian, Utopian"
skills:
  - name: "Skills"
    desc: "Arcana: +38, Deception: +38, Stealth: +34, Thievery: +32, Portal Lore: +41"
abilityMods: [6, 7, 6, 7, 8, 5]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder #150: Broken Promises_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +30, __Ref__ +33, __Will__ +36"
hp: 380
health:
  - name: ""
  - name: HP
    desc: "380; __Immunities__  acid,  paralyzed,  sleep; __Resistances__ cold 15, physical 10 (except cold iron)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Hostile Juxtaposition"
    desc: "`pf2:r` (arcane,teleportation) **Trigger** A creature targets the vazgorlu with a Strike\n* * *\n\n**Effect** The vazgorlu chooses a different creature within 60 feet and attempts to swap places with that creature using [[Spells/Translocate|Translocate]] in the instant before the Strike. The target must attempt a DC 39 Will check save.\n* * *\n\n**Critical Success** The target resists the teleportation, and the vazgorlu can't use Hostile Juxtaposition for 1d4 rounds.\n\n**Success** The target resists the teleportation.\n\n**Failure** The target and the vazgorlu instantly swap places, and the triggering Strike is resolved against the target instead.\n\n**Critical Failure** As failure, but the target is transported to the vazgorlu's demiplane after resolving the triggering Strike against it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+38 (reach 10 feet)\n__Damage__  4d10 + 8 piercing 3d10 acid"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+38 (range increment 60 feet)\n__Damage__  6d6 + 8 acid plus dimensional-tether"

  - name: "Arcane Innate Spells"
    desc: "DC 35, attack +27; __7th __  _[[Spells/Interplanar Teleport|Plane Shift (To and From the Vazgorlu's Demiplane Only)]]_, _[[Spells/Teleport|Teleport (x3)]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(4th)__ _[[Spells/Air Walk|Air Walk]]_"

  - name: "Demiplane Lair"
    desc: "  A vazgorlu maintains a 30-foot-diameter demiplane in the Astral Plane. Gravity in this demiplane pulls out from the center, so that creatures can walk upon the inner surface. A vazgorlu's demiplane lair lacks a built-in point of exit, and if the vazgorlu fails to visit the demiplane during a 24-hour period, the demiplane collapses- all objects and creatures within are then returned to their original locations in the multiverse before they entered the demiplane. A vazgorlu can create a replacement demiplane lair with 24 hours of concentration."

  - name: "Dimensional Tether"
    desc: "  A creature hit by a vazgorlu's web Strike is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface until it Escapes (DC 42). As long as it remains immobilized by the web, the web attempts to counteract any effect that would move the webbed creature to another plane, with a counteract rank of 10 and using the vazgorlu's Arcana skill to attempt the counteract check."

  - name: "Redirect Portal"
    desc: "  A vazgorlu can spend 10 minutes in contact with a magical portal to redirect it, causing the portal to instead lead to its demiplane lair. To do so, the vazgorlu must succeed at a Portal Lore check (the DC is either equal to the caster's spell DC for a portal created by a spell, or set by the portal's level; if the portal in question has no level listed, assume it's a 20th-level portal)."
 
```

```encounter-table
name: Vazgorlu
creatures:
  - 1: Vazgorlu
```



The arthropod monstrosity known as a vazgorlu makes its home on the Astral Plane or inside of a stable portal, ambushing creatures that travel there using dimensional magic.
