---
title: "Magnetic Gecko"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.caE1U8W2WxSEWGmK" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Magnetic Gecko"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Magnetic Gecko"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +6, Stealth: +6"
abilityMods: [2, 3, 4, -4, 2, -1]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +10, __Ref__ +7, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  electricity"
abilities_top:
  - name: ""

  - name: "Greater Electrolocation"
    desc: "  A magnetic gecko can sense minute electrical charges in living creatures, which it can use as a precise sense at a range of 20 feet. This distance increases to 100 feet against any creature that has used an electricity effect within the last minute."

  - name: "Uncanny Climber"
    desc: "  A magnetic gecko's feet allow it to climb virtually any surface, no matter how slick or sheer. If a gecko attempts an Athletics check to Climb and critically fails, it gets a failure instead."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+7 ()\n__Damage__  1d6 + 2 piercing"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+7 (electricity, finesse, reach 10 feet)\n__Damage__  2d4 electricity plus static-cling"

  - name: "Launch Metal"
    desc: "`pf2:2`  The gecko repulses the metal attached to its body in all directions, dealing 2d6 bludgeoning damage (DC 17 Reflex check save) to all creatures in a 10-foot emanation. The gecko can't use Launch Metal again for 1d4 rounds."

  - name: "Repel"
    desc: "`pf2:1`  The gecko manipulates its magnetic field to repel metal, humming audibly and gaining resistance 2 to damage from metal weapons and metal effects until the beginning of its next turn."

  - name: "Static Cling"
    desc: "  If the gecko hits Small or smaller creature with its tongue, and the target is made of metal or is wearing metallic armor, the gecko's tongue latches on to the creature. The creature must attempt a DC 17 Reflex check save or become [[Conditions/Grabbed|Grabbed]]. While the gecko is Grabbing a creature in this way, it can attempt an Athletics check check against the target's Fortitude DC to pull the creature to a space adjacent to the gecko. A creature grabbed in this way can [[Actions/Escape|Escape]] normally."
 
```

```encounter-table
name: Magnetic Gecko
creatures:
  - 1: Magnetic Gecko
```




