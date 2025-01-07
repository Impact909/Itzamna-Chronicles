---
title: "Wild Hunt Hound"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.AA8yBtWsiyqqBjl0" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/fey
  - pf2e/creature/type/wild-hunt
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Wild Hunt Hound"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Wild Hunt Hound"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[fey]]
trait_03: [[wild-hunt]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Greater Darkvision, Scent (Imprecise) 30 Feet, See the Unseen"
languages: "Common, Fey; speak with animals; speak with plants"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +29, Stealth: +26, Survival: +27"
abilityMods: [7, 4, 5, 1, 5, 4]
speed: 50 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +27, __Ref__ +24, __Will__ +25"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "Greensight"
    desc: "  The wild hunt hound ignores the [[Conditions/Concealed|Concealed]] condition from leaves and other foliage."

  - name: "Planar Acclimation"
    desc: "  The wild hunt hound treats the plane it is located on as its home plane."

  - name: "Wild Hunt Link"
    desc: " (aura,magical) 500 feet. A wild hunt hound grants all other members of the wild hunt in the aura except wild hunt hounds the effects of its constant [[Spells/See the Unseen|See the Unseen]] innate spell."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Instinctive Cooperation"
    desc: "  The wild hunt hound automatically achieves a critical success on saving throws against effects created by other allied wild hunt creatures."

  - name: "Wild Gaze"
    desc: " (aura,fear,incapacitation,mental,primal,visual) 30 feet. Those who meet the gaze of a wild hunt hound come face-to-face with the hunt's fearful power and find it difficult to act in the face of such a legendary legacy. When a creature ends its turn in the aura, it must succeed at a DC 31 Will check save to resist becoming [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure). The wild hunt hound can deactivate or activate this aura by using a single action, which has the concentrate trait."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+29 (agile, magical)\n__Damage__  3d10 + 11 piercing plus knockdown"

  - name: "Primal Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Dispel Magic|Dispel Magic]]_; __6th __  _[[Spells/Speak with Stones|Stone Tell]]_; __5th __  _[[Spells/Locate|Locate (x3)]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Know the Way|Know Direction]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_\n__Constant__  __(7th)__ _[[Spells/See the Unseen|See Invisibility]]_, _[[Spells/Speak with Animals|Speak with Animals]]_, _[[Spells/Speak with Plants|Speak with Plants]]_"

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,fear,incapacitation,mental,primal,visual) The wild hunt hound fixes its glare at a creature it can see within 30 feet. The target must immediately attempt a Will save against the wild hunt hound's wild gaze. If the creature was already slowed by the wild gaze before attempting its save, a failed save causes it to be [[Conditions/Paralyzed|Paralyzed]] for 1 round. After attempting its save, the creature is temporarily immune to Focus Gaze from any wild hunt until the start of the wild hunt hound's next turn."

  - name: "Summon Pack"
    desc: "`pf2:2` (aura,primal) **Frequency** once per day\n\n**Effect** With a howl, the wild hunt hound summons a fog that manifests into several misty hounds. These foggy hounds shift and race and howl in a 20-foot emanation [[Bestiary Ability Glossary/Aura|Aura]] as long as the wild hunt hound Sustains the effect. While the hounds seem to be made of fog, their teeth are very real, and any creature that ends its turn in this aura takes 6d6 piercing damage from numerous bites (DC 31 Reflex check)."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Wild Hunt Hound
creatures:
  - 1: Wild Hunt Hound
```



Wild hunt hounds are intelligent hunters and expert trackers that take the lead against elusive prey. Left to their own devices, they seek out creatures that are notoriously difficult to track. They are always surrounded with green mist composed of fragments of the spirits of the wild hunt's victims, a mystic fog that forms itself into a spectral pack to fight at its side.

* * *

Although some believe the wild hunt is nothing more than legend, the riders of the wild hunt are real. Countless members of these fey compose the wild hunt-the term "wild hunt" refers to the family of creatures as a whole as well as to individual groups of these fey who gather to pursue their quarry.

Wild hunt monarchs set the terms of each specific hunt, depending upon the prey and their own whims. The easier the prey, the more likely a monarch is to impose rules to make the hunt more entertaining, such as forbidding anyone but their hounds from injuring the quarry, or holding back their forces to give the target creature time to rest and recover.

While most missions come from rumors gathered by a wild hunt monarch, monarchs occasionally consider proposals from the few who are brave and knowledgeable enough to seek them out. They accept tasks only from sources they deem worthy, and the payments they demand for their services vary significantly, though they have no interest in material wealth. Wild hunt monarchs take grave offense at unfavorable deals. Those who attempt to cheat a monarch often become the enraged fey's next target.
