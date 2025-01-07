---
title: "Wight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AHBDMFdmG6lGelyG" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wight
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Wight"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Wight"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[undead]]
trait_02: [[unholy]]
trait_03: [[wight]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +10, Intimidation: +9, Stealth: +8"
abilityMods: [4, 1, 4, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +11, __Ref__ +6, __Will__ +10"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40, fueled by spite, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]]"
  - name: "Grave Weapon"
    desc: " (divine) The wight is bound to a dagger it was buried with. Other wights can be bound to different weapons."

abilities_mid:
  - name: ""
  - name: "Final Spite"
    desc: "`pf2:r`  **Trigger** The wight is reduced to 0 Hit Points\n* * *\n\n**Effect** The wight makes a Strike before being destroyed. This Strike can inflict corrupting spite, but fueled by spite doesn't apply."

  - name: "Fueled by Spite"
    desc: "  Each time a creature loses Hit Points due to a corrupting spite curse the wight inflicted, the wight gains 3 temporary Hit Points."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+12 (agile)\n__Damage__  1d4 + 6 slashing plus corrupting-spite"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+12 (agile, finesse, versatile s)\n__Damage__  1d4 + 6 slashing plus corrupting-spite"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+10 (agile, thrown 10 ft., versatile s)\n__Damage__  1d4 + 6 slashing plus corrupting-spite"

  - name: "Corrupting Spite"
    desc: " (curse,divine,void) The wight's unarmed attacks and bound weapons inflict a curse that makes a creature grow weak and spiteful. If a wight inflicts corrupting spite on a creature already afflicted by it, the victim attempts a new save, ignoring the result if it's better than a failure.\n\nA living humanoid that dies while under the curse rises as a wight after 1d4 rounds, controlled by the wight that killed it. The wight spawn can't inflict corrupting spite and is [[Conditions/Clumsy|Clumsy 2]]. If its creator dies or after roughly a month of existence, the new wight becomes autonomous and turns into a normal wight\n\n**Saving Throw** DC 17 Fortitude check;\n* * *\n\n**Stage 1** [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** [[Conditions/Drained|Drained 2]] and doesn't treat any creatures as allies (1 round)\n\n**Stage 3** As stage 2, except [[Conditions/Drained|Drained 3]] (1 round)\n\n**Stage 4** As stage 2, except [[Conditions/Drained|Drained 4]] (1 round)."
 
```

```encounter-table
name: Wight
creatures:
  - 1: Wight
```



Wights are intelligent undead spawned through inescapable cycles of spite. This spite might come from their own malevolent will in life, or can be instilled by necromantic rituals, typically involving the desecration of burial sites. Wights usually haunt burial grounds, catacombs, or other places of the dead. Their hunger is targeted toward the living—those whose pumping hearts and ruddy warmth inspire visceral hatred.

As many types of wights exist as types of people from which they might be created. Hulking brutes, skittering sneaks, and cunning tinkers all make for different wights with different niches to fill. The environment, too, plays a part in determining a wight's special abilities and defenses. Frost wights, for instance, can be found in parts of the world where exposure is a common end and the resentment of being left alone in the wild is a common source of spite. Durable and sustained by void energy, wights can last in harsh environments without decaying the way some lesser undead do.

A single wight can wreak significant havoc if it is compelled to rise from its tomb. Because creatures slain under a wight's curse can become wights as well, all it takes is a single wight and a handful of unlucky graveyard visitors to create a veritable horde of these undead. Thus, canny priests and adventurers know that the best solution to a wight problem is swift and total eradication. Care must be taken, though, to destroy wight spawn before attempting to destroy the parent wight, for spawn without a master gain the ability to create spawn of their own.
