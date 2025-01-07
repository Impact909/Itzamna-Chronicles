---
title: "Yeti"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.q78UPYxZGl67Ts05" 
tags:
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Yeti"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Yeti"
level: "Creature 5"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[humanoid]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Athletics: +14, Stealth: +12, Survival: +11"
abilityMods: [5, 2, 4, -1, 4, -1]
speed: 35 feet,  climb 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +15, __Ref__ +11, __Will__ +13; +4 status to all saves vs. fear and dreams"
hp: 115
health:
  - name: ""
  - name: HP
    desc: "115; __Immunities__  cold; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

  - name: "Snowblind"
    desc: "  When [[Actions/Hide|Hiding]], the yeti is [[Conditions/Concealed|Concealed]] by any snowfall, even if it's not thick enough to make other creatures concealed."

abilities_mid:
  - name: ""
  - name: "Nightmare Guardian"
    desc: "  Yetis gain a +4 status bonus to saves against fear and against spells and abilities that affect dreams. A yeti that falls prey to a supernatural nightmare loses this ability and becomes permanently enraged, gaining a +1 status bonus to attack and damage rolls and a -1 status penalty to AC."

  - name: "Vanish"
    desc: "`pf2:r`  **Trigger** The yeti is [[Conditions/Hidden|Hidden]] or [[Conditions/Undetected|Undetected]] while not in combat, and a creature would observe it.\n* * *\n\n**Effect** The yeti Strides or Climbs up to half its Speed to a location where it can [[Actions/Hide|Hide]], then Hides. If its new Stealth check result meets or exceeds the triggering creature's Perception DC, the yeti remains hidden."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 ()\n__Damage__  2d10 + 5 slashing"

  - name: "Arctic Passage"
    desc: "  The yeti ignores difficult terrain caused by ice or snow."

  - name: "Grizzly Arrival"
    desc: " (emotion,fear,mental) **Trigger** The yeti hits a creature in the first round of combat and the yeti was [[Conditions/Hidden|Hidden]] from that creature at the start of combat.\n* * *\n\n**Effect** Each enemy within 30 feet that witnesses the attack (including the target of the attack) must attempt a DC 23 Will check save. On a failure, the creature is [[Conditions/Frightened|Frightened 2]]; on a critical failure, it's [[Conditions/Frightened|Frightened 4]]."

  - name: "[[Bestiary Ability Glossary/Rend|Rend]]"
    desc: "`pf2:1`  Claw\n* * *\n\nA Rend entry lists a Strike the monster has.\n\n**Requirements** The monster hit the same enemy with two consecutive Strikes of the listed type in the same round.\n* * *\n\n**Effect** The monster automatically deals that Strike's damage again to the enemy."
 
```

```encounter-table
name: Yeti
creatures:
  - 1: Yeti
```



Nearly a myth, a yeti is rarely seen—and even when it is, it is often too late. Yetis dwell amid the highest, most remote peaks of the world, coming down from their snowy mountain holds to raid, steal livestock, and sometimes feed their insatiable urges for slaughter and destruction. Those folks who live at the foot of a yeti-ruled mountain warn of the "abominable snowmen": monstrous, furcovered humanoids who leave strange and bloody tracks in the snow.

In actuality, most yetis protect the world rather than hunt its other denizens, guarding eldritch portals that link the mortal Universe and other, much stranger dimensions of reality. From within these snow-covered arches and ancient stone doorways, aliens, living nightmares, fiends, and worse can emerge into the world. Yetis who guard these portals sometimes succumb to the horrors within, taking on the bloodthirsty urges and horrific behaviors of the very monsters they strive to guard against. Driven out of their clans and forced to wander alone, they give rise to the myth of the abominable snowman. These exiled yetis often fully embrace the corrupting elements that caused their exile in the first place, growing more powerful and more deadly.
