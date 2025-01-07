---
title: "Gloaming Will-o'-Wisp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QgOdn2eDGT0YiOSi" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/air
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Gloaming Will-o&#x27;-Wisp"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Gloaming Will-o'-Wisp"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Small"
trait_01: [[aberration]]
trait_02: [[air]]
trait_03: [[chaotic]]
trait_04: [[evil]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Greater Darkvision"
languages: "Aklo, Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +29, Deception: +23, Intimidation: +23, Stealth: +27"
abilityMods: [-5, 8, 2, 2, 6, 4]
speed:  fly 50 feet
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +19, __Ref__ +27, __Will__ +23"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110; __Immunities__  magic"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Hypnotic Glow"
    desc: " (aura,light,mental) 30 feet. Similar to other will-o'-wisps, a gloaming will-o'-wisp is naturally invisible, but glows with a faint colored light. They cast dim light in the aura, which makes them visible. In addition, any non-aberration creature that ends their turn in the aura and can see the gloaming will-o'-wisp is distracted by the gloaming will-o'-wisp's glow and must attempt a DC 31 Will check save. On a failure, the creature is [[Conditions/Stupefied|Stupefied 1]] for 1 round and takes 3d6 mental damage."

  - name: "Magic Immunity"
    desc: "  A will-o'-wisp is immune to all spells except _faerie fire_, _glitterdust_, _magic missile_, and _maze_."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shock"
    desc: "+27 (electricity, magical)\n__Damage__  4d8 + 13 electricity"

  - name: "Feed on Fear"
    desc: "`pf2:1` (concentrate) **Requirement** An enemy is under a fear effect or dying within 15 feet of the will-o'-wisp\n* * *\n\n**Effect** The will-o'-wisp feeds on the creature's terror. They regains 4d8 Hit Points, and if they've Gone Dark, their glow reignites. A will-o'-wisp can take this action only once per round."

  - name: "Go Dark"
    desc: "`pf2:1` (concentrate) The gloaming will-o'-wisp extinguishes their hypnotic glow, becoming [[Conditions/Invisible|Invisible]]. They can end this effect with another use of this action. If they use their shock attack while invisible, the arc of electricity lets any observer determine their location, making the will-o'-wisp only [[Conditions/Hidden|Hidden]] to observers until they move."
 
```

```encounter-table
name: Gloaming Will-o'-Wisp
creatures:
  - 1: Gloaming Will-o'-Wisp
```




