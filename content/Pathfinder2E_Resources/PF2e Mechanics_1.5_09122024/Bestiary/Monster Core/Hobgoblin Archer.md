---
title: "Hobgoblin Archer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.M5Gv44UUBpLd8aUy" 
tags:
  - pf2e/creature/type/hobgoblin
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Hobgoblin Archer"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Hobgoblin Archer"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[hobgoblin]]
trait_02: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Goblin"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +8, Stealth: +10"
abilityMods: [2, 4, 2, 0, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +10, __Ref__ +12, __Will__ +8"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Crossbow|Crossbow]], [[Equipment/Shortsword|Shortsword]], [[Equipment/Scale Mail|Scale Mail]], 20x [[Equipment/Bolts|Bolts]]"
abilities_mid:
  - name: ""
  - name: "Formation"
    desc: "  When it's adjacent to at least two other allies, the hobgoblin archer gains a +1 circumstance bonus to AC and saving throws. This bonus increases to +2 to Reflex saves against area effects."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+12 (agile, versatile s)\n__Damage__  1d6 + 4 piercing"

  - name: "**Ranged** `pf2:1` Crossbow"
    desc: "+14 (range increment 120 feet, reload 1)\n__Damage__  1d8 + 2 piercing plus crossbow-precision"

  - name: "Crossbow Precision"
    desc: "  The first time the archer hits with a crossbow attack in a round, it deals 1d8 extra precision damage."

  - name: "Perfect Aim"
    desc: "  The hobgoblin archer ignores the [[Conditions/Concealed|Concealed]] condition.\n\nTheir targets don't benefit from lesser cover, and they reduce the AC bonus from standard cover by 2 against the hobgoblin archer's attack."

  - name: "Running Reload"
    desc: "`pf2:1`  The archer Strides, Steps, or [[Actions/Sneak|Sneaks]], then Interacts to reload."
 
```

```encounter-table
name: Hobgoblin Archer
creatures:
  - 1: Hobgoblin Archer
```



Bands of hobgoblin soldiers typically have at least one archer among their ranks. In smaller groups, the hobgoblin archer also serves as that band's captain.

* * *

Hobgoblins may appear to outsiders to be the most civilized of goblinkind, but their civilization is hardly one of kindness and equality-instead, they revel in all that is militaristic, tyrannical, cruel, and destructive. Hobgoblins are singularly devoted to war, and their entire culture is built upon fostering and maintaining conflict while simultaneously proving their superiority in battle. Hobgoblins are highly organized, and they work efficiently and effectively in groups, whether that group is a small raiding party, a roving war band, or a fully regimented army. Hobgoblin rulers require little provocation before declaring war, and more often than not, such wars are waged to gain slaves or territory. Physically, hobgoblins stand about as tall as humans and have gray, ashen skin.

Hobgoblin society is organized along military lines, and every hobgoblin is effectively a member of the army. Each hobgoblin in a community has a rank in the military hierarchy, and individuals are naturally ambitious and obsessed with advancement. Hobgoblins are constantly expected to prove that they're fearless, ruthless, cunning, and strong. Demonstrating such aptitudes is an individual hobgoblin's best hope for promotion through the ranks, but failure leads only to cruel exploitation at the hands of their superiors. Though brutal, hobgoblin society is a true meritocracy, and all hobgoblins, regardless of age, gender, or birth, wield authority and earn respect from their peers based on their skill in battle. Even those individuals who serve in non-combat roles in hobgoblin society-blacksmiths, builders, cooks, messengers, quartermasters, and the like-know that they perform vital jobs that support the larger hobgoblin army, though they rarely rise above the rank of common soldier. Everyone contributes to the larger whole, ensuring that hobgoblin society is the strongest and most efficient it can be, and anyone who fails to do so is culled from the army and this hobgoblin society as dead weight. Hobgoblins don't usually engage in trade with other races, or even with other hobgoblin tribes, preferring to take what they want by force.
