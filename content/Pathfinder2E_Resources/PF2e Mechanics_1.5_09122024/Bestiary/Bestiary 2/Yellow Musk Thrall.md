---
title: "Yellow Musk Thrall"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.04i4CsxeF33CsuER" 
tags:
  - pf2e/creature/type/mindless
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/-1
statblock: inline
name: "Yellow Musk Thrall"
level: -1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Yellow Musk Thrall"
level: "Creature -1"

alignment: ""
size: "Medium"
trait_01: [[mindless]]
trait_02: [[plant]]
modifier: 0
perception:
  - name: "Perception"
    desc: "+0; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +5"
abilityMods: [3, -2, 2, -5, 0, -2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +6, __Ref__ +0, __Will__ +2"
hp: 12
health:
  - name: ""
  - name: HP
    desc: "12; __Immunities__  mental; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

  - name: "Slow"
    desc: "  A yellow musk thrall is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

abilities_mid:
  - name: ""
  - name: "Entangling Tendrils"
    desc: " (aura) 5 feet. Grasping tendrils extend out from the thrall. When the thrall ends its movement next to a creature, or a creature ends its turn next to the thrall, that creature must succeed at a DC 14 Reflex check save or be [[Conditions/Grabbed|Grabbed]] by the tendrils."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+7 ()\n__Damage__  1d4 + 3 bludgeoning plus grab,pollen-touch"

  - name: "Limb Extension"
    desc: "  **Trigger** The yellow musk thrall is reduced to 4 HP or fewer\n* * *\n\n**Effect** Creeper tendrils tear through the thrall's limbs, causing its forearms to tear loose. The thrall's melee reach increases by 5 feet."

  - name: "Pollen Touch"
    desc: "  When the thrall strikes a creature, that creature is exposed to yellow musk creeper pollen, as Spray Pollen (DC 14). The creature is [[Conditions/Fascinated|Fascinated]] by the yellow musk creeper that spawned the thrall, not by the thrall itself. The affected creature must attempt a DC 14 Will check save.\n\nOnce a creature succeeds at any save against Spray Pollen, it becomes temporarily immune for 24 hours.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]]. For as long as it is fascinated, it must spend each of its actions to move closer to the yellow musk creeper that spawned the thrall as expediently as possible, while avoiding obvious dangers. If the creature is adjacent to the yellow musk creeper, it stays still and doesn't act.\n\n**Critical Failure** As failure, but the condition doesn't end automatically. The creature can attempt a new save at the end of each of its turns. On a success, the fascinated condition and other effects end."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Yellow Musk Thrall
creatures:
  - 1: Yellow Musk Thrall
```



A creature transformed by a yellow musk creeper's tendrils boring into its brain becomes a yellow musk thrall if it's Small or Medium, or a yellow musk brute if Large (a Small creature becomes a Small thrall rather than a Medium one). The transformation takes 1 hour. A yellow musk thrall takes only the most rudimentary of actions: bringing the yellow musk creeper water and new creatures to infest. After a few days (or if the creeper dies), the thrall wanders off into the wilderness and falls dead within 24 hours. The body of a deceased thrall sprouts a new yellow musk creeper within hours of its death, becoming a fully grown plant within 24 hours.
