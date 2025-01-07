---
title: "Web Lurker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.XNKzvx7yK3suuiBX" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Web Lurker"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Web Lurker"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[evil]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Aklo; spider speak"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +9, Crafting: +8, Stealth: +11"
abilityMods: [4, 4, 3, 1, 3, -1]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +10, __Ref__ +11, __Will__ +8"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet (Creatures Touching its Web)]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Spider Speak"
    desc: "  The web lurker can speak with spiders, with the same effects and limitations as [[Spells/Speak with Animals|Speak with Animals]]."

abilities_mid:
  - name: ""
  - name: "Spring upon Prey"
    desc: "`pf2:r`  **Trigger** A creature touches the web lurker's web while the web lurker is on it.\n\n**Requirements** Initiative has not yet been rolled.\n* * *\n\n**Effect** The web lurker automatically notices the creature and Strides or Climbs before rolling initiative."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+11 (poison)\n__Damage__  1d8 + 6 piercing plus web-lurker-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile)\n__Damage__  1d8 + 6 slashing"

  - name: "**Melee** `pf2:1` Web"
    desc: "+11 ()\n__Damage__ "

  - name: "Web Lurker Venom"
    desc: " (poison) **Saving Throw** DC 19 Fortitude check\n* * *\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 1d6 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 1d6 poison damage, off-guard, and [[Conditions/Slowed|Slowed 1]] (1 round)"

  - name: "Web Trap"
    desc: "  A creature hit by the web lurker's web attack is immobilized and stuck to the nearest surface until it succeeds at DC 20 Acrobatics check check to [[Actions/Escape|Escape]]."
 
```

```encounter-table
name: Web Lurker
creatures:
  - 1: Web Lurker
```



Web lurkers, known also as ettercaps, are ugly monsters that not only dwell within the lairs of spiders and swarms, but actively cultivate and shepherd such vermin.
