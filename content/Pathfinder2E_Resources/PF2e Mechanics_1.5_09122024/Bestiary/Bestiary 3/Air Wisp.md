---
title: "Air Wisp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.IbaNiZz1xMH9SjyW" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/elemental
  - pf2eMonster
  - pf2e/creature/level/0
statblock: inline
name: "Air Wisp"
level: 0
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Air Wisp"
level: "Creature 0"

alignment: ""
size: "tiny"
trait_01: [[air]]
trait_02: [[elemental]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Sussuran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Stealth: +7, Plane of Air Lore: +4"
abilityMods: [0, 3, 1, 0, 2, 0]
speed:  fly 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +3, __Ref__ +9, __Will__ +4"
hp: 10
health:
  - name: ""
  - name: HP
    desc: "10; __Immunities__  bleed,  paralyzed,  poison,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Accord Essence"
    desc: "`pf2:r` (air) **Trigger** An ally within 30 feet that benefited from the wisp's resonance in the last hour is targeted by an attack\n* * *\n\n**Effect** The wisp detonates itself in a small elemental explosion that gives temporary Hit Points equal to half the wisp's current Hit Points to allies within 30 feet that have benefited from the wisp's resonance in the last hour. These temporary Hit Points last 1 hour.\n\nA wisp that uses this reaction is permanently destroyed, and it can be restored only by a [[Spells/Wish|Wish]] spell or similarly powerful effect. If an ability would prevent the wisp's destruction (for instance, if the wisp is summoned and would merely be dismissed), Accord Essence has no effect."

  - name: "Resonance"
    desc: " (air,aura) 30 feet. All wisps vibrate at a frequency attuned to their element, resonating with and empowering all creatures and effects sharing that trait.\n\nA creature in the area gains a +1 status bonus to attack and damage rolls for effects with the air trait; a creature with the elemental and air traits gains this bonus to all attack and damage rolls.\n\n[[Bestiary Effects/Effect_ Resonance|Effect: Resonance]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+7 (reach 10 feet)\n__Damage__  1d4 bludgeoning"

  - name: "In Concert"
    desc: "  When an air wisp rolls a critical failure on a check to [[Actions/Aid|Aid]], they get a failure instead, and when they roll a success, they get a critical success instead."
 
```

```encounter-table
name: Air Wisp
creatures:
  - 1: Air Wisp
```



Air wisps are floating spheres of cloud and storm, perpetually humming a light, whispery tone. They're playful and capricious with great curiosity toward strangers.

* * *

Wisps are tiny elemental beings that emerged during the creation of the Elemental Planes. The first wisps roamed the Inner Sphere in shifting symphonies that traded members with their every meeting. These symphonies of free wisps created music out of their combined resonances, but when the evil Elemental Lords realized the value of the wisps' resonance, they captured whole symphonies for use as servants.

Wisps attune to each other and to those they surround themselves with. This attunement makes them naturally supportive allies. Free wisps still roam the Inner Sphere and the Material Plane, but they're usually shy and hide themselves from strangers. However, they happily offer their service to those who show them kindness. They especially find themselves drawn to spellcasters who practice elemental magic; these wisps usually watch from afar but sometimes approach those who seem safe to become familiars or comrades.

Free wisps who find one another become close almost immediately. They get especially excited when they find wisps of elements other than their own, showing none of the animosity some elementals exhibit toward other types. Instead, they join in an excited dance, emitting resonances that faintly echo the symphonies of ancient days.
