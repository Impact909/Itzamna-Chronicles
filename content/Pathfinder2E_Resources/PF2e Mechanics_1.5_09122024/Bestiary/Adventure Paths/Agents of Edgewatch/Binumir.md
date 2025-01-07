---
title: "Binumir"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gY7jjvsT5OltxJGv" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Binumir"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #157: Devil at the Dreaming Palace"
name: "Binumir"
level: "Creature 3"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[lawful]]
trait_04: [[spirit]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Society: +10"
abilityMods: [-4, 4, 3, 0, 1, 0]
speed:  fly 25 feet
sourcebook: "_Pathfinder #157: Devil at the Dreaming Palace_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +9, __Ref__ +12, __Will__ +8"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 2 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Delay Condition"
    desc: "  The binumir's dual spirit takes longer to be affected by detrimental effects. When the binumir is the target of an effect that imparts the [[Conditions/Confused|Confused]], [[Conditions/Controlled|Controlled]], [[Conditions/Fascinated|Fascinated]], [[Conditions/Frightened|Frightened]], [[Conditions/Sickened|Sickened]], [[Conditions/Slowed|Slowed]], or [[Conditions/Stunned|Stunned]] condition, the condition is automatically suppressed until the end of the binumir's next turn."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+12 (agile, finesse, magical)\n__Damage__  1d8 + 4 void"

  - name: "Agonizing Wail"
    desc: "`pf2:2` (auditory,concentrate) The binumir unleashes a distressing cry that fills others with wrenching sadness. Creatures within 30 feet must attempt a DC 17 Will check save.\n* * *\n\n**Critical Success** The target is unaffected and is temporarily immune to Agonizing Wail for 1 minute.\n\n**Success** The target can't use reactions for 1 round.\n\n**Failure** The target is [[Conditions/Slowed|Slowed 1]] and can't use reactions for 1 minute as it sobs uncontrollably. It can attempt a new Will save to end the effect at the end of each of its turns.\n\n**Critical Failure** As failure, but the target can't make saves to end the effect."

  - name: "Dual Assault"
    desc: "`pf2:3`  The binumir makes four Strikes; no more than two can be against the same target.\n\nThese attacks count toward the binumir's multiple attack penalty, but the penalty doesn't increase until after all the attacks have been made."
 
```

```encounter-table
name: Binumir
creatures:
  - 1: Binumir
```




