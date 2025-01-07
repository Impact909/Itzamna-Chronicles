---
title: "Vrolikai"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3pJtsQUZkGT22bPT" 
tags:
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Vrolikai"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vrolikai"
level: "Creature 20"

alignment: ""
size: "Large"
trait_01: [[demon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Darkvision, Truesight"
languages: "Chthonian, Draconic, Empyrean, Necril; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +37, Arcana: +33, Athletics: +36, Deception: +36, Intimidation: +38, Religion: +34, Stealth: +34, Survival: +34"
abilityMods: [10, 7, 9, 6, 6, 8]
speed: 35 feet,  fly 50 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +35, __Ref__ +33, __Will__ +34; +1 to all saves vs. magic"
hp: 440
health:
  - name: ""
  - name: HP
    desc: "440; __Immunities__  death effects; __Weaknesses__ cold iron 15, holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 Feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Death-Stealing Gaze"
    desc: " (aura,divine,visual) 30 feet. When a non-demon ends its turn in the aura, it must attempt a DC 38 Fortitude check save. If it fails, it becomes [[Conditions/Drained|Drained 1]].\n\nA creature that dies while it has drain from a vrolikai's gaze rises as a ghoul the next midnight. The GM determines what kind of ghoul."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (magical, reach 10 feet, unholy)\n__Damage__  4d12 + 18 piercing"

  - name: "**Melee** `pf2:1` Black Flame Knife"
    desc: "+40 (agile, magical, unholy)\n__Damage__  3d4 + 18 piercing 2d6 void"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+38 (magical, reach 15 feet, unholy)\n__Damage__  4d8 + 18 piercing plus mindwarping"

  - name: "Divine Innate Spells"
    desc: "DC 44, attack +36; __10th __  _[[Spells/Execute|Execute]]_, _[[Spells/Massacre|Massacre]]_, _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __7th __  _[[Spells/Regenerate|Regenerate]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_"

  - name: "Black Flame Knives"
    desc: "`pf2:1` (divine,unholy) The vrolikai manifests a dagger-shaped blade of what looks like crystallized black flame in each of their four hands. These weapons function as _+2 greater striking daggers_ that deal an additional 2d6 void damage. They fade away into nothingness 1 minute after a vrolikai no longer carries them."

  - name: "Consume Death"
    desc: "`pf2:1` (concentrate,divine,visual) The vrolikai focuses their deathstealing gaze upon a single target they can see within 30 feet. The target must immediately attempt a Fortitude save against death-stealing gaze.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is affected by death-stealing gaze and becomes [[Conditions/Drained|Drained 1]]. If the creature was already drained 1 by the death-stealing gaze before attempting the save, a failed save increases the value of the drained condition by 1, to a maximum of [[Conditions/Drained|Drained 4]]. The vrolikai gains 10 temporary Hit Points, and the drained creature is temporarily immune until the start of the vrolikai's next turn.\n\n**Critical Failure** As failure, but the creature increases the amount of drain by 2."

  - name: "Focused Flames"
    desc: "`pf2:2`  The vrolikai attacks a single target with all of their black flame knives. The demon makes a black flame knife Strike with the following additional effects. This counts toward the vrolikai's multiple attack penalty as a number of attacks equal to the number of back flame knives the vrolikai used.\n* * *\n\n**Critical Success** The target takes an additional 2d6 void damage for each knife beyond the first (typically 6d6 extra damage) and takes 4d6 persistent void damage.\n\n**Success** The target takes an additional 2d6 void damage for each knife beyond the first.\n\n**Failure** The vrolikai deals the damage their black flame knife Strike normally deals on a hit."

  - name: "Mindwarping"
    desc: " (emotion,mental) The sting of a vrolikai is mind-warping. A creature struck must attempt a DC 44 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Stupefied|Stupefied 1]] for 1 minute.\n\n**Failure** The creature becomes stupefied 1. If it's already stupefied, its stupefied value increases by 1 instead (to a maximum of [[Conditions/Stupefied|Stupefied 4]]).\n\n**Critical Failure** As failure, plus the creature is [[Conditions/Confused|Confused]] for 1 minute."
 
```

```encounter-table
name: Vrolikai
creatures:
  - 1: Vrolikai
```



Powerful vrolikais command the untamed armies of demonkind, uniting them behind their one unifying desire for death and destruction. Unlike other demons, the dreaded vrolikai doesn't form directly from a single soul—they instead manifest when a demon devours so many damned souls that their own individual desires are lost in the sinful cacophony. A vrolikai who survives this process gains great power and can claim a region of the Outer Rifts as their own domain.

Vrolikais' enthusiastic embrace of the multitude of sins makes them uniquely suited to lead and unite demons, such that even demon lords often must rely on vrolikais to command their forces. The chaotic and conflicting motivations of demonkind leave little room to find common ground, but the vrolikai can expound upon the beauty of every kind of sin while marching demon armies to battle.

* * *

When a sinful mortal soul is judged and sent on to the Outer Rifts, it can become a deadly fiend—a demon. Demons are living incarnations of sin—be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold—the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Outer Rifts.

Demons are selfish and self-absorbed creatures, and most firmly believe that mortals only play at being more virtuous than fiends. They enjoy tempting mortals into damnation to both indulge their egos and swell their armies. Like many other fiends, one of the great rewards of this manipulation is fulfilling their hunger for souls. In their eyes, the primary use for these souls is to spawn new demons, who can serve as soldiers, slaves, pawns, or even currency for their more powerful masters.
