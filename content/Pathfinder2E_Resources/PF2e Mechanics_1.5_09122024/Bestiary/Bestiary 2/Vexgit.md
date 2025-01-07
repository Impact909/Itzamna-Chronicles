---
title: "Vexgit"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BcE4eM8BoWf9DxOu" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2e/creature/type/gremlin
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Vexgit"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Vexgit"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[fey]]
trait_03: [[gremlin]]
trait_04: [[lawful]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +6, Crafting: +6, Nature: +6, Stealth: +5, Thievery: +7"
abilityMods: [1, 4, 2, 1, 1, 0]
speed: 20 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +5, __Ref__ +9, __Will__ +6"
hp: 24
health:
  - name: ""
  - name: HP
    desc: "24; __Weaknesses__ cold iron 2"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Maul|Maul]]"
  - name: "Clacking Exoskeleton"
    desc: "  A creature that can hear gains a +2 circumstance bonus to its Perception DC against a vexgit's attempts to [[Actions/Sneak|Sneak]]."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maul"
    desc: "+8 (shove)\n__Damage__  1d12 + 1 bludgeoning plus destructive-smash"

  - name: "**Melee** `pf2:1` Bite"
    desc: "+11 (agile, finesse)\n__Damage__  1d6 + 1 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 17, attack +7; __1st __  _[[Spells/Alarm|Alarm]]_\n__Cantrips__  __(1st)__ _[[Spells/Prestidigitation|Prestidigitation]]_"

  - name: "Destructive Smash"
    desc: "  A vexgit's maul Strike against an object deals ignores up to 5 of the object's Hardness."

  - name: "Gremlin Snare"
    desc: "`pf2:3` (primal) **Frequency** once per hour\n* * *\n\n**Effect** The vexgit creates a snare of their level or lower that normally takes 1 minute to craft at no cost. A single vexgit can maintain one gremlin snare at a time-if they create a new snare, the previously created one vanishes."

  - name: "Rusting Grasp"
    desc: "`pf2:2` (primal) **Frequency** once per hour\n* * *\n\n**Effect** The vexgit makes a +9 spell attack against a creature or unattended object. If they succeed, the vexgit deals 1d6 damage (doubled on a critical hit) to a metal item the target is wearing or holding, ignoring its Hardness. If they hit an unattended metal item, the item takes this damage automatically.\n\nIf a creature uses [[Bestiary Ability Glossary/Shield Block|Shield Block]] with a metal shield against this attack, the shield is automatically [[Conditions/Broken|Broken]], but no other item is rusted on that attack."

  - name: "Speedy Sabotage"
    desc: "  When a vexgit succeeds or critically succeeds at a check to [[Actions/Disable a Device|Disable a Device]], they gain an additional success toward disabling a complex device."
 
```

```encounter-table
name: Vexgit
creatures:
  - 1: Vexgit
```



These gremlins are covered head-to-toe by a crustacean-like exoskeleton that clacks and rattles whenever a vexgit moves. They delight in sabotaging the works of other creatures, often turning these works into dangerous traps. An individual vexgit might jam a door lock, loosen the wheels on a carriage, or remove nails from a boat hull. Buildings infested by vexgits become filled with traps like portcullises descending suddenly, water pipes exploding violently, and clock towers disgorging an avalanches of gears.

Aware of their own physical weakness, vexgits carry hammers and other tools to leverage pieces apart or smash whatever they're unable to disassemble. Indeed, a hammer sized for a human becomes a maul in the tiny hands of a vexgit.

Vexgit infestations range from one to a score. Larger groups are often led by a more powerful vexgit with additional skill in thievery or primal magic. Trained giant rats, vipers, and rat swarms are common in vexgit lairs.
