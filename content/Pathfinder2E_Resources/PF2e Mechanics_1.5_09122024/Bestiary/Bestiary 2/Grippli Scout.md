---
title: "Grippli Scout"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.DteDb1ZbSJ9BfU9U" 
tags:
  - pf2e/creature/type/grippli
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Grippli Scout"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Grippli Scout"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[grippli]]
trait_02: [[humanoid]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Grippli"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +4, Nature: +6, Stealth: +7, Survival: +6"
abilityMods: [1, 4, 2, 0, 3, -1]
speed: 25 feet,  climb 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +9, __Will__ +6"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dart|Dart]], [[Equipment/Sickle|Sickle]], [[Equipment/Leather Armor|Leather Armor]], [[Equipment/Net|Net]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Sickle"
    desc: "+9 (agile, finesse, trip)\n__Damage__  1d4 + 1 slashing"

  - name: "**Ranged** `pf2:1` Dart"
    desc: "+9 (agile, range increment 20 feet)\n__Damage__  1d4 + 1 piercing"

  - name: "Hurl Net"
    desc: "`pf2:1`  **Requirements** The grippli is wielding a net in two hands\n* * *\n\n**Effect** The grippli makes a ranged Strike (with a +9 modifier) against a Medium or smaller creature within 20 feet. On a hit, the target is [[Conditions/Off-Guard|Off-Guard]] and takes a -10-foot circumstance penalty to its Speeds. On a critical hit, the creature is [[Conditions/Restrained|Restrained]] instead. The DC to [[Actions/Escape|Escape]] the net is 16. A creature adjacent to the target can Interact with the net to remove it."

  - name: "Jungle Stride"
    desc: "  Gripplis ignore difficult terrain in forests and jungles."
 
```

```encounter-table
name: Grippli Scout
creatures:
  - 1: Grippli Scout
```



Gripplis make their homes in the treetops of tropical jungles and forests. These frog-like humanoids are uniquely adapted to their environment, with oversized eyes that give them keen vision in both light and dark and large toes that allow them to easily scale trees. Gripplis vary widely in physical appearance, with their physiologies influenced by their surrounding environment. Those who live in verdant forests, for example, typically have bright green skin and red eyes. In contrast, gripplis who live in regions of rot and decay have mottled-brown coloration, and those who dwell near lakes or streams may bear bright blue and orange stripes. Typical gripplis stand just over 2 feet tall and weigh approximately 30 pounds.

Whatever region they come from, gripplis tend to be peaceful hunter-gatherers. Due to their modest understanding of agriculture, gripplis don't maintain typical farms like other humanoids do. Rather, they cultivate mushroom patches and gather a wide array of fruits from the surrounding wilderness. While most gripplis hunt insects, some societies also capture and breed them, nurturing herds of giant dragonflies or beetles that they eventually slaughter for food. Particularly enterprising gripplis might even seek out and tame larger flying insects to use as mounts during their hunts. The rearing of such massive insects is no easy feat, however, so gripplis who manage to do so are often heralded as local heroes.

Gripplis usually construct their villages in particularly dense copses, stringing thin rope bridges between wide wooden platforms built around each trunk. They make use of broad leaves and thick branches to further obscure their villages, making them especially difficult to spot from the forest floor, and riddle the surrounding forest with labyrinthine trails that only they can navigate.

Grippli scouts typically keep watch on the outskirts of grippli settlements. More potent gripplis inhabit the settlements, be they religious leaders, powerful druids, or agile warriors that, due to their small size, focus more on finesse weapons and ranged attacks than on melee tactics.
