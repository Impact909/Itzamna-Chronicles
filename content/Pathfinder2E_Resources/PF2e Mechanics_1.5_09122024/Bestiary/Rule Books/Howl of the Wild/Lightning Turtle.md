---
title: "Lightning Turtle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.rReOaBnyUQyzUBUS" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/12
  - remaster
statblock: inline
name: "Lightning Turtle"
level: 12
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Lightning Turtle"
level: "Creature 12"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +25"
abilityMods: [5, 1, 7, -4, 4, 1]
speed: 15 feet,  swim 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +25, __Ref__ +19, __Will__ +22"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  electricity"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  The lightning turtle can hold its breath for 30 minutes."

  - name: "Greater Electrolocation"
    desc: "  A lightning turtle can sense minute electrical charges in living creatures, which it can use as a precise sense at a range of 20 feet. This distance increases to 100 feet against any creature that has used an electricity effect within the last minute."

abilities_mid:
  - name: ""
  - name: "Shell Shock"
    desc: "`pf2:r` (electricity,nonlethal) **Trigger** A lightning turtle is hit by a melee or an unarmed attack\n* * *\n\n**Effect** The lightning turtle releases some of its stored electrical power, inflicting 7d6 electricity damage to the creature attacking it."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (electricity)\n__Damage__  2d12 + 5 piercing 2d6 electricity"

  - name: "**Ranged** `pf2:1` Electrical Burst"
    desc: "+22 (electricity, range 60 feet)\n__Damage__  4d10 electricity"

  - name: "Healing Pulse"
    desc: "`pf2:3` (electricity,healing,primal) The lightning turtle releases a pulse of low-intensity electricity from its body to promote healing. This restores 5d8 healing Hit Points to the turtle and each living ally within 10 feet, including creatures normally immune to electricity. The turtle can't use Healing Pulse again for 1 minute and is temporarily immune to the Healing Pulse of any lightning turtle for 1 minute."

  - name: "Sparking Shell"
    desc: "`pf2:1`  The lightning turtle withdraws into its shell. This increases its AC to 36, but it can't act except to use Shell Shock or reemerge as a single action. While in its shell, the turtle's Shell Shock deals another 4d6 damage and loses the nonlethal trait."
 
```

```encounter-table
name: Lightning Turtle
creatures:
  - 1: Lightning Turtle
```




