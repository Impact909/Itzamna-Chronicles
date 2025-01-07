---
title: "Shikwashim Mercenary"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZZ7hUMgEEMtq6sEn" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lizardfolk
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Shikwashim Mercenary"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #159: All or Nothing"
name: "Shikwashim Mercenary"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[lizardfolk]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; "
languages: "Common, Draconic, Iruxi"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +19, Stealth: +19, Survival: +17"
abilityMods: [4, 4, 3, 1, 2, 0]
speed: 25 feet,  swim 15 feet
sourcebook: "_Pathfinder #159: All or Nothing_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +20, __Ref__ +19, __Will__ +15"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/Javelin|Javelin]], [[Equipment/Scimitar|+1 Striking Scimitar]], [[Equipment/Wooden Shield|Wooden Shield]], [[Equipment/Studded Leather Armor|+1 Studded Leather Armor]], [[Equipment/Darkvision Elixir (Moderate)|Darkvision Elixir (Moderate)]], 32x [[Equipment/Gold Pieces|Gold Pieces]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Deep Breath"
    desc: "  A Shikwashim mercenary can hold their breath for 20 minutes."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Scimitar"
    desc: "+20 (forceful, magical, sweep)\n__Damage__  2d6 + 10 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+19 ()\n__Damage__  1d6 + 10 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+19 (agile)\n__Damage__  1d4 + 10 bludgeoning"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+19 (thrown 30 ft.)\n__Damage__  1d6 + 10 piercing"

  - name: "Coordinated Distraction"
    desc: "`pf2:1` (auditory,concentrate,visual) With a sharp whistle or wave of their hand, the mercenary distracts an opponent so one of the mercenary's allies can land a clean blow.\n\nThe mercenary chooses a target and an ally, both of whom must be within 30 feet of the mercenary. The target is [[Conditions/Off-Guard|Off-Guard]] against the first Strike the mercenary's ally makes on its next turn; if the ally doesn't Strike that target, the effect is lost.\n\nDepending on how the mercenary distracts their foe, this action gains either the auditory or visual trait."

  - name: "Human Hunter"
    desc: "  A Shikwashim mercenary's multiple attack penalty for attacks against humans is -3 (-2 with an agile weapon) on their second attack per turn or -6 (-4 with an agile weapon) on their third or subsequent attack per turn."

  - name: "Powerful Swipe"
    desc: "`pf2:2`  The Shikwashim mercenary makes a melee Strike. If it hits, it deals an extra die of damage.\n\nThis counts as two attacks for the mercenary's multiple attack penalty."

  - name: "Terrain Advantage"
    desc: "  Non-lizardfolk creatures in difficult terrain and non-lizardfolk creatures that are in water and lack a Swim speed are [[Conditions/Off-Guard|Off-Guard]] to a Shikwashim mercenary."
 
```

```encounter-table
name: Shikwashim Mercenary
creatures:
  - 1: Shikwashim Mercenary
```




