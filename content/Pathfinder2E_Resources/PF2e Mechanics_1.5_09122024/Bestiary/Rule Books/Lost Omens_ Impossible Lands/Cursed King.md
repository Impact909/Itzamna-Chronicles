---
title: "Cursed King"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sbtNlQOYd3KwZglC" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/mummy
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Cursed King"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: Impossible Lands"
name: "Cursed King"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[mummy]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Necril; plus any two ancient languages (can&#x27;t speak)"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Intimidation: +17, Stealth: +17"
abilityMods: [7, 3, 4, -4, 4, 3]
speed: 25 feet
sourcebook: "_Pathfinder Lost Omens: Impossible Lands_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +20, __Ref__ +20, __Will__ +16"
hp: 210
health:
  - name: ""
  - name: HP
    desc: "210, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ fire 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Deadly Pursuit"
    desc: "`pf2:r`  **Trigger** A creature within the cursed king's reach attempts to move away\n* * *\n\n**Effect** The cursed king Strides up to its Speed, keeping the creature within reach until the creature stops or the cursed king has moved its full Speed. If the creature is still within reach, the cursed king makes a jaws Strike against it."

  - name: "False Authority"
    desc: " (aura,emotion,fear,mental) 30 feet. When a creature enters or ends its turn within the cursed king's aura, it must attempt a DC 26 Will check save. If it fails, it becomes [[Conditions/Frightened|Frightened 2]]. If it critically fails, it's cowed into submission; in addition to becoming frightened 2, it must use its first action on its turn to kneel or flee from the cursed king. A creature who succeeds at its saving throw becomes immune to the king's false authority for 24 hours."

  - name: "Usurper's Curse"
    desc: " (curse) When a creature slays a cursed king, it must attempt a DC 29 Will check save. On a failure, it suffers the effects of the usurper's curse."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (unarmed)\n__Damage__  2d12 + 13 piercing plus grab"

  - name: "**Melee** `pf2:1` Fist"
    desc: "+23 (agile, unarmed)\n__Damage__  2d8 + 13 bludgeoning"

  - name: "Berserk"
    desc: "  At the beginning of each of its turns in combat, a cursed king must attempt a DC 2 Flat check. If it succeeds, the DC increases by 1. If it fails, it immediately goes berserk, becoming mindless for the rest of its turn, immune to all mental effects, and attacking the nearest creature it can reach. While it's berserk, each of its unarmed attacks gain the deadly d8 trait. At the end of a turn it failed this flat check or whenever the combat encounter ends, the DC resets to 2."

  - name: "Usurper's Curse"
    desc: " (curse,polymorph) DC 30 Will check saving throw. On a failure, the creature who killed the cursed king becomes [[Conditions/Stupefied|Stupefied 1]]. On a critical failure, it becomes [[Conditions/Stupefied|Stupefied 2]]. As long as that creature remains cursed, it can't remove or decrease the value of the stupefied condition in any way. Afflicted creatures must attempt the saving throw again every 24 hours, increasing the stupefied condition by 1 on a failure or 2 on a critical failure. If the condition ever increases past [[Conditions/Stupefied|Stupefied 4]], they transform, body and mind, into the same animal as the cursed king's head, similar to the critical failure effect of [[Spells/Cursed Metamorphosis|Cursed Metamorphosis]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Cursed King
creatures:
  - 1: Cursed King
```



A cursed king is a grotesque mockery of ambition. When treasonous advisors, false prophets, and rebel leaders are captured by evil rulers, they're subjected to all manner of torture and humiliation before their eventual executions. But the cursed king isn't even granted dignity in death, as after their beheading, a desiccated animal head is sewn onto their neck. These horrific mummies are then dressed in fine linens and jewelry befitting royalty—a permanent warning of what happens to those who seek to rise above their station.

A cursed king is bound in servitude to the ruler against whom they once fought, forced to act as a bodyguard. Even the death of their maker gives no reprieve, as they guard the true monarch's tomb forever.
