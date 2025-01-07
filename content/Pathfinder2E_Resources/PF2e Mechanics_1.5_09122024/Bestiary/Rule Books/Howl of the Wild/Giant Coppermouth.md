---
title: "Giant Coppermouth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vc8ZhOqQEI1SmuF6" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Giant Coppermouth"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Giant Coppermouth"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +14, Stealth: +17, Survival: +15"
abilityMods: [3, 6, 4, -4, 4, -2]
speed: 30 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +15, __Ref__ +18, __Will__ +12"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Immunities__  electricity"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  The giant coppermouth can hold its breath for 1 hour."

  - name: "Greater Electrolocation"
    desc: "  A giant coppermouth can sense minute electrical charges in living creatures, which it can use as a precise sense at a range of 20 feet. This distance increases to 100 feet against any creature that has used an electricity effect within the last minute."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+18 (electricity, finesse)\n__Damage__  2d8 + 6 piercing plus coppermouth-venom 1d4 electricity plus coppermouth-venom"

  - name: "Coppermouth Venom"
    desc: " (electricity,poison) **Saving Throw** DC 25 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison and 1d6 electricity (1 round)\n\n**Stage 2** 2d6 poison and 1d6 electricity and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 3** 2d6 poison and 2d6 electricity and [[Conditions/Clumsy|Clumsy 2]]"

  - name: "Quickening Jolt"
    desc: "`pf2:2` (electricity) The coppermouth manipulates its own nervous system by increasing its reaction time, Striding and making two Strikes against different targets during the movement. Both attacks count toward its multiple attack penalty, but the penalty doesn't increase until after it has made both attacks."

  - name: "Venomous Spit"
    desc: "`pf2:2` (electricity,poison) The coppermouth unleashes a stream of electrified venom in a 30-foot line. The venom deals 8d6 electricity damage (DC 22 Reflex check) and creatures that take damage from the venom are immediately exposed to coppermouth venom. The copper mouth can't use Venomous Spit again for 1d4 rounds."
 
```

```encounter-table
name: Giant Coppermouth
creatures:
  - 1: Giant Coppermouth
```




