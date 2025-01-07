---
title: "Soulbound Homunculus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.p5EeStK7IYcEhvVe" 
tags:
  - pf2e/creature/type/construct
  - pf2e/creature/type/soulbound
  - pf2eMonster
  - pf2e/creature/level/0
  - remaster
statblock: inline
name: "Soulbound Homunculus"
level: 0
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Soulbound Homunculus"
level: "Creature 0"

alignment: ""
size: "tiny"
trait_01: [[construct]]
trait_02: [[soulbound]]
modifier: 3
perception:
  - name: "Perception"
    desc: "+3; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Stealth: +5"
abilityMods: [-1, 3, 0, 0, 1, -2]
speed: 15 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +2, __Ref__ +7, __Will__ +3"
hp: 17
health:
  - name: ""
  - name: HP
    desc: "17; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  unconscious,  vitality,  void"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+7 (finesse, magical, reach 0 feet)\n__Damage__  1d4 piercing plus homunculus-poison"

  - name: "Homunculus Poison"
    desc: " (poison) A homunculus has one dose of poison in a reservoir in its head. It can refill this poison from its reserves with an Interact action\n\n**Saving Throw** DC 15 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)."
 
```

```encounter-table
name: Soulbound Homunculus
creatures:
  - 1: Soulbound Homunculus
```



Most homunculi use a dose of their creator's blood as their spark of life, but it's possible to use a technique similar to that used in the crafting of a soulbound doll to give a homunculus a personality and the semblance of life. These homunculi gain the soulbound trait, lose immunity to spirit, can speak, and do not have a special link to a creator, yet the process tends to warp the soul used so that, more often than not, what rises in the new homunculus body is a parody of its prior life. As such, soulbound homunculi are generally created by cruel spellcasters as a method of humiliating and tormenting vanquished enemies.

* * *

A homunculus is a tiny servitor construct created by a crafter to serve as a spy, scout, messenger, or assistant. When a crafter first begins to study the art of creating constructs, they often craft a homunculus first, since the creation process is simple and inexpensive due to a magical shortcut: the use of the creator's own blood. This forges a link between the homunculus and its master, causing the homunculus to gain a spark of the creator's intellect, as well as the same moral values and some of the creator's basic personality traits. Homunculi left to their own devices never stray far from their masters.

In most cases, a homunculus doesn't survive the death of its master for long. Deprived of its creator, a homunculus loses focus and grows increasingly selfdestructive, and some even end up battering themselves to annihilation. Rarely, a homunculus with a slain master survives the trauma with its mind intact, often seeing itself as its deceased creator's child or successor and attempting to further its creator's legacy as best it can. In such cases, and if the homunculus was in close proximity to its master upon that creature's death, a portion of the dead master's soul "infects" the surviving homunculus as they pass on to the afterlife.

This doesn't result in a truly soulbound homunculus, since only a fragment of the soul is left behind, but this is still enough to grant the homunculus a greater personality, free will of its own, and perhaps most importantly, the ability to speak. Over time, a few of these "awakened" homunculi even go so far as to become convinced that they are the reincarnation of their prior masters, although their actual personalities never quite reach the depth and complexity of a truly living creature. They are, at best, caricatures of the master, and at worst, they become awful, bitter-minded parodies of life itself. Still, a free-willed homunculus might pursue studies in its creator's class, becoming a unique creature with the abilities of that class if time and fortune permit.

Homunculi are created from a mixture of clay, ash, mandrake root, spring water, and a pint of the creator's own blood. It is possible for a separate donor to provide the blood, but the process is more difficult.
