---
title: "Cloud Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.PAfIRnfgYeCQSBeW" 
tags:
  - pf2e/creature/type/air
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Cloud Giant"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Cloud Giant"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[air]]
trait_02: [[giant]]
trait_03: [[humanoid]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Common, Jotun, Sussuran"
skills:
  - name: "Skills"
    desc: "Athletics: +26, Crafting: +21, Diplomacy: +24, Intimidation: +26, Performance: +21"
abilityMods: [7, 0, 5, 1, 3, 1]
speed: 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +25, __Ref__ +18, __Will__ +21"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Ranseur|+1 Striking Ranseur]]"
  - name: "Cloudsight"
    desc: "  Cloud giants ignore concealment from weather conditions, including clouds and rain."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ranseur"
    desc: "+25 (disarm, magical, reach 20 feet)\n__Damage__  2d10 + 13 piercing"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+24 (agile, reach 15 feet)\n__Damage__  2d8 + 13 bludgeoning"

  - name: "Primal Innate Spells"
    desc: "DC 30, attack +22; __4th __  _[[Spells/Vapor Form|Vapor Form]]_; __3rd __  _[[Spells/Levitate|Levitate (At Will)]]_; __2nd __  _[[Spells/Mist|Mist (At Will)]]_"

  - name: "Crushing Cloud"
    desc: "`pf2:1` (air,primal) The cloud giant solidifies some clouds, including fog or mist, around a creature that's already in a cloud up to 120 feet away. The target takes 3d8 bludgeoning damage (DC 30 Fortitude check save). If it fails its save, it treats clouds as difficult terrain for 1 round."

  - name: "Wind Strike"
    desc: "`pf2:2` (air,primal) The cloud giant Strikes a creature with their ranseur, surrounded in a roar of rushing air. On a hit, the target takes an additional 4d8 bludgeoning damage and is [[Conditions/Deafened|Deafened]] for 1 minute. Whether or not the Strike hits, each non-cloud giant within a 20-foot emanation, including the target of the Strike, is buffeted by roaring winds and must attempt a DC 30 Fortitude check saving throw.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 2d8 sonic damage.\n\n**Failure** The creature takes 4d8 sonic damage and is deafened until the end of its next turn.\n\n**Critical Failure** As failure, but double damage and also knocked [[Conditions/Prone|Prone]]."
 
```

```encounter-table
name: Cloud Giant
creatures:
  - 1: Cloud Giant
```



The graceful and regal cloud giants are fractious, with roughly half their clans believing they should rule over humanoids regardless of their size and the rest shying away from any contact with outsiders. Due to the physical and ideological distance between clans, most rely on giant eagle or roc messengers, to arrange marriages and exchange art without setting foot in each other's territory.

Cloud giants' skin color ranges from milky white to powdery blue. They make their homes anywhere veiled by the clouds, generally mountaintops or isolated valleys, but occasionally fog-shrouded swamps or misty rainforests. Legends persist of floating cities ruled by magically gifted cloud giant queens and kings. While most cloud giants plainly state that such claims are pure fantasy, others are mysteriously tight-lipped or evasive about the matter.

* * *

Giants are massive humanoid creatures who live in remote regions throughout the world. They vary widely but are united in their hunger, requiring sustenance of their own element along with the feasts one would expect from such a massive humanoid. Although a simple matter for some giants, more esoteric types find this need a harsh reality. While a massive fistful of ice or snow alongside their meal will satisfy a frost giant, shadow giants hunger for the coagulated shadows of the Netherworld.
