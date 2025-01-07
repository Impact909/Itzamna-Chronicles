---
title: "Lacedon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AzmvQ77lS907BUhq" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Lacedon"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Lacedon"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[chaotic]]
trait_03: [[evil]]
trait_04: [[ghoul]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Common, Necril, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +9, Stealth: +8, Survival: +7"
abilityMods: [3, 4, 3, 1, 1, 3]
speed: 25 feet,  swim 30 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +10, __Will__ +7"
hp: 32
health:
  - name: ""
  - name: HP
    desc: "32, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Corpse Scent (Imprecise) 1 mile"
    desc: "  The lacedon can smell humanoid corpses in the water from up to 1 mile away."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (finesse)\n__Damage__  1d6 + 5 piercing plus ghoul-ghoul-fever"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile, finesse)\n__Damage__  1d4 + 5 slashing"

  - name: "[[Bestiary Ability Glossary/Aquatic Ambush|Aquatic Ambush]]"
    desc: "`pf2:1`  45 feet\n* * *\n\n**Requirements** The monster is hiding in water and a creature that hasn't detected it is within the listed number of feet.\n* * *\n\n**Effect** The monster moves up to its swim Speed + 10 feet toward the triggering creature, traveling on water and on land. Once the creature is in reach, the monster makes a Strike against it. The creature is [[Conditions/Off-Guard|Off-Guard]] against this Strike."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The lacedon is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The lacedon devours a chunk of the corpse and regains 2d6 healing Hit Points. It can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 16 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d6 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 2d6 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a [[Bestiary 1/Ghoul|Ghoul]] the next midnight."

  - name: "Paralyzing Spew"
    desc: "`pf2:1` (incapacitation,occult) The lacedon discharges a spray of carrion vomit at a creature within 20 feet, dealing 1d6 poison damage with a DC 17 Fortitude check. A non-elf creature that fails its save is also [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save to end the paralysis at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save. The lacedon can't use Paralyzing Spew again for 1d4 rounds."
 
```

```encounter-table
name: Lacedon
creatures:
  - 1: Lacedon
```



Feared by mariners and coastal dwellers everywhere, the aquatic ghouls known as lacedons are said to be the spawn of an ancient crew of sailors who became lost at sea and were forced to resort to cannibalism to survive. Their appearance is the stuff of a diver's nightmare, supplementing the vicious traits of their land-bound kin with spines, fins, and wide mouths bristling with needle-sharp teeth like piscine predators of the nethermost ocean depths.

* * *

Devious and cunning, ghouls can be found anywhere corpses are laid to rest, forever seeking to satisfy their boundless craving for humanoid flesh.
