---
title: "Yamaraj"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NuHDWxz7YOYj4p3Z" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Yamaraj"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Yamaraj"
level: "Creature 20"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 37
perception:
  - name: "Perception"
    desc: "+37; Darkvision, Lifesense 240 Feet, Truesight"
languages: "Chthonian, Diabolic, Empyrean, Requian; Telepathy 120 feet, Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Athletics: +38, Deception: +34, Diplomacy: +34, Intimidation: +36, Occultism: +38, Religion: +38, Society: +38, Boneyard Lore: +40, Legal Lore: +40"
abilityMods: [10, 7, 7, 10, 7, 6]
speed: 35 feet,  fly 50 feet,  swim 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +33, __Ref__ +31, __Will__ +35; +1 status to all saves vs. magic"
hp: 375
health:
  - name: ""
  - name: HP
    desc: "375, fast healing 20, lightning drinker; __Immunities__  death effects,  disease,  electricity; __Resistances__ void 20, poison 20"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 120 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 240 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 20]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet DC 39 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Lightning Drinker"
    desc: "  Whenever a yamaraj would take electricity damage if not for its immunity, its fast healing increases to 40 on its next turn.\n\nDuring that turn, if it uses Beetle Breath, the beetles deal 2d12 additional electricity damage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (magical, reach 15 feet)\n__Damage__  4d8 + 18 piercing plus improved-grab,spirit-touch,yamaraj-venom"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, magical, reach 15 feet)\n__Damage__  4d4 + 18 slashing plus spirit-touch"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+38 (magical, reach 20 feet)\n__Damage__  4d10 + 18 bludgeoning plus spirit-touch"

  - name: "Divine Innate Spells"
    desc: "DC 44, attack +36; __10th __ (1 slots) _[[Spells/Manifestation|Manifestation]]_, _[[Spells/Revival|Revival]]_; __9th __ (4 slots) _[[Spells/Harm|Harm]]_, _[[Spells/Heal|Heal]]_, _[[Spells/Seize Soul|Seize Soul]]_, _[[Spells/Spirit Blast|Spirit Blast]]_, _[[Spells/Wails of the Damned|Wails of the Damned]]_; __8th __ (8 slots) _[[Spells/Chain Lightning|Chain Lightning (x3)]]_, _[[Spells/Dispel Magic|Dispel Magic (x3)]]_, _[[Spells/Wall of Force|Wall of Force]]_; __5th __ (2 slots) _[[Spells/Mind Probe|Mind Probe (At will)]]_, _[[Spells/Translocate|Translocate (At will)]]_\n__Constant__  __(10th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "Rituals"
    desc: "_Call Spirit_, _Resurrect_"

  - name: "Beetle Breath"
    desc: "`pf2:2` (divine) The yamaraj breathes a blast of beetles in a 50-foot cone that deals 14d8 slashing damage and 4d8 persistent slashing damage to creatures in the area with a DC 42 Reflex check save.\n\nIt can't use Beetle Breath again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage and is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature takes full damage and is [[Conditions/Sickened|Sickened 2]].\n\n**Critical Failure** The creature takes double damage and is [[Conditions/Sickened|Sickened 3]]."

  - name: "Final Judgment"
    desc: "  A yamaraj's [[Spells/Manifestation|Manifestation]] spells are used only to pronounce judgment, typically either to restore a dead or destroyed creature to life, bind a creature to the Boneyard, or banish a creature from the Boneyard."

  - name: "Shepherd's Touch"
    desc: " (incorporeal) A yamaraj's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 3d6 void damage to living creatures and 3d6 vitality damage to undead."

  - name: "Yamaraj Venom"
    desc: " (poison) While a creature is clumsy from this poison, it is [[Conditions/Doomed|Doomed]] with the same value;\n\n**Saving Throw** DC 42 Fortitude check\n* * *\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 3d8 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 5d8 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** 7d8 poison damage and [[Conditions/Clumsy|Clumsy 3]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Yamaraj
creatures:
  - 1: Yamaraj
```



The greatest judges among the psychopomps are yamarajes, whose wisdom is legendary and whose edicts are unappealable except to ushers or Pharasma herself. A yamaraj resembles an immense dragon with dark, feathery scales and an emotionless, dispassionate gaze behind a feathered mask. When not serving as the senior magistrates, lords, and generals of the Boneyard, yamarajes pursue highly individualistic hobbies, such as gardening or literature.

* * *

Psychopomps are guardians and shepherds of the dead in the Boneyard, the vast plane of graves where mortal souls are judged and sent on to their eternal rewards or damnations. Psychopomps ensure that the dead come to terms with their transition from mortality and are properly sorted into the appropriate afterlife. They also protect souls from being preyed upon by supernatural predators. Nearly all psychopomps wear masks, especially when they're likely to be interacting with mortals, although the types of masks they wear are as varied as the psychopomps themselves. The courts of the Boneyard preside in Requian, a somber yet melodic language spoken slowly with various tonal shifts.

Many psychopomps are intimately involved with the Boneyard's massive bureaucracy. Few pursue mercy, justice, or personal gain; their duties to Pharasma and her Boneyard are supreme. Nevertheless, individual psychopomps interpret their duties in different ways, which might put them in conflict with mortals or even with each other.
