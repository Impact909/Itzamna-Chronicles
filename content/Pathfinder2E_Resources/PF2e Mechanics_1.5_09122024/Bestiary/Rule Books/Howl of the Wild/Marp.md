---
title: "Marp"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YwJF1ZkBovG6hkEw" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Marp"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Marp"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[beast]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Fey"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Athletics: +10, Deception: +13, Thievery: +12"
abilityMods: [4, 4, 2, -2, 2, 5]
speed: 25 feet,  climb 15 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +10, __Ref__ +14, __Will__ +10"
hp: 48
health:
  - name: ""
  - name: HP
    desc: "48"
abilities_top:
  - name: ""

  - name: "Goldsense"
    desc: "  Marps can sense any accumulation of gold within range. They also can precisely measure the purity of gold by touch."

abilities_mid:
  - name: ""
  - name: "Panicked Withdrawal"
    desc: "`pf2:r`  **Trigger** The marp takes damage from a melee Strike\n* * *\n\n**Effect** The marp drops any items held in their hands, then Climbs or Strides up to 15 feet."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 ()\n__Damage__  2d6 + 6 piercing"

  - name: "Gold?"
    desc: "`pf2:1` (auditory,emotion,linguistic,mental) The marp asks for gold from all creatures in a 30-foot emanation. Each target must attempt a DC 22 Will check save or retrieve and drop gold valuables as a free action.\n* * *\n\n**Critical Success** The target can refuse the request, though they can also choose to willingly hand over any amount of gold. If they do so, they gain a +1 status bonus to the next saving throw they attempt within 1 minute, and they're temporarily immune to Scampering Theft for 1 minute.\n\n**Success** The target can refuse the request.\n\n**Failure** The target must drop coins, gold jewelry, or other objects worth 20 gp.\n\n**Critical Failure** As failure, but 40 gp."

  - name: "Scampering Theft"
    desc: "`pf2:2` (manipulate,move) The marp runs and attempts to snatch a purse, pendant, or other such object. The marp Strides up to their Speed, and they can move through enemy spaces during this movement. They then attempt to steal valuables from the target, who must attempt a DC 22 Reflex check save.\n\n**Success** The marp fails to steal anything from the target.\n\n**Failure** The marp steals one object from the target's possession that is made of or contains gold. They can't steal objects held by or permanently attached to the creature. If the object contains lead, the marp drops it at the target's feet. After stealing the object (or dropping it), the marp then Strides up to their Speed."
 
```

```encounter-table
name: Marp
creatures:
  - 1: Marp
```




