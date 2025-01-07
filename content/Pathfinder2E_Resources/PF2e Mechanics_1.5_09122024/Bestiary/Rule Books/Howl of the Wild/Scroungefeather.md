---
title: "Scroungefeather"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.347pfy1fJXLhONvz" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Scroungefeather"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Scroungefeather"
level: "Creature 5"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Stealth: +12, Thievery: +14"
abilityMods: [3, 5, 2, -4, 1, 2]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +14, __Ref__ +16, __Will__ +8"
hp: 76
health:
  - name: ""
  - name: HP
    desc: "76"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+12 (finesse)\n__Damage__  2d8 + 3 piercing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+12 (agile, finesse)\n__Damage__  2d6 + 3 slashing"

  - name: "Junk Nest"
    desc: "  The scroungefeather's nest of sharp metallic junk covers a 15-foot-by-15-foot area. The area is difficult terrain and hazardous terrain to any non-scroungefeather creatures. A creature that moves on the ground through the nest takes 3 piercing damage for each square of the area it moves into. Scroungefeathers can [[Actions/Take Cover|Take Cover]] at any point in the nest."

  - name: "Tossed Scraps"
    desc: "`pf2:1`  **Requirements** The scroungefeather has Grabbed Debris\n* * *\n\n**Effect** The scroungefeather flings the debris at a target within 20 feet, making an attack roll with a +12 modifier. On a success, the target takes 2d10+5 bludgeoning damage."

  - name: "Grab Debris"
    desc: "`pf2:1`  **Requirements** The scroungefeather is in its nest or another environment rich with debris\n* * *\n\n**Effect** The scroungefeather uses an Interact action to grab an item with its beak, selected randomly; roll 1d4 to determine the type of debris. The scroungefeather gains access to the listed abilities until it uses Tossed Scraps to discard the debris or until it Releases the debris. The scroungefeather can't use its beak attack while it is using its beak to Grab Debris.\n\n  \n\n| d4 | Item | Effect |\n| --- | --- | --- |\n| 1 | Armor scrap | The scroungefeather gains a +2 circumstance bonus to its AC. |\n| 2 | Shattered blade | The scroungefeather gains a broken blade melee Strike with a +12 attack modifier that deals 2d10+6 slashing damage. |\n| 3 | Unexploded bomb | When the scroungefeather throws this with Tossed Scraps, all the damage is fire damage, and the bomb also deals 3 fire splash damage. |\n| 4 | Faulty wand | The scroungefeather gains a magic bolt ranged Strike witha +14 attack modifier that deals 2d6+6 force damage. |"
 
```

```encounter-table
name: Scroungefeather
creatures:
  - 1: Scroungefeather
```




