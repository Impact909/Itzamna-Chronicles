---
title: "Imperfect Automaton"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7IYHZpavHXDmPRe1" 
tags:
  - pf2e/creature/type/automaton
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Imperfect Automaton"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Monsters of Myth"
name: "Imperfect Automaton"
level: "Creature 6"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[automaton]]
trait_02: [[construct]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Osiriani; one language depending on its mortal life; telepathy 30 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +11, Athletics: +13, Crafting: +13, Intimidation: +12, Society: +11, Stealth: +10"
abilityMods: [5, 3, 4, 3, 0, 2]
speed: 25 feet
sourcebook: "_Pathfinder Lost Omens: Monsters of Myth_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +16, __Ref__ +11, __Will__ +14"
hp: 85
health:
  - name: ""
  - name: HP
    desc: "85; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Resistances__ physical 5 (except adamantine)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 30 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Unsubstantiated Consciousness"
    desc: "  When an imperfect automaton succeeds at a Will save, it gets a critical success instead. When it fails at a Will save, it gets a critical failure instead."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+17 (magical)\n__Damage__  2d8 + 8 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Energy Beam"
    desc: "+17 (cold, magical, range increment 60 feet)\n__Damage__  2d10 + 3 cold"

  - name: "Empty Wail"
    desc: "`pf2:2` (auditory,emotion,mental) The imperfect automaton utters a mournful cry in a 30-foot cone. The cry deals 4d6 mental damage to all creatures in the area (DC 22 Will check save). The imperfect automaton can't use its Empty Wail again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is [[Conditions/Stupefied|Stupefied 1]] for 1d4+1 rounds.\n\n**Critical Failure** The creature takes double damage and is stupefied 1 for 1d4+1 rounds and [[Conditions/Stunned|Stunned 1]]."

  - name: "Impassioned Strikes"
    desc: "  While the imperfect automaton is affected by an emotion effect, its fist Strikes deal 1d6 additional mental damage."

  - name: "Mortal Reflection"
    desc: "`pf2:1` (emotion) **Requirements** The imperfect automaton has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The imperfect automaton draws upon the target's emotions to recall a semblance of mortal feeling, gaining a +5-foot status bonus to its Speed for 1 minute. If the grabbed or restrained creature has an ongoing emotion or mental effect with a counteract rank of 4 or lower, the imperfect automaton can gain a copy of that effect that lasts for 1 minute.\n\n[[Bestiary Effects/Effect_ Mortal Reflection|Effect: Mortal Reflection]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Imperfect Automaton
creatures:
  - 1: Imperfect Automaton
```




