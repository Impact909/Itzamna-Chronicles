---
title: "Nosoi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nTjNhX38odvlA4lw" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Nosoi"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Nosoi"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision, Lifesense 60 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +6, Performance: +6, Religion: +6, Society: +2, Stealth: +6, Boneyard Lore: +8, Library Lore: +8"
abilityMods: [-1, 3, 1, 1, 1, 3]
speed: 15 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +4, __Ref__ +8, __Will__ +6"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18; __Immunities__  death effects,  disease; __Resistances__ void 3, poison 3"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 60 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+6 (finesse, magical, reach 0 feet)\n__Damage__  1d4 - 1 piercing plus spirit-touch"

  - name: "Divine Innate Spells"
    desc: "DC 16, attack +8; __4th __  _[[Spells/Read Omens|Read Omens]]_, _[[Spells/Talking Corpse|Talking Corpse]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_, _[[Spells/Noise Blast|Noise Blast]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The nosoi takes the appearance of a raven or songbird. This doesn't change its Speed or its attack and damage modifiers with its Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Haunting Melody"
    desc: "`pf2:1` (auditory,concentrate,divine,incapacitation,mental) The nosoi croons an entrancing song. Each living or undead creature within a 60-foot emanation must attempt a DC 18 Will check save. The effect lasts until the end of the nosoi's next turn, but the nosoi can Sustain it. A creature that succeeds at its save is temporarily immune for 24 hours. Despite being a mental effect, this ability affects mindless undead.\n\nPsychopomps are immune to this ability.\n* * *\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]] with the nosoi.\n\n**Critical Failure** The creature is fascinated with the nosoi and must spend each of its actions on its turn to move closer to the nosoi as expediently as possible while avoiding obvious dangers. If a fascinated creature is adjacent to the nosoi, it stays still and doesn't act. If the creature is attacked, the fascination ends."

  - name: "Shepherd's Touch"
    desc: "  A nosoi's Strikes have the benefit of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal an additional 1d6 void damage to living creatures or 1d6 vitality damage to undead."
 
```

```encounter-table
name: Nosoi
creatures:
  - 1: Nosoi
```



A nosoi resembles a whippoorwill, sparrow, or other small bird wearing a heavy leather plague doctor's mask. They are the clerks, messengers, and scribes of the Boneyard, witnessing judgments, directing souls, and generally performing the administrative grunt work that keeps the Boneyard functioning. Most nosois are particularly chatty and eager to discuss how important they consider their individual assignments to be.

* * *

Psychopomps are guardians and shepherds of the dead in the Boneyard, the vast plane of graves where mortal souls are judged and sent on to their eternal rewards or damnations. Psychopomps ensure that the dead come to terms with their transition from mortality and are properly sorted into the appropriate afterlife. They also protect souls from being preyed upon by supernatural predators. Nearly all psychopomps wear masks, especially when they're likely to be interacting with mortals, although the types of masks they wear are as varied as the psychopomps themselves. The courts of the Boneyard preside in Requian, a somber yet melodic language spoken slowly with various tonal shifts.

Many psychopomps are intimately involved with the Boneyard's massive bureaucracy. Few pursue mercy, justice, or personal gain; their duties to Pharasma and her Boneyard are supreme. Nevertheless, individual psychopomps interpret their duties in different ways, which might put them in conflict with mortals or even with each other.
