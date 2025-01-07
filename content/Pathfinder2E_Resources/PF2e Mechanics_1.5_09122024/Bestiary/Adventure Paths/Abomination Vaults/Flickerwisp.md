---
title: "Flickerwisp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7Iv9nfhPNJsDMYDJ" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Flickerwisp"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Flickerwisp"
level: "Creature 2"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[air]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Deception: +7, Intimidation: +5, Stealth: +8"
abilityMods: [-5, 4, 0, 0, 3, 1]
speed:  fly 25 feet
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +6, __Ref__ +10, __Will__ +7"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18; __Immunities__  magic"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Glow"
    desc: " (aura,light) 5 feet. A flickerwisp is itself naturally invisible, but glows with pale yellow light, casting bright light in the aura and making it visible."

  - name: "Innocuous"
    desc: "  A flickerwisp's appearance registers strangely in the minds of creatures who are confused. A creature with the [[Conditions/Confused|Confused]] condition never targets a flickerwisp with attacks unless the creature has been damaged by the flickerwisp's shock ability within the last 24 hours."

  - name: "Magic Immunity"
    desc: "  A flickerwisp is immune to all spells except [[Spells/Faerie Fire|Faerie Fire]], [[Spells/Gust of Wind|Gust of Wind]], [[Spells/Force Barrage|Force Barrage]], and [[Spells/Quandary|Quandary]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shock"
    desc: "+11 (magical)\n__Damage__  1d8 + 2 electricity"

  - name: "Consume Confusion"
    desc: "`pf2:1` (concentrate) **Frequency** once per round\n\n**Requirement** A creature within 15 feet of the flickerwisp is [[Conditions/Confused|Confused]]\n* * *\n\n**Effect** The flickerwisp feeds on the creature's confusion, even as its flashing body and disjointed gyrations cause existing confusion effects to persist.\n\nIt regains 1d4 healing Hit Points, and if the creature's confused condition has a limited duration, it lasts 1 additional round."

  - name: "Flicker"
    desc: "`pf2:2` (emotion,mental,visual) The flickerwisp churns and flits in the air around an adjacent creature's head, and its length flashes and sparkles in a bewildering array of distracting pulsations.\n\nThe creature must succeed at a DC 18 Will check save or become [[Conditions/Confused|Confused]] for 1 round (2 rounds on a critical failure). On a critical success, the creature is temporarily immune to for 24 hours."
 
```

```encounter-table
name: Flickerwisp
creatures:
  - 1: Flickerwisp
```



The dancing, twisting flickerwisp is a less powerful but no less malevolent type of will-o'-wisp. Like their more dangerous kin, flickerwisps prefer to haunt lonely swamps or stretches of lonely rivers or creeks, particularly near the shorelines where they can pass themselves off as nothing more than a small gathering of fireflies. A flickerwisp's body is a 3-foot-long length of hair-like fibers that flashes and pulses with ribbons and points of eerie yellow light as the creature flits through the air.

While a flickerwisp can taste fear, and finds the flavor delectable, it does not feed on this emotion. Instead, flickerwisps subsist on confusion and doubt. The sense of unease a traveler exudes when they become lost in the woods is flickerwisps' favorite repast. They can sip from this sense of disorientation without betraying their presence or harming their prey. Eventually, the flickerwisps grow too hungry and are compelled to flit closer, confuse their prey, and glut on the raw emotions. Flickerwisps do their best to swoop away before death occurs, and the most skilled of these tormentors can keep a chosen meal alive for days, sipping from confusion in small doses.
