---
title: "Ogre Spider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IwGlVAaYKJdORrKV" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Ogre Spider"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Ogre Spider"
level: "Creature 5"

alignment: ""
size: "huge"
trait_01: [[animal]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +13"
abilityMods: [6, 4, 4, -5, 2, -4]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +13, __Will__ +9"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70"
abilities_top:
  - name: ""

  - name: "Web Sense"
    desc: "  The ogre spider has imprecise [[Bestiary Ability Glossary/Tremorsense|Tremorsense]] to detect the vibrations of creatures touching its web."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+15 ()\n__Damage__  2d8 + 8 piercing plus ogre-spider-venom"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+13 (range increment 30 feet)\n__Damage__ "

  - name: "Eerie Flexibility"
    desc: "  An ogre spider can fit through tight spaces as if it were a Large creature. While [[Actions/Squeeze|Squeezing]], it can move at its full speed."

  - name: "Ogre Spider Venom"
    desc: " (poison) **Saving Throw** DC 22 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage (1 round)\n\n**Stage 2** 1d6 poison damage, [[Conditions/Clumsy|Clumsy 1]], and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 1]], and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 4** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 2]], and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "Web Trap"
    desc: "  A creature hit by the ogre spider's web attack is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface until it [[Actions/Escape|Escapes]] (DC 22)."
 
```

```encounter-table
name: Ogre Spider
creatures:
  - 1: Ogre Spider
```



These terrifying creatures grow as large as elephants. The placement of their eyes above their wide mandibles evokes the grimacing visage of an ogre's leer. Ogres themselves find the appearance of ogre spider faces simultaneously amusing and adorable, but in most cases, ogres' attempts to keep these spiders as pets result in dead ogres and well-fed spiders.
