---
title: "Yellow Musk Brute"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HwSxMGZcOSKmXmeg" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Yellow Musk Brute"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Yellow Musk Brute"
level: "Creature 2"

alignment: ""
size: "Large"
trait_01: [[mindless]]
trait_02: [[plant]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +9"
abilityMods: [5, -3, 4, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__ +10, __Ref__ +3, __Will__ +6"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45; __Immunities__  mental; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  A yellow musk brute is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "Entangling Tendrils"
    desc: " (aura) 5 feet. Grasping tendrils extend out from the brute. When the brute ends its movement next to a creature, or a creature ends its turn next to the brute, that creature must succeed at a DC 15 Reflex check save or be [[Conditions/Grabbed|Grabbed]] by the tendrils."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+11 (reach 10 feet)\n__Damage__  1d12 + 5 bludgeoning plus improved-push,pollen-touch"

  - name: "Limb Extension"
    desc: "  **Trigger** The yellow musk brute is reduced to 15 HP or fewer\n* * *\n\n**Effect** Creeper tendrils tear through the brute's limbs, causing its forearms to tear loose. The brute's melee reach increases by 5 feet."

  - name: "Pollen Touch"
    desc: "  When the brute strikes a creature, that creature is exposed to yellow musk creeper pollen, as Spray Pollen (DC 15). The creature is fascinated by the yellow musk creeper that spawned the brute, not by the brute itself. The affected creature must attempt a DC 15 Will check save.\n\nOnce a creature succeeds at any save against Spray Pollen, it becomes temporarily immune for 24 hours.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]]. For as long as it is fascinated, it must spend each of its actions to move closer to the yellow musk creeper that spawned the brute as expediently as possible, while avoiding obvious dangers. If the creature is adjacent to the yellow musk creeper, it stays still and doesn't act.\n\n**Critical Failure** As failure, but the condition doesn't end automatically. The creature can attempt a new save at the end of each of its turns. On a success, the fascinated condition and other effects end."

  - name: "[[Bestiary Ability Glossary/Improved Push|Improved Push]]"
    desc: "  The monster can use [[Bestiary Ability Glossary/Push|Push]] as a free action triggered by a hit with its initial attack."
 
```

```encounter-table
name: Yellow Musk Brute
creatures:
  - 1: Yellow Musk Brute
```



A creature transformed by a yellow musk creeper's tendrils boring into its brain becomes a yellow musk thrall if it's Small or Medium, or a yellow musk brute if Large (a Small creature becomes a Small thrall rather than a Medium one). The transformation takes 1 hour. A yellow musk thrall takes only the most rudimentary of actions: bringing the yellow musk creeper water and new creatures to infest. After a few days (or if the creeper dies), the thrall wanders off into the wilderness and falls dead within 24 hours. The body of a deceased thrall sprouts a new yellow musk creeper within hours of its death, becoming a fully grown plant within 24 hours.
