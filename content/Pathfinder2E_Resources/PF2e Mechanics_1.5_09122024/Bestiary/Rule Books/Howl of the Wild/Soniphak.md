---
title: "Soniphak"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9UwHQ4N6krkilULx" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Soniphak"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Soniphak"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[beast]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Echolocation 120 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +20, Survival: +17"
abilityMods: [7, 6, 4, -2, 4, 1]
speed: 20 feet,  fly 50 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +21, __Ref__ +21, __Will__ +15"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Immunities__  visual; __Resistances__ sonic 10"
abilities_top:
  - name: ""

  - name: "[[Actor.OEY3bg3YOjRPkyzI.Item.iJajFZP5ZYRFW9er|Sensitive Echolocation]]"
    desc: "  The soniphak can use its hearing as a precise sense with the listed range. If the soniphak takes sonic damage beyond its resistance, its senses are overloaded and all creatures are [[Conditions/Concealed|Concealed]] from it for 1 round."

  - name: "Snatch"
    desc: "  The soniphak can Fly at half Speed with a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in its claws, carrying that creature along with it."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+19 (reach 15 feet)\n__Damage__  3d8 + 9 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+19 (agile)\n__Damage__  3d6 + 9 slashing plus grab"

  - name: "**Ranged** `pf2:1` Screech"
    desc: "+19 (range 60 feet, sonic)\n__Damage__  6d6 sonic plus aftershock"

  - name: "Aftershock"
    desc: "  Whenever a soniphak hits with a screech Strike, feedback deals each creature the soniphak has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] 1d6 sonic damage."

  - name: "Disruptive Screech"
    desc: "`pf2:r`  **Trigger** A creature within 30 feet of the soniphak uses an auditory action\n* * *\n\n**Effect** The soniphak makes a screech Strike against the triggering creature. This disrupts a triggering concentrate action if the Strike is a critical hit."

  - name: "Shattering Scream"
    desc: "`pf2:2` (sonic) The soniphak can focus its screech at a stone or rock surface within 60 feet to create an explosion in a 15-foot burst from the point of impact. Creatures in the area take 5d6 piercing damage (DC 28 Reflex check save), and the area becomes difficult terrain due to fragments of loose stone."
 
```

```encounter-table
name: Soniphak
creatures:
  - 1: Soniphak
```



Dischorans are a group of predators who hunt via focused sound. Though they possess protuberances that resemble eyes, these are actually auditory sensory organs that can pick up even the slightest sound and are used to locate prey with pinpoint accuracy.

Only a few types of dischorans have been identified, but they all share unifying features: front-facing pseudo-eyes, deceptive speed, and ravenous hunger. Their sensitivity to noise combined with their ability to weaponize sound are likely the primary reasons dischorans spend most of their time alone.

* * *

Often mistaken for drakes, soniphaks glide above rocky or barren ground, picking out prey with their hearing. A hunting soniphak disables its targets with concentrated bursts of sound before snatching them up and feasting on the move. Despite being able to speak, soniphaks are no more social than other dischorans, generally responding to even the quietest attempts at communication with destructive shouting.
