---
title: "Leng Ghoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mcm56LMBPIse6ine" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dream
  - pf2e/creature/type/evil
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Leng Ghoul"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Leng Ghoul"
level: "Creature 10"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[dream]]
trait_03: [[evil]]
trait_04: [[ghoul]]
trait_05: [[undead]]
trait_06: [[unholy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Aklo, Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +21, Arcana: +19, Athletics: +19, Occultism: +21, Religion: +19, Stealth: +21"
abilityMods: [5, 7, 5, 3, 5, 6]
speed: 25 feet,  burrow 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +18, __Ref__ +21, __Will__ +19; +1 status to all saves vs. vitality"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180, void healing; __Immunities__  cold,  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scroll of 4th-rank Spell|Scroll of Confusion (Level 4)]], [[Equipment/Scroll of 4th-rank Spell|Scroll of Fly (Level 4)]]"
  - name: "Erudite"
    desc: "  Leng ghouls can cast arcane, divine, and occult spells from scrolls, with a spell DC of 28 and a spell attack roll of +20."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+23 (finesse)\n__Damage__  2d8 + 8 piercing plus ghoul-ghoul-fever,ghoul-paralysis"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, finesse)\n__Damage__  2d6 + 8 slashing plus ghoul-paralysis"

  - name: "Absorb Memories"
    desc: "`pf2:1` (manipulate) **Requirements** The Leng ghoul is adjacent to the corpse of a creature that retains flesh on its bones\n* * *\n\n**Effect** The Leng ghoul devours a chunk of the corpse and regains 6d6 healing Hit Points. At the same time, they also absorb some of the memories stored in the flesh from when the corpse was alive, gaining a +1 status bonus to all skill checks for 10 minutes.\n\nThe Leng ghoul can immediately attempt an Occultism check to learn one non-secret memory the corpse had when it was alive (use the standard DC for the creature's level). The exact memory learned is determined by the GM but is typically something of use to the Leng ghoul. The memory can't be one the creature was trying to keep secret unless the check was a critical success.\n\nA Leng ghoul can Absorb Memories from any given corpse only once.\n\n[[Bestiary Effects/Effect_ Absorb Memories|Effect: Absorb Memories]]"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Fever|Leng Ghoul Fever]]"
    desc: " (disease) **Saving Throw** DC 28 Fortitude check\n* * *\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 4d8 void damage and regains half as many Hit Points from all healing (1 day)\n\n**Stage 3** as stage 2 (1 day)\n\n**Stage 4** 4d8 void damage and gains no benefit from healing (1 day)\n\n**Stage 5** as stage 4 (1 day)\n\n**Stage 6** dead, and rises as a Leng ghoul the next sunset."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Paralysis|Paralysis]]"
    desc: " (incapacitation,occult) Any living creature hit by a Leng ghoul's attack must succeed at a DC 28 Fortitude check save or become [[Conditions/Paralyzed|Paralyzed]]. It can attempt a new save at the end of each of its turns, and the DC cumulatively decreases by 1 on each such save."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  A Leng ghoul deals an extra 2d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Leng Ghoul
creatures:
  - 1: Leng Ghoul
```



In the icy nightmare dimension of Leng, ghouls with hoofed feet gather in morbid groups to worship and research, forming societies that mockingly mimic (and in their opinion, surpass) those of the living. Most worship the malevolent gods of the Elder Mythos and see the living as little more than fodder who will eventually die and provide memories for Leng ghouls to consume and absorb. Not all Leng ghouls are evil, but most are, and even those who aren't possess sardonic senses of humor and grisly appetites that make them disturbing allies at best.
