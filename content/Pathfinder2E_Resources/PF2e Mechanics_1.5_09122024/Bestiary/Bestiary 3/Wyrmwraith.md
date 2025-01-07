---
title: "Wyrmwraith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hKfqofxTkV30NcFY" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wraith
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Wyrmwraith"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Wyrmwraith"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[incorporeal]]
trait_05: [[undead]]
trait_06: [[unholy]]
trait_07: [[wraith]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Lifesense 120 Feet"
languages: "Common, Draconic, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Arcana: +30, Intimidation: +33, Religion: +33, Stealth: +33"
abilityMods: [-5, 9, 0, 7, 7, 9]
speed: 50 feet,  fly 80 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +29, __Ref__ +32, __Will__ +32"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  precision; __Resistances__ all damage 20 (except force, ghost touch, or vitality)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 120 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 33 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Positive Energy Transfer"
    desc: "`pf2:r` (divine) **Trigger** The wyrmwraith succeeds at a saving throw to resist vitality damage but still takes damage\n* * *\n\n**Effect** The wyrmwraith transfers all vitality damage from the effect to a single undead creature of their choice within 120 feet that they control or that's [[Conditions/Friendly|Friendly]] or [[Conditions/Helpful|Helpful]] to them."

  - name: "Sunlight Powerlessness"
    desc: "  A wyrmwraith in sunlight is [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Stunned|Stunned 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spectral Jaws"
    desc: "+34 (reach 20 feet)\n__Damage__  3d12 + 17 void plus drain-life"

  - name: "**Melee** `pf2:1` Spectral Claw"
    desc: "+34 (agile, reach 15 feet)\n__Damage__  3d8 + 17 void plus divine-dispelling,drain-life"

  - name: "Divine Innate Spells"
    desc: "DC 35, attack +27; __8th __  _[[Spells/Charm|Charm (Undead Only)]]_; __7th __  _[[Spells/Divine Wrath|Divine Wrath (x3)]]_, _[[Spells/Execute|Finger of Death]]_; __6th __  _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __4th __  _[[Spells/Charm|Charm (Undead Only) (x3)]]_, _[[Spells/Darkness|Darkness]]_; __3rd __  _[[Spells/Bind Undead|Bind Undead (At Will)]]_"

  - name: "Rituals"
    desc: "_Create Undead_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (divine,void) The wyrmwraith unleashes a burst of void energy that deals 18d6 void damage to all creatures in a 60-foot cone (DC 38 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds."

  - name: "Divine Dispelling"
    desc: " (divine) A wyrmwraith's claws rend divine magic. Whenever a wyrmwraith hits a creature with a spectral claws Strike, the wyrmwraith can attempt a Religion check check to counteract an ongoing divine spell effect on the creature."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The wyrmwraith makes two claw Strikes and one jaws Strike in any order."

  - name: "Drain Life"
    desc: " (divine) When a wyrmwraith deals damage to a living creature with a spectral jaws or spectral claw Strike, the wyrmwraith gains 18 temporary Hit Points, and the creature must succeed at a DC 38 Fortitude check save or become [[Conditions/Drained|Drained 2]]. Further damage dealt by the wyrmwraith's spectral jaws or spectral claws Strikes increases the value of the drained condition by 2 on a failed save, to a maximum of drained 4."

  - name: "Ectoplasmic Form"
    desc: "`pf2:1` (divine) A wyrmwraith can push through the ectoplasmic veil to temporarily assume a physical form made of ectoplasm. The wyrmwraith loses the incorporeal trait for 1d4 rounds, though they can return to their incorporeal form as a free action before then. Once this ability ends, the wyrmwraith can't use this ability again for 1d4 rounds. While in their ectoplasmic form, the wyrmwraith's AC increases to 43 and they gain 100 temporary Hit Points. They lose their immunity to precision damage and all of their resistances. Their melee Strikes deal slashing and piercing damage, respectively, instead of void damage.\n\n[[Bestiary Effects/Effect_ Ectoplasmic Form (Physical)|Effect: Ectoplasmic Form (Physical)]]"

  - name: "Phase Lurch"
    desc: "`pf2:1` (divine,move) **Requirements** The wyrmwraith is in their ectoplasmic form\n* * *\n\n**Effect** As the Stride action, but the wyrmwraith can pass through walls or material obstacles as though they were incorporeal. They must begin and end their movement outside of any physical obstacles, and passing through solid material is difficult terrain."
 
```

```encounter-table
name: Wyrmwraith
creatures:
  - 1: Wyrmwraith
```



Though they refused to accept death, wyrmwraiths nonetheless despise their new undead condition. Indeed, lacking in all motivation to collect treasure, a wyrmwraith instead fixates on their hatred of all living things (especially dragons) and their own self-loathing. A wyrmwraith blights the land with their very presence, spreading slowly until their lair becomes a lifeless wasteland haunted by other undead.

* * *

Wyrmwraiths rise from the souls of dragons who refuse to accept death or have an irrational fear of the afterlife.
