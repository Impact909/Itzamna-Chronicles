---
title: "Groetan Candle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZwerrszMFxqlGvcP" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Groetan Candle"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #164: Hands of the Devil"
name: "Groetan Candle"
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

  - name: "**Melee** `pf2:1` Shock"
    desc: "+17 (cold, magical)\n__Damage__  2d8 + 4 cold"

  - name: "Feed on Fear"
    desc: "`pf2:1` (concentrate) **Requirement** An enemy is under a fear effect or [[Conditions/Dying|Dying]] within 15 feet of the will-o'-wisp.\n* * *\n\n**Effect** The will-o'wisp feeds on the creature's terror. It regains 2d4 healing Hit Points, and if it has Gone Dark, its glow reignites.\n\nA will-o'-wisp can take this action only once per round."

  - name: "Go Dark"
    desc: "`pf2:1` (concentrate) The will-o'-wisp extinguishes its glow, becoming [[Conditions/Invisible|Invisible]]. It can end this effect with another use of this action. If it uses its shock attack while invisible, the arc of electricity lets any observer determine its location, making the will-o'-wisp only [[Conditions/Hidden|Hidden]] to all observers until it moves."

  - name: "Show the Looming Moon"
    desc: "`pf2:1` (concentrate) **Requirements** The Groetan candle is [[Conditions/Invisible|Invisible]]\n* * *\n\n**Effect** The Groetan candle ends its invisibility and flashes with cold brightness. Creatures within 20 feet of the Groetan candle who can see it must succeed at a DC 24 Fortitude check save or become [[Conditions/Dazzled|Dazzled]] for 1 round (1 minute on a critical failure)."
 
```

```encounter-table
name: Groetan Candle
creatures:
  - 1: Groetan Candle
```



Malevolent balls of colored light, will-o'-wisps haunt lonely marshes and forests where they lure unsuspecting travelers into danger. Will-o'-wisps can vary the color and illumination they shed, and delight in mimicking bobbing lanterns or distant fires to draw lost or disoriented travelers off of safe trails. They can extinguish their illumination entirely to become invisible, and they enjoy doing so once their victims are wholly lost and have realized that the bobbing light in the distance isn't, in fact, leading them to safety. Even invisible, however, a will-o'-wisp rarely ventures far from its target, as it feasts upon the panic and dread felt by its victims.

Beneath its glow, a will-o'-wisp's body is a spongy ball approximately 1 foot in diameter and weighing less than 5 pounds. Although most will-o'-wisps are merely translucent, featureless orbs, gaining definition only in the shifting illumination they create, a few have dark mottling that makes them resemble a skull when viewed closely. Will-o'-wisps have no need for mundane nourishment, and in fact lack the ability to consume matter of any kind; they find all the sustenance they need in the terror of nearby creatures. For this reason, they like to work alongside undead that produce terror in their victims. Will-o'-wisps are long-lived, if not effectively immortal, and they have good memories. A cowed or defeated will-o'-wisp can be a good source of lore and information, though acquiring such cooperation from such a sinister monster is no easy feat.

Will-o'-wisps inhabit desolate swamps and forests and are generally active at twilight and after dark. They are therefore reluctant to lead victims into immediately fatal areas such as deadfalls, but instead prefer hazards where their victims suffer over a long time, such as pockets of stale or poisonous air, patches of quicksand, and dens of bigger monsters. According to will-o'-wisps, different types of fear have subtle differences in flavor. The lurking dread in the pit of the stomach that gnaws at those who slowly become aware of the fact that they're lost produces a much different taste than the sudden stark terror of imminent death in the face of a towering monster. Because of this, will-o'-wisps try to vary the ways in which they induce terror in their prey, to ensure they don't tire of certain flavors of fear.

* * *

Nearly always adherents of the grim deity Groetus, these will-o'-wisps resemble the leering skull-faced moon of their namesake. They often gather in grim choruses that work together with eerie synchronicity. Groetan candles deal cold damage rather than electricity.
