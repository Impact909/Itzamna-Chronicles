---
title: "Hobgoblin Soldier"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.knhmXkYjzViJ45Lq" 
tags:
  - pf2e/creature/type/hobgoblin
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Hobgoblin Soldier"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Hobgoblin Soldier"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[hobgoblin]]
trait_02: [[humanoid]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Common, Goblin"
skills:
  - name: "Skills"
    desc: "Athletics: +6, Stealth: +6"
abilityMods: [3, 3, 2, 0, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18 (20 with shield raised); __Fort__ +5, __Ref__ +6, __Will__ +5"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|Longsword]], [[Equipment/Shortbow|Shortbow]], [[Equipment/Wooden Shield|Wooden Shield]], [[Equipment/Breastplate|Breastplate]], 10x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Formation"
    desc: "  When it's adjacent to at least two other allies, the hobgoblin soldier gains a +1 circumstance bonus to AC and saving throws. This bonus increases to +2 to Reflex saves against area effects."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+8 (versatile p)\n__Damage__  1d8 + 3 slashing"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+8 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  1d6 piercing"
 
```

```encounter-table
name: Hobgoblin Soldier
creatures:
  - 1: Hobgoblin Soldier
```



Soldiers make up the bulk of hobgoblin society, whether that society is a village or a military unit.

* * *

Hobgoblins may appear to outsiders to be the most civilized of goblinkind, but their civilization is hardly one of kindness and equality-instead, they revel in all that is militaristic, tyrannical, cruel, and destructive. Hobgoblins are singularly devoted to war, and their entire culture is built upon fostering and maintaining conflict while simultaneously proving their superiority in battle. Hobgoblins are highly organized, and they work efficiently and effectively in groups, whether that group is a small raiding party, a roving war band, or a fully regimented army. Hobgoblin rulers require little provocation before declaring war, and more often than not, such wars are waged to gain slaves or territory. Physically, hobgoblins stand about as tall as humans and have gray, ashen skin.

Hobgoblin society is organized along military lines, and every hobgoblin is effectively a member of the army. Each hobgoblin in a community has a rank in the military hierarchy, and individuals are naturally ambitious and obsessed with advancement. Hobgoblins are constantly expected to prove that they're fearless, ruthless, cunning, and strong. Demonstrating such aptitudes is an individual hobgoblin's best hope for promotion through the ranks, but failure leads only to cruel exploitation at the hands of their superiors. Though brutal, hobgoblin society is a true meritocracy, and all hobgoblins, regardless of age, gender, or birth, wield authority and earn respect from their peers based on their skill in battle. Even those individuals who serve in non-combat roles in hobgoblin society-blacksmiths, builders, cooks, messengers, quartermasters, and the like-know that they perform vital jobs that support the larger hobgoblin army, though they rarely rise above the rank of common soldier. Everyone contributes to the larger whole, ensuring that hobgoblin society is the strongest and most efficient it can be, and anyone who fails to do so is culled from the army and this hobgoblin society as dead weight. Hobgoblins don't usually engage in trade with other races, or even with other hobgoblin tribes, preferring to take what they want by force.
