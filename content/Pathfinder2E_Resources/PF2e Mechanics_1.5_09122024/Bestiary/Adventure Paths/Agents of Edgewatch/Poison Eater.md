---
title: "Poison Eater"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8NPIgHDzSWqkUaZf" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Poison Eater"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #160: Assault on Hunting Lodge Seven"
name: "Poison Eater"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[human]]
trait_04: [[humanoid]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Intimidation: +15, Religion: +14"
abilityMods: [4, 3, 4, 0, 1, 1]
speed: 25 feet
sourcebook: "_Pathfinder #160: Assault on Hunting Lodge Seven_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +19, __Ref__ +15, __Will__ +13"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Resistances__ poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "3x [[Equipment/Dagger|Dagger]], [[Equipment/Maul|+1 Maul]], [[Equipment/Chain Mail|Chain Mail]], 5x [[Equipment/Giant Scorpion Venom|Giant Scorpion Venom]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Toxin-Inured"
    desc: "  A poison eater can't gain the [[Conditions/Enfeebled|Enfeebled]] or [[Conditions/Sickened|Sickened]] condition from poisons."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Maul"
    desc: "+19 (magical, shove)\n__Damage__  1d12 + 6 bludgeoning plus knockdown"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+18 (agile, versatile s)\n__Damage__  1d4 + 6 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+17 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 8 piercing"

  - name: "Consume Poison"
    desc: "`pf2:2` (manipulate) The poison eater uses an Interact action to draw a dose of poison and eats it, gaining strength.\n\nThe poison-eater's Strikes deal two weapon dice of damage rather than one. The poison eater is affected by the consumed poison normally and, therefore, usually chooses poisons mitigated by their poison resistance and toxin-inured ability.\n\nAt the end of each of their turns, the poison eater attempts a DC 17 Flat check check; on a success, this ability ends."

  - name: "Poison Frenzy"
    desc: "  **Requirements** The poison eater isn't [[Conditions/Fatigued|Fatigued]] or already in a frenzy\n\n**Trigger** the poison eater damages a creature while Consume Poison is in effect\n* * *\n\n**Effect** The poison eater flies into a frenzy that lasts for 1 minute. While in a frenzy, the poison eater gains a +1 status bonus to attack rolls with melee Strikes, gains a +4 status bonus to damage rolls with melee Strikes, gains 20 temporary Hit Points until the end of the frenzy, and takes a -2 status penalty to AC. The poison eater can't voluntarily end their frenzy. After their frenzy, the poison eater is fatigued.\n\n[[Bestiary Effects/Effect_ Poison Frenzy|Effect: Poison Frenzy]]"

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Poison Eater
creatures:
  - 1: Poison Eater
```




