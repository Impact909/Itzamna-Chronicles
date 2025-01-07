---
title: "Dragon Turtle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5JAcHUS5AN79jms0" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Dragon Turtle"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Dragon Turtle"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[dragon]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Draconic, Thalassic"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Diplomacy: +18, Intimidation: +18, Stealth: +13, Survival: +17"
abilityMods: [6, 0, 4, 1, 3, 1]
speed: 20 feet,  swim 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +19, __Ref__ +15, __Will__ +17"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Shell Block"
    desc: "`pf2:r`  **Trigger** A creature adjacent to the dragon turtle targets it with a melee attack.\n* * *\n\n**Effect** The dragon turtle rolls its shell toward the triggering creature, gaining a +2 circumstance bonus to its AC against the triggering attack."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (reach 10 feet)\n__Damage__  2d12 + 9 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile)\n__Damage__  2d8 + 9 slashing"

  - name: "Capsize"
    desc: "`pf2:1` (attack) The dragon turtle tries to capsize an adjacent aquatic vessel of their size or smaller. The dragon turtle must succeed at a DC 30 Athletics check check (reduce the DC by 5 for each size smaller than the dragon turtle) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Conjure Storm"
    desc: "`pf2:1` (air,aura,primal,water) The dragon turtle summons a mighty storm to rage around themself. The area in a 30-foot emanation around the turtle becomes difficult terrain for all other flying and swimming creatures. The dragon turtle can end the storm by taking this action again."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon turtle makes two Claw Strikes and one Jaws Strike in any order."

  - name: "Tsunami"
    desc: "`pf2:2` (primal,water) The dragon turtle unleashes their destructive prowess by creating a massive growing wave that deals 7d6 bludgeoning damage in a 60-foot cone (DC 27 Reflex check save). The wave's damage increases by 10 for creatures who are more than 30 feet away. A creature that fails its save is knocked [[Conditions/Prone|Prone]].\n\nThe dragon turtle can't use Tsunami again for 1d4 rounds."
 
```

```encounter-table
name: Dragon Turtle
creatures:
  - 1: Dragon Turtle
```



These immense aquatic dragons have rocky shells similar to those of tortoises and flippers powerful enough to overturn hardy vessels. The fearsome creatures enjoy being considered as dangerous as storms or natural disasters by seafaring folk. Despite their reputation, many dragon turtles delight in secretly observing seafaring cities grow and evolve throughout the ages. They have even been known to protect such cities from pirates, invading armies, or even other dangerous sea creatures. According to rumor, these turtles have even hired adventurers to handle more inland threats. Such cities will often offer tribute to the great turtle if they discover its intervention. While a dragon turtle hoards the treasures of the ships it sinks, they consider the bounty freely offered from their protected city most precious.

While many dragon turtles are already large enough to inspire awe, some can grow substantially larger. Those massive, ancient dragon turtles are somnolent, resembling rocky islands from a distance; their prodigious hoards can be a source of ancient sea lore. Legends persist of truly immense dragon turtles who spend centuries drifting on the surface of the ocean, far from established shipping lanes or charted waters, with shells that serve as islands capable of supporting entire ecosystems and even, some claim, small settlements whose inhabitants know nothing of land that doesn't drift across the sea.
