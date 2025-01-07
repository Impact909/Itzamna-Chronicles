---
title: "Ghoul Soldier"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sr8lf4RYk77i5YZe" 
tags:
  - pf2e/creature/type/ghoul
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
  - remaster
statblock: inline
name: "Ghoul Soldier"
level: 2
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Ghoul Soldier"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[ghoul]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +9, Stealth: +8, Survival: +6"
abilityMods: [3, 2, 2, 1, 2, 3]
speed: 25 feet,  burrow 5 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +8, __Ref__ +8, __Will__ +6"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bastard Sword|Bastard Sword]], [[Equipment/Breastplate|Breastplate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Stench|Stench]]"
    desc: " (aura,olfactory) 10 feet, DC 15 Fortitude check\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (finesse)\n__Damage__  1d10 + 3 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile, finesse)\n__Damage__  1d8 + 3 slashing plus grab"

  - name: "**Melee** `pf2:1` Bastard Sword"
    desc: "+11 (two-hand d12)\n__Damage__  1d8 + 3 slashing"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Consume Flesh|Consume Flesh]]"
    desc: "`pf2:1` (manipulate) **Requirements** The ghoul is adjacent to the corpse of a creature that died within the last hour.\n* * *\n\n**Effect** The ghoul devours a chunk of the corpse and regains 2d6 healing Hit Points.\n\nIt can regain Hit Points from any given corpse only once."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Ghoul Whispers|Ghoul Whispers]]"
    desc: "`pf2:1` (auditory,linguistic,occult) **Requirements** A [[Conditions/Grabbed|Grabbed]], [[Conditions/Paralyzed|Paralyzed]], [[Conditions/Restrained|Restrained]], or [[Conditions/Unconscious|Unconscious]] creature is within the ghoul's reach\n* * *\n\n**Effect** The ghoul whispers dark thoughts and vile cravings into the creature's ears. The creature must save against the forbidden cravings curse.\n\n**Forbidden Cravings** (curse)\n\n**Saving Throw** DC 18 Will check\n\n**Stage 1** carrier with no ill effects (1 day)\n\n**Stage 2** 2d6 void damage and the target is [[Conditions/Sickened|Sickened 1]] until it consumes raw meat (1 day)\n\n**Stage 3** as stage 2\n\n**Stage 4** as stage 2 unless the target has consumed raw meat in the past 24 hours, then it takes 4d6 void damage and is [[Conditions/Sickened|Sickened 2]] until it consumes raw meat;\n\n**Stage 5** if the creature has eaten raw meat in the past 24 hours, it dies and rises as a ghoul, if not, it returns to stage 4"

  - name: "[[Creature Family Ability Glossary/(Ghoul) Grave Knowledge|Grave Knowledge]]"
    desc: " (occult) +8 skill modifier\n* * *\n\n**Frequency** once per hour\n* * *\n\n**Effect** The ghoul calls upon knowledge it retains from one creature it has consumed in the past 7 days. The ghoul attempts a skill check using a skill in which the consumed creature was trained (if it's unclear whether the creature was trained, the GM decides). The ghoul is treated as trained and uses the high skill modifier for the ghoul's level. This takes the same amount of actions or time as usual for the check.\n\nThe ghoul can instead automatically learn something specific known by a creature it consumed in the last 7 days, like the location of a [[Conditions/Hidden|Hidden]] treasure or the name of a loved one. The ghoul can do this only once for a given creature, no matter how much of its flesh the ghoul consumed."

  - name: "[[Creature Family Ability Glossary/(Ghoul) Swift Leap|Swift Leap]]"
    desc: "`pf2:1` (move) The ghoul jumps up to half its Speed. This movement doesn't trigger reactions."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ghoul Soldier
creatures:
  - 1: Ghoul Soldier
```



Retaining their martial skill, these powerful ghouls are not afraid to meet their foe in the open, feeding on the flesh of their fallen opponents to learn their combat abilities.

* * *

Few creatures are more ubiquitous to sinister locations such as lonely graveyards and ruined crypts than the flesh-eating undead known as ghouls.
