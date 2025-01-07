---
title: "Dune Candle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8YH77aQ76DSdzzvb" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Dune Candle"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Dune Candle"
level: "Creature 6"

alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[air]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Deception: +12, Intimidation: +12, Stealth: +16"
abilityMods: [-5, 6, 0, 2, 4, 2]
speed:  fly 50 feet
sourcebook: "_Pathfinder #164: Hands of the Devil_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +10, __Ref__ +16, __Will__ +14"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Immunities__  magic"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Glow"
    desc: " (aura,light) 20 feet. A will-o'-wisp is itself naturally invisible, but glows with a colored light, casting bright light in the aura and making it visible."

  - name: "Magic Immunity"
    desc: "  A will-o'-wisp is immune to all spells except [[Spells/Faerie Fire|Faerie Fire]], [[Spells/Revealing Light|Revealing Light]], [[Spells/Force Barrage|Force Barrage]], and [[Spells/Quandary|Quandary]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Flare"
    desc: "+17 (fire, magical)\n__Damage__  2d4 + 4 fire plus light-the-living-wick"

  - name: "Heat Mirage"
    desc: "`pf2:1` (concentrate) The dune candle extinguishes its glow, becoming [[Conditions/Invisible|Invisible]]. It can end this effect with another use of this action. Its body reflects creatures on fire (but not other fires) while it's invisible.\n\nAs a result, when any creature within 20 feet of the dune candle is taking [[Conditions/Persistent Damage|Persistent Fire Damage]], the dune candle is [[Conditions/Hidden|Hidden]] to observers rather than [[Conditions/Undetected|Undetected]]."

  - name: "Light the Living Wick"
    desc: " (arcane) A creature damaged by a dune candle's flare Strike must succeed at a DC 24 Fortitude check save or catch on fire, taking 1d4 persistent fire damage.\n\nIf the creature is already taking persistent fire damage, a failed save increases the persistent fire damage by 1d4."
 
```

```encounter-table
name: Dune Candle
creatures:
  - 1: Dune Candle
```



Malevolent balls of colored light, will-o'-wisps haunt lonely marshes and forests where they lure unsuspecting travelers into danger. Will-o'-wisps can vary the color and illumination they shed, and delight in mimicking bobbing lanterns or distant fires to draw lost or disoriented travelers off of safe trails. They can extinguish their illumination entirely to become invisible, and they enjoy doing so once their victims are wholly lost and have realized that the bobbing light in the distance isn't, in fact, leading them to safety. Even invisible, however, a will-o'-wisp rarely ventures far from its target, as it feasts upon the panic and dread felt by its victims.

Beneath its glow, a will-o'-wisp's body is a spongy ball approximately 1 foot in diameter and weighing less than 5 pounds. Although most will-o'-wisps are merely translucent, featureless orbs, gaining definition only in the shifting illumination they create, a few have dark mottling that makes them resemble a skull when viewed closely. Will-o'-wisps have no need for mundane nourishment, and in fact lack the ability to consume matter of any kind; they find all the sustenance they need in the terror of nearby creatures. For this reason, they like to work alongside undead that produce terror in their victims. Will-o'-wisps are long-lived, if not effectively immortal, and they have good memories. A cowed or defeated will-o'-wisp can be a good source of lore and information, though acquiring such cooperation from such a sinister monster is no easy feat.

Will-o'-wisps inhabit desolate swamps and forests and are generally active at twilight and after dark. They are therefore reluctant to lead victims into immediately fatal areas such as deadfalls, but instead prefer hazards where their victims suffer over a long time, such as pockets of stale or poisonous air, patches of quicksand, and dens of bigger monsters. According to will-o'-wisps, different types of fear have subtle differences in flavor. The lurking dread in the pit of the stomach that gnaws at those who slowly become aware of the fact that they're lost produces a much different taste than the sudden stark terror of imminent death in the face of a towering monster. Because of this, will-o'-wisps try to vary the ways in which they induce terror in their prey, to ensure they don't tire of certain flavors of fear.

* * *

These desert-based will-o'-wisps deal fire damage rather than electricity and delight in setting their victims aflame, relishing the resulting screams that echo across the landscape. They can quench their glow like other will-o'-wisps, but the nearer they remain to their burning victims, the more obvious their heat shimmer appears in the air.
