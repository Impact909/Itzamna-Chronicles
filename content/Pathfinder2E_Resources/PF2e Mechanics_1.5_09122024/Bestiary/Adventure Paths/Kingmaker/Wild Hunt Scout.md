---
title: "Wild Hunt Scout"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.usr2DEBrQnwDmHQb" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/wild-hunt
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Wild Hunt Scout"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Wild Hunt Scout"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[wild-hunt]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Greater Darkvision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common, Fey; speak with animals; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +33, Deception: +32, Intimidation: +32, Nature: +29, Stealth: +37, Survival: +34"
abilityMods: [9, 6, 6, 5, 8, 6]
speed: 40 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +28, __Ref__ +30, __Will__ +34"
hp: 380
health:
  - name: ""
  - name: HP
    desc: "380; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "Greensight"
    desc: "  The wild hunt scout ignores the [[Conditions/Concealed|Concealed]] condition from leaves and other foliage."

  - name: "Planar Acclimation"
    desc: "  The wild hunt scout treats the plane it is located on as its home plane."

  - name: "Wild Hunt Link"
    desc: " (aura,magical) 500 feet. A wild hunt scout grants other wild hunt creatures the scout's [[Class Features/Deny Advantage|Deny Advantage]]."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Instinctive Cooperation"
    desc: "  The wild hunt scout automatically achieves a critical success on saving throws against effects created by other allied wild hunt creatures."

  - name: "Wild Gaze"
    desc: " (aura,fear,incapacitation,mental,primal,visual) 30 feet. Those who meet the gaze of a wild hunt scout come face-to-face with the hunt's fearful power and find it difficult to act in the face of such a legendary legacy. When a creature ends its turn in the aura, it must succeed at a DC 37 Will check save to resist becoming [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure). The wild hunt scout can deactivate or activate this aura by using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Crystal Scimitar"
    desc: "+35 (forceful, magical, sweep)\n__Damage__  3d6 + 17 slashing 2d6 force"

  - name: "**Ranged** `pf2:1` Emerald Beam"
    desc: "+34 (range 40 feet)\n__Damage__ "

  - name: "Primal Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Unfettered Pack|Unfettered Pack]]_; __8th __  _[[Spells/Disappearance|Disappearance]]_, _[[Spells/Migration|Wind Walk]]_; __7th __  _[[Spells/Force Barrage|Magic Missile]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_; __6th __  _[[Spells/Speak with Stones|Stone Tell]]_; __5th __  _[[Spells/Translocate|Dimension Door (x3)]]_, _[[Spells/Force Barrage|Magic Missile]]_\n__Cantrips__  __(9th)__ _[[Spells/Know the Way|Know Direction]]_\n__Constant__  __(9th)__ _[[Spells/Vanishing Tracks|Pass Without Trace]]_, _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Befuddle"
    desc: " (mental,primal) A wild hunt scout can emit a beam of emerald light from their crystal shard to attempt an emerald beam ranged Strike. If the beam hits, it inflicts no damage (nor does it inflict precision damage from a sneak attack), but it overstimulates the target's mind, causing them to become [[Conditions/Dazzled|Dazzled]] and [[Conditions/Off-Guard|Off-Guard]] for 1 round. On a critical hit, the target is also [[Conditions/Blinded|Blinded]] for 1 round."

  - name: "Deny Advantage"
    desc: "  A wild hunt scout isn't [[Conditions/Off-Guard|Off-Guard]] to [[Conditions/Hidden|Hidden]], [[Conditions/Undetected|Undetected]], or flanking creatures of your level or lower, or creatures of their level or lower using [[Class Features/Surprise Attack|Surprise Attack]]. However, they can still help their allies flank."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,fear,incapacitation,mental,primal,visual) The wild hunt scout fixes its glare at a creature it can see within 30 feet. The target must immediately attempt a Will save against the wild hunt hound's wild gaze. If the creature was already slowed by the wild gaze before attempting its save, a failed save causes it to be [[Conditions/Paralyzed|Paralyzed]] for 1 round. After attempting its save, the creature is temporarily immune to Focus Gaze from any wild hunt until the start of the wild hunt scout's next turn."

  - name: "Forceful Focus"
    desc: "`pf2:3` (concentrate) **Requirement** The wild hunt scout cast magic missile the previous round.\n\n**Effect** The wild hunt scout focuses on their mastery of force, standing still as they become swathed in pulsing emerald light. Any magic missile innate spells they have cast that day are restored, allowing them to be cast again. Until the end of their next turn, any creature that takes force damage from the wild hunt scout must succeed at a DC 40 Fortitude check save or be [[Conditions/Stunned|Stunned 1]] ([[Conditions/Stunned|Stunned 3]] on a critical failure). The wild hunt scout can't use forceful focus for 1 hour."

  - name: "Manifest Crystals"
    desc: "  A wild hunt scout can manifest a _+2 greater striking scimitar_ made of crystalized force or a fist-sized shard of the same in her hands. These objects vanish upon the wild hunt scout's death, or as soon as they no longer possess the items."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  A wild hunt scout's Strikes deal 3d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Wild Hunt Scout
creatures:
  - 1: Wild Hunt Scout
```



These compact few have pointed ears, green eyes, and ram's horns. They relish the chance to seek revenge upon those who have wronged or insulted the wild hunt, but they tend to grow bored when the stakes aren't lethal.

* * *

Although some believe the wild hunt is nothing more than legend, the riders of the wild hunt are real. Countless members of these fey compose the wild hunt-the term "wild hunt" refers to the family of creatures as a whole as well as to individual groups of these fey who gather to pursue their quarry.

Wild hunt monarchs set the terms of each specific hunt, depending upon the prey and their own whims. The easier the prey, the more likely a monarch is to impose rules to make the hunt more entertaining, such as forbidding anyone but their hounds from injuring the quarry, or holding back their forces to give the target creature time to rest and recover.

While most missions come from rumors gathered by a wild hunt monarch, monarchs occasionally consider proposals from the few who are brave and knowledgeable enough to seek them out. They accept tasks only from sources they deem worthy, and the payments they demand for their services vary significantly, though they have no interest in material wealth. Wild hunt monarchs take grave offense at unfavorable deals. Those who attempt to cheat a monarch often become the enraged fey's next target.
