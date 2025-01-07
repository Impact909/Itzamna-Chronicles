---
title: Black Powder Bomb
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - mechanical
  - trap
  - pf2eHazard

source: Pathfinder #146: Cult of Cinders
aliases: "Actor.SEmT1tD5QxkloSMS" 
level: 6
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #146: Cult of Cinders"
name: "Black Powder Bomb"
level: "Hazard 6"


trait_01: [[mechanical]]
trait_02: [[trap]]
modifier: 5
sourcebook: "_Pathfinder #146: Cult of Cinders_"
ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__ +17, __Ref__ +8, "
hp: 20
health:
  - name: ""
  - name: "HP"
    desc: "20; __Hardness__ 5; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ fire 5"
perception:
  - name: ""
  - name: "Stealth DC 15" 
    desc: "The three powder kegs aren't particularly well hidden, but they are out of sight to casual observation."
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Three bulky kegs of black powder placed at key locations in the temple are triggered to explode in unison, causing the entire structure to collapse into rubble and slide partially down the cliff face."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "No special skills are required to disable this manually activated trap. As an Interact action, a PC can sweep aside some black powder to interrupt the fuse line, but this doesn't prevent Gerhard from activating a keg via blunderbuss. A keg that is removed from its position (either by being thrown over the cliff or merely carried away) retains its explosive potential, but as long as one of the three kegs are removed they no longer have the precise placement required to trigger a collapse-an explosion at this point merely inflicts fire damage in the appropriate areas but does not particularly damage the temple structure itself.\n\nA keg's contents can be dispersed by scattering the gunpowder to the wind (most efficiently by pouring it over the cliff side) as a 2-action activity, or rendered permanently inert by pouring a gallon of water into the powder, inhibiting its explosive qualities. The kegs themselves can be destroyed with damage (note that the AC listed below for each keg takes into account the fact that Gerhard has wedged the kegs into nooks in the temple's stone flooring and walls), but note that any fire damage (including incidental fire damage from area effects like a fireball or Gerhard's blunderbuss) causes them to explode. At your option, other actions may be similarly effective at disabling this hazard."
attacks:
  - name: ""

  - name: "Destructive Explosion"
    desc: "`pf2:r` (fire) **Trigger** One of the three kegs takes any fire damage, including damage caused by a line of black powder burning up to a keg.\n* * *\n\n**Effect** The keg explodes, causing 5d6 fire damage (DC 24 Reflex check) in a 20-foot emanation; this can cause an instantaneous chain reaction if either of the other kegs are in this area (note that as positioned, all three kegs are in range to trigger a chain reaction). Fire damage in overlapping areas isn't cumulative, but if all three kegs are in their initial positions when the explosion occurs, the temple itself collapses, causing 8d6 bludgeoning damage to all creatures in the temple (DC 24 Reflex check)."

  - name: "Routine"
    desc: "If Gerhard lights the black powder fuse, it burns at a speed of 10 feet each round; when the fuse reaches a keg 6 rounds later, the black powder bomb explodes. The bomb explodes immediately if he shoots a barrel with his blunderbuss."

```

```encounter-table
name: Black Powder Bomb
creatures:
  - 1: Black Powder Bomb
```

