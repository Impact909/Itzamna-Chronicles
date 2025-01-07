---
title: "Wild Hunt Monarch"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MhdhndZemJPSm4HK" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/wild-hunt
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Wild Hunt Monarch"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Wild Hunt Monarch"
level: "Creature 20"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[wild-hunt]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Greater Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common, Draconic, Fey; speak with animals; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +38, Diplomacy: +36, Intimidation: +40, Nature: +36, Performance: +36, Stealth: +37, Survival: +37"
abilityMods: [10, 6, 7, 6, 7, 10]
speed: 40 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 46
armorclass:
  - name: AC
    desc: "46; __Fort__ +33, __Ref__ +32, __Will__ +35"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450; __Weaknesses__ cold iron 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Glaive|Glaive]], Monarch's Horn"
  - name: "Greensight"
    desc: "  The wild hunt monarch ignores the [[Conditions/Concealed|Concealed]] condition from leaves and other foliage, mist, and fog."

  - name: "Planar Acclimation"
    desc: "  The wild hunt monarch treats the plane it is located on as its home plane."

  - name: "Wild Hunt Link"
    desc: " (aura,magical) 1 mile. A wild hunt monarch increases the range of wild hunt link to affect all wild hunt members within a mile. Other wild hunt creatures in this link who end their turn within 60 feet of a wild hunt monarch gain regeneration 50 until the end of their next turn; this regeneration can only be deactivated by forcing the wild hunt out of the 60-foot aura or by killing the wild hunt monarch."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Instinctive Cooperation"
    desc: "  The wild hunt monarch automatically achieves a critical success on saving throws against effects created by other allied wild hunt creatures."

  - name: "Wild Gaze"
    desc: " (aura,fear,incapacitation,mental,primal,visual) 30 feet. Those who meet the gaze of a wild hunt monarch come face-to-face with the hunt's fearful power and find it difficult to act in the face of such a legendary legacy. When a creature ends its turn in the aura, it must succeed at a DC 39 Will check save to resist becoming [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure). The wild hunt monarch can deactivate or activate this aura by using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Glaive"
    desc: "+38 (deadly d8, forceful, magical, reach 10 feet)\n__Damage__  1d6 sonic 1d6 bleed 4d8 + 20 slashing"

  - name: "**Melee** `pf2:1` Horns"
    desc: "+38 (agile, magical)\n__Damage__  4d8 + 20 piercing plus brutal-gore"

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +32; __10th __  _[[Spells/Primal Phenomenon|Primal Phenomenon]]_; __9th __  _[[Spells/Dispel Magic|Dispel Magic]]_, _[[Spells/Dominate|Dominate]]_, _[[Spells/Execute|Finger of Death]]_; __8th __  _[[Spells/Charm|Charm]]_, _[[Spells/Suggestion|Suggestion]]_, _[[Spells/Migration|Wind Walk]]_; __7th __  _[[Spells/Mirage|Hallucinatory Terrain]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_; __6th __  _[[Spells/Speak with Stones|Stone Tell]]_\n__Cantrips__  __(10th)__ _[[Spells/Electric Arc|Electric Arc]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Know the Way|Know Direction]]_, _[[Spells/Produce Flame|Produce Flame]]_\n__Constant__  __(10th)__ _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Rituals"
    desc: "_Control Weather_, _Primal Call (Creatures with the Wild Hunt Trait Only)_"

  - name: "Brutal Gore"
    desc: "  A creature critically hit by a monarch's horns strike is [[Conditions/Stunned|Stunned 1]]."

  - name: "Call Glaive"
    desc: "`pf2:1` (primal,teleportation) The wild hunt monarch wields a magic weapon known as a monarch's glaive. This weapon functions as a _+3 major striking greater thundering wounding glaive_ in the monarch's hands only. The monarch can call their glaive to their hands using this action, transporting it across any distance. If their glaive is destroyed, the monarch can create a new one by using Call Glaive as a three-action activity that gains the manipulate trait."

  - name: "Call to the Hunt"
    desc: "`pf2:3` (manipulate,primal,teleportation) **Frequency** once per day\n\n**Effect** The wild hunt monarch blows their monarch's horn, causing two wild hunt scouts or four wild hunt archers part of the monarch's wild hunt link and no more than 1 mile from the monarch's location to appear as the monarch chooses at any point within 30 feet. They act immediately before the wild hunt monarch in initiative starting on the next round."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,fear,incapacitation,mental,primal,visual) The wild hunt monarch fixes its glare at a creature it can see within 30 feet. The target must immediately attempt a Will save against the wild hunt hound's wild gaze. If the creature was already slowed by the wild gaze before attempting its save, a failed save causes it to be [[Conditions/Paralyzed|Paralyzed]] for 1 round. After attempting its save, the creature is temporarily immune to Focus Gaze from any wild hunt until the start of the wild hunt monarch's next turn."

  - name: "Wild Reincarnation"
    desc: "`pf2:r` (primal) **Trigger** The wild hunt monarch kills an adjacent non-fey creature.\n\n**Effect** The wild hunt monarch attempts to reincarnate the creature as a fey. The slain creature must attempt a DC 42 Fortitude check save, and it takes a -2 status penalty to this save if it was under any enchantment effect placed by the monarch when it died.\n* * *\n\n**Critical Success** The creature is instead restored to life as if via [[Spells/Raise Dead|Raise Dead]] (heightened to 10th level), and it is permanently immune to Wild Reincarnation from that wild hunt monarch.\n\n**Success** The creature is not reincarnated and remains dead.\n\n**Failure** The creature is temporarily reincarnated as a fey creature of the monarch's choice. The new fey must be of a level equal to or less than the dead creature's level, and it functions in all ways as that fey creature; it retains none of the abilities and only scatterings of the memories or personality of the reincarnated character, and it follows the commands and orders of the wild hunt monarch. After 1 minute, the reincarnated fey dies and its body reverts back to its original corpse, which can then be restored to life normally.\n\n**Critical Failure** As failure, but the reincarnated fey remains alive until slain; a [[Spells/Miracle|Miracle]], [[Spells/Wish|Wish]] or similarly powerful spell or effect can reverse the reincarnation as well."
 
```

```encounter-table
name: Wild Hunt Monarch
creatures:
  - 1: Wild Hunt Monarch
```



Each wild hunt follows a wild hunt monarch, who travels between the realm of the fey and the Material Plane in search of new quarry. These limber and regal humanoids have elk antlers, long pointed ears, flowing white hair, and luminescent green eyes.

* * *

Although some believe the wild hunt is nothing more than legend, the riders of the wild hunt are real. Countless members of these fey compose the wild hunt-the term "wild hunt" refers to the family of creatures as a whole as well as to individual groups of these fey who gather to pursue their quarry.

Wild hunt monarchs set the terms of each specific hunt, depending upon the prey and their own whims. The easier the prey, the more likely a monarch is to impose rules to make the hunt more entertaining, such as forbidding anyone but their hounds from injuring the quarry, or holding back their forces to give the target creature time to rest and recover.

While most missions come from rumors gathered by a wild hunt monarch, monarchs occasionally consider proposals from the few who are brave and knowledgeable enough to seek them out. They accept tasks only from sources they deem worthy, and the payments they demand for their services vary significantly, though they have no interest in material wealth. Wild hunt monarchs take grave offense at unfavorable deals. Those who attempt to cheat a monarch often become the enraged fey's next target.
