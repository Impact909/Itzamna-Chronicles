---
title: "Shadow Giant"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Xg9voXpNbiXODmBs" 
tags:
  - pf2e/creature/type/giant
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/13
  - remaster
statblock: inline
name: "Shadow Giant"
level: 13
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Shadow Giant"
level: "Creature 13"

alignment: ""
size: "Large"
trait_01: [[giant]]
trait_02: [[humanoid]]
trait_03: [[shadow]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Common, Jotun, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Athletics: +27, Intimidation: +24, Stealth: +21"
abilityMods: [8, 2, 5, 0, 1, 3]
speed: 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +25, __Ref__ +20, __Will__ +23"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Chain|+1 Striking Spiked Chain]], [[Equipment/Breastplate|+1 Resilient Breastplate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+27 (disarm, reach 10 feet, trip)\n__Damage__  3d8 + 18 slashing plus pall-of-shadow"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+26 (agile, nonlethal, reach 10 feet)\n__Damage__  3d8 + 18 bludgeoning plus pall-of-shadow"

  - name: "Pall of Shadow"
    desc: " (divine,shadow) When a shadow giant hits with a melee attack, the target must succeed at a DC 30 Fortitude check save or become [[Conditions/Drained|Drained 1]] and take a –1 status penalty to Perception checks involving sight as long as they remain drained. On a critical failure, this condition doesn't heal naturally and can be removed only with magic."

  - name: "Shadow Chain"
    desc: "`pf2:2` (divine,shadow,teleportation) Shadows extend the giant's chain as they make a spiked chain Strike, increasing their reach to 60 feet for that Strike. If this hits, the target must succeed at a DC 33 Will check save or be teleported to an empty space within the shadow giant's normal reach."

  - name: "Shadowcloak"
    desc: "`pf2:1` (divine,shadow) The shadow giant gains the effect of the [[Spells/Blur|Blur]] spell for 1 minute or until it is exposed to direct sunlight, whichever comes first."
 
```

```encounter-table
name: Shadow Giant
creatures:
  - 1: Shadow Giant
```



Shadow giants are natives of the Netherworld, where they have dwelled in perpetual twilight for millennia. They live in familiar groups and uphold a nomadic way of life as they roam across ancestral lands between shadowy forests and misty chasms. These hunter-gatherers pass down lore through oral histories, conduct pilgrimages to unholy ziggurats of black stone, and bathe in the blood of their long-standing foes, including rival shadow giant clans and fiends of the Netherworld intent on enslaving their kind.

Standing 15 feet tall, with gray skin and hair only a shade lighter, shadow giants are fearsome foes with a well-earned reputation as zealous warmongers and ruthless combatants. They rarely interact with outsiders, though they may treat with proven warriors who show the giants the respect and deference they feel they deserve.

* * *

Giants are massive humanoid creatures who live in remote regions throughout the world. They vary widely but are united in their hunger, requiring sustenance of their own element along with the feasts one would expect from such a massive humanoid. Although a simple matter for some giants, more esoteric types find this need a harsh reality. While a massive fistful of ice or snow alongside their meal will satisfy a frost giant, shadow giants hunger for the coagulated shadows of the Netherworld.
