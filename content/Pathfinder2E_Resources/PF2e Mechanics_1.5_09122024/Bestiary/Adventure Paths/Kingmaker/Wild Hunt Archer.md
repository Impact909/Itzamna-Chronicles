---
title: "Wild Hunt Archer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.3n3TLe9AphB6tbOj" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/wild-hunt
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Wild Hunt Archer"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Wild Hunt Archer"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[wild-hunt]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Greater Darkvision, Scent (Imprecise) 30 Feet, Truesight"
languages: "Aklo, Common, Fey; speak with animals; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +30, Intimidation: +32, Nature: +27, Stealth: +32, Survival: +30"
abilityMods: [6, 8, 6, 3, 6, 6]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +26, __Ref__ +32, __Will__ +28"
hp: 340
health:
  - name: ""
  - name: HP
    desc: "340; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Composite Longbow|Living Bow]], [[Equipment/Leather Armor|+2 Resilient Leather Armor]]"
  - name: "Greensight"
    desc: "  The wild hunt archer ignores the [[Conditions/Concealed|Concealed]] condition from leaves and other foliage."

  - name: "Planar Acclimation"
    desc: "  The wild hunt archer treats the plane it is located on as its home plane."

  - name: "Wild Hunt Link"
    desc: " (aura,magical) 500 feet. A wild hunt archer grants wild hunt other than archers the ability to target [[Conditions/Concealed|Concealed]] creatures with ranged Strikes without having to succeed at a DC 5 Flat check."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Instinctive Cooperation"
    desc: "  The wild hunt archer automatically achieves a critical success on saving throws against effects created by other allied wild hunt creatures."

  - name: "Wild Gaze"
    desc: " (aura,fear,incapacitation,mental,primal,visual) 30 feet. Those who meet the gaze of a wild hunt archer come face-to-face with the hunt's fearful power and find it difficult to act in the face of such a legendary legacy. When a creature ends its turn in the aura, it must succeed at a DC 34 Will check save to resist becoming [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure). The wild hunt archer can deactivate or activate this aura by using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Horns"
    desc: "+30 (agile, magical)\n__Damage__  3d12 + 12 piercing"

  - name: "**Ranged** `pf2:1` Living Bow"
    desc: "+32 (deadly d10, magical, propulsive, range 100 feet, volley 30 ft.)\n__Damage__  1d6 cold 3d8 + 12 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Disintegrate|Disintegrate]]_, _[[Spells/Polar Ray|Polar Ray]]_; __7th __  _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Eclipse Burst|Eclipse Burst]]_, _[[Spells/Execute|Finger of Death]]_, _[[Spells/Vampiric Feast|Vampiric Touch (x3)]]_, _[[Spells/Wall of Ice|Wall of Ice]]_; __6th __  _[[Spells/Speak with Stones|Stone Tell]]_\n__Cantrips__  __(8th)__ _[[Spells/Know the Way|Know Direction]]_\n__Constant__  __(8th)__ _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,fear,incapacitation,mental,primal,visual) The wild hunt archer fixes its glare at a creature it can see within 30 feet. The target must immediately attempt a Will save against the wild hunt hound's wild gaze. If the creature was already slowed by the wild gaze before attempting its save, a failed save causes it to be [[Conditions/Paralyzed|Paralyzed]] for 1 round. After attempting its save, the creature is temporarily immune to Focus Gaze from any wild hunt until the start of the wild hunt archer's next turn."

  - name: "Infuse Arrow"
    desc: "`pf2:3` (magical) The wild hunt archer Casts a Spell with a range of touch and then makes a ranged Strike with their living bow. If they hit a creature with that Strike, that creature is also targeted by the spell's effects. If the Strike misses, the spell is wasted.\n\nAlternatively, the wild hunt archer can [[Actions/Cast a Spell|Cast a Spell]] that affects an area and then make a ranged Strike with their living bow. If they hit a creature with that Strike, the spell takes effect centered on that creature, and the creature struck takes a -2 circumstance penalty to any save against the spell's effect. If the Strike misses, the spell is wasted."

  - name: "Living Bow"
    desc: " (primal) The wild hunt archer carries a manifestation of their archery in the form of a living bow. This weapon functions as a _+2 greater striking frost composite longbow_ as long as it is wielded by the wild hunt archer, but in any other creature's hands the living bow functions as a normal, nonmagic composite longbow. A wild hunt archer can manifest a replacement living bow if its previous one is lost or destroyed by performing a one-minute activity that has the concentrate trait. A living bow appears to be made of wood and constantly sprouts leaves that turn autumnal colors and drop away; it's bowstring is a glowing green line of energy. A wild hunt archer spontaneously generates arrows as needed from its quiver when using a living bow."

  - name: "Seeking Shots"
    desc: "  The wild hunt archer's ranged Strikes and spells with ranged attack rolls ignore their target's [[Conditions/Concealed|Concealed]] condition."
 
```

```encounter-table
name: Wild Hunt Archer
creatures:
  - 1: Wild Hunt Archer
```



These lithe, androgynous humanoids have pointed ears, glowing green eyes, and hair that flows softly at all times as if in a gentle breeze. They are methodical hunters who fire their bows with uncanny accuracy. Since wild hunt archers tend to be slower on foot than most of their companions, they often rely on wild hunt horses to provide increased mobility. Rather than carrying normal arrows, they can produce arrows as needed from magical quivers-these quivers do not function in this manner for anyone other than wild hunt archers.

* * *

Although some believe the wild hunt is nothing more than legend, the riders of the wild hunt are real. Countless members of these fey compose the wild hunt-the term "wild hunt" refers to the family of creatures as a whole as well as to individual groups of these fey who gather to pursue their quarry.

Wild hunt monarchs set the terms of each specific hunt, depending upon the prey and their own whims. The easier the prey, the more likely a monarch is to impose rules to make the hunt more entertaining, such as forbidding anyone but their hounds from injuring the quarry, or holding back their forces to give the target creature time to rest and recover.

While most missions come from rumors gathered by a wild hunt monarch, monarchs occasionally consider proposals from the few who are brave and knowledgeable enough to seek them out. They accept tasks only from sources they deem worthy, and the payments they demand for their services vary significantly, though they have no interest in material wealth. Wild hunt monarchs take grave offense at unfavorable deals. Those who attempt to cheat a monarch often become the enraged fey's next target.
