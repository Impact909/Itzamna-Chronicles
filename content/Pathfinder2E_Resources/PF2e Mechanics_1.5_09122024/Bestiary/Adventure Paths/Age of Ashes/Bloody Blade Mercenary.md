---
title: "Bloody Blade Mercenary"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NDSqYj58HEmC9UF2" 
tags:
  - pf2e/creature/type/dromaar
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Bloody Blade Mercenary"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #145: Hellknight Hill"
name: "Bloody Blade Mercenary"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[dromaar]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
trait_05: [[orc]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; "
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Athletics: +7, Intimidation: +2, Nature: +4, Stealth: +6, Survival: +4, Thievery: +6"
abilityMods: [4, 3, 1, 0, 1, -1]
speed: 25 feet
sourcebook: "_Pathfinder #145: Hellknight Hill_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +6, __Ref__ +9, __Will__ +4"
hp: 19
health:
  - name: ""
  - name: HP
    desc: "19"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|Longsword]], [[Equipment/Shortbow|Shortbow]], [[Equipment/Studded Leather Armor|Studded Leather Armor]], 20x [[Equipment/Arrows|Arrows]], 15x [[Equipment/Silver Pieces|Silver Pieces]]"
abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+9 (versatile p)\n__Damage__  1d8 + 4 slashing"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+8 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 piercing"

  - name: "Hunt Prey"
    desc: "`pf2:1`  The bloody blade mercenary designates a single creature as their prey and focuses their attacks against that creature. The mercenary must be able to see or hear the prey, or must be tracking the prey during exploration.\n\nThe mercenary gains a +2 circumstance bonus to Perception checks to [[Actions/Seek|Seeks]] their prey and a +2 circumstance bonus to Survival checks when they [[Actions/Track|Tracks]] their prey. The mercenary also ignores the penalty for making ranged attacks within their second range increment against the prey they are hunting.\n\nThe mercenary can have only one creature designated as their prey at a time. If they use Hunt Prey against a creature when they already have a creature designated, the prior creature loses the designation and the new prey gains the designation. This designation lasts until their next daily preparations."

  - name: "Hunted Shot"
    desc: "`pf2:1`  **Frequency** once per round\n\n**Requirement** The bloody blade mercenary is wielding a ranged weapon with reload 0\n* * *\n\nThe bloody blade mercenary takes two quick shots against the one they hunt. They make two Strikes against their prey with the required weapon. If both hit the same creature, combine their damage for the purpose of resistances and weaknesses. Apply the mercenary's multiple attack penalty to each Strike normally."

  - name: "Precision"
    desc: "  The first time the mercenary hits their hunted prey in a round, they deal 1d8 additional precision damage."
 
```

```encounter-table
name: Bloody Blade Mercenary
creatures:
  - 1: Bloody Blade Mercenary
```


Human (half-orc) ranger 1


