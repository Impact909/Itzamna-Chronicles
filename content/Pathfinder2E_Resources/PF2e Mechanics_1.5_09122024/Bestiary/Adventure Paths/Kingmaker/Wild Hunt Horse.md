---
title: "Wild Hunt Horse"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gUs116RoVpxMTd2I" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/wild-hunt
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Wild Hunt Horse"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Wild Hunt Horse"
level: "Creature 15"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[wild-hunt]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Greater Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Fey; speak with animals; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +31, Survival: +29"
abilityMods: [8, 4, 6, -1, 6, 4]
speed: 80 feet,  fly 80 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +27, __Ref__ +23, __Will__ +29"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "Greensight"
    desc: "  The wild hunt horse ignores the [[Conditions/Concealed|Concealed]] condition from leaves and other foliage."

  - name: "Planar Acclimation"
    desc: "  The wild hunt horse treats the plane it is located on as its home plane."

  - name: "Wild Hunt Link"
    desc: " (aura,magical) 500 feet. A wild hunt horse grants a +10-foot status bonus to wild hunt creatures' Speed other than wild hunt horses."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Buck|Buck]]"
    desc: "`pf2:r`  DC 36 Reflex check\n* * *\n\nMost monsters that serve as mounts can attempt to buck off unwanted or annoying riders, but most mounts will not use this reaction against a trusted creature unless the mounts are spooked or mistreated.\n\n**Trigger** A creature [[Actions/Mount|Mounts]] or uses the [[Actions/Command an Animal|Command an Animal]] action while riding the monster.\n* * *\n\n**Effect** The triggering creature must succeed at a Reflex saving throw against the listed DC or fall off the creature and land [[Conditions/Prone|Prone]]. If the save is a critical failure, the triggering creature also takes 1d6 bludgeoning damage in addition to the normal damage for the fall."

  - name: "Instinctive Cooperation"
    desc: "  The wild hunt horse automatically achieves a critical success on saving throws against effects created by other allied wild hunt creatures."

  - name: "Rider Synergy"
    desc: "  If the wild hunt horse has a wild hunt rider, damage done to the horse or rider from Strikes is split equally between the two."

  - name: "Wild Gaze"
    desc: " (aura,fear,incapacitation,mental,primal,visual) 30 feet. Those who meet the gaze of a wild hunt horse come face-to-face with the hunt's fearful power and find it difficult to act in the face of such a legendary legacy. When a creature ends its turn in the aura, it must succeed at a DC 33 Will check save to resist becoming [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure). The wild hunt horse can deactivate or activate this aura by using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+30 (agile, magical)\n__Damage__  1d8 bleed 3d10 + 11 bludgeoning"

  - name: "Primal Innate Spells"
    desc: "DC 36, attack +28; __8th __  _[[Spells/Unfettered Movement|Freedom of Movement]]_, _[[Spells/Nature's Pathway|Tree Stride (Self plus Willing Rider)]]_; __6th __  _[[Spells/Speak with Stones|Stone Tell]]_\n__Cantrips__  __(8th)__ _[[Spells/Know the Way|Know Direction]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_\n__Constant__  __(8th)__ _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Bewildering Hoofbeats"
    desc: "`pf2:2` (auditory,aura,emotion,mental,primal) 60 feet. The wild hunt horse stamps its hooves and prances in place, creating the sound of hundreds of horses apparently approaching from all directions. Each creature within 60-foot emanation must attempt a DC 33 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Bewildering Hoofbeats for 1 hour.\n\n**Success** The creature is distracted by the sound. Until the start of the creature's next turn, if it attempts to use a reaction, it must succeed at a DC 5 Flat check or the reaction is disrupted, wasted with no effect.\n\n**Failure** The creature is bewildered by the sound, with the same effects as success except it is also [[Conditions/Confused|Confused]] for 1 round.\n\n**Critical Failure** As failure, but the confusion effect persists for 1 minute or until the creature recovers by other means."

  - name: "Deafening Cry"
    desc: "`pf2:1` (auditory,primal,sonic) The wild hunt horse gives out a thundering cry in a 15-foot cone. Creatures in the area take 16d6 sonic damage (DC 36 Fortitude check, plus [[Conditions/Deafened|Deafened]] for 1 minute on a critical failure). The wild hunt horse can't use Deafening Cry again for 1d4 rounds."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,fear,incapacitation,mental,primal,visual) The wild hunt horse fixes its glare at a creature it can see within 30 feet. The target must immediately attempt a Will save against the wild hunt hound's wild gaze. If the creature was already slowed by the wild gaze before attempting its save, a failed save causes it to be [[Conditions/Paralyzed|Paralyzed]] for 1 round. After attempting its save, the creature is temporarily immune to Focus Gaze from any wild hunt until the start of the wild hunt horse's next turn."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or smaller, Hoof, DC 36 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Wild Hunt Horse
creatures:
  - 1: Wild Hunt Horse
```



These steeds stand upon puffs of air, their grassy manes and tails swishing majestically in the wind. When they are not participating in a hunt, wild hunt horses enjoy constructing complicated courses through land and sky and racing each other for ever-changing stakes.

* * *

Although some believe the wild hunt is nothing more than legend, the riders of the wild hunt are real. Countless members of these fey compose the wild hunt-the term "wild hunt" refers to the family of creatures as a whole as well as to individual groups of these fey who gather to pursue their quarry.

Wild hunt monarchs set the terms of each specific hunt, depending upon the prey and their own whims. The easier the prey, the more likely a monarch is to impose rules to make the hunt more entertaining, such as forbidding anyone but their hounds from injuring the quarry, or holding back their forces to give the target creature time to rest and recover.

While most missions come from rumors gathered by a wild hunt monarch, monarchs occasionally consider proposals from the few who are brave and knowledgeable enough to seek them out. They accept tasks only from sources they deem worthy, and the payments they demand for their services vary significantly, though they have no interest in material wealth. Wild hunt monarchs take grave offense at unfavorable deals. Those who attempt to cheat a monarch often become the enraged fey's next target.
