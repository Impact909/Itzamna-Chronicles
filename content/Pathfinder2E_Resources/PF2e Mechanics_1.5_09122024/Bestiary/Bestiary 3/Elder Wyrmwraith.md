---
title: "Elder Wyrmwraith"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.uNgGvVQJ53wvlMmQ" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wraith
  - pf2eMonster
  - pf2e/creature/level/23
statblock: inline
name: "Elder Wyrmwraith"
level: 23
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Elder Wyrmwraith"
level: "Creature 23"
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
modifier: 40
perception:
  - name: "Perception"
    desc: "+40; Darkvision, Lifesense 120 Feet"
languages: "Common, Draconic, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +38, Arcana: +38, Intimidation: +43, Religion: +43, Stealth: +43"
abilityMods: [-5, 11, 0, 9, 9, 11]
speed: 50 feet,  fly 100 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 49
armorclass:
  - name: AC
    desc: "49; __Fort__ +32, __Ref__ +38, __Will__ +42"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  precision; __Resistances__ all damage 25 (except force, ghost touch, or vitality)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 120 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 46 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Positive Energy Transfer"
    desc: "`pf2:r` (divine) **Trigger** The wyrmwraith succeeds at a saving throw to resist vitality damage but still takes damage\n* * *\n\n**Effect** The wyrmwraith transfers all vitality damage from the effect to a single undead creature of their choice within 120 feet that they control or that's [[Conditions/Friendly|Friendly]] or [[Conditions/Helpful|Helpful]] to them."

  - name: "Sunlight Powerlessness"
    desc: "  An elder wyrmwraith in sunlight is [[Conditions/Clumsy|Clumsy 2]] and [[Conditions/Stunned|Stunned 2]]."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spectral Jaws"
    desc: "+42 (reach 20 feet)\n__Damage__  4d12 + 23 void plus drain-life"

  - name: "**Melee** `pf2:1` Spectral Claw"
    desc: "+42 (agile, reach 15 feet)\n__Damage__  4d8 + 23 acid plus divine-dispelling,drain-life"

  - name: "Divine Innate Spells"
    desc: "DC 46, attack +38; __10th __  _[[Spells/Miracle|Miracle]]_; __8th __  _[[Spells/Charm|Charm (Undead Only)]]_; __7th __  _[[Spells/Divine Wrath|Divine Wrath (x3)]]_, _[[Spells/Execute|Finger of Death]]_; __6th __  _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination]]_; __4th __  _[[Spells/Charm|Charm (Undead Only) (x3)]]_, _[[Spells/Darkness|Darkness]]_; __3rd __  _[[Spells/Bind Undead|Bind Undead (At Will)]]_"

  - name: "Rituals"
    desc: "_Create Undead_, _Imprisonment_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (divine,void) The elder wyrmwraith unleashes a burst of void energy that deals 24d6 void damage to all creatures in a 90-foot cone (DC 46 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds."

  - name: "Consume Souls"
    desc: "`pf2:2` (death,divine,incapacitation) The elder wyrmwraith inhales sharply, sucking in the souls of nearby creatures. Each creature in a 60-foot cone must attempt a DC 46 Will check save.\n\nThe elder wyrmwraith can't Consume Souls again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature becomes [[Conditions/Doomed|Doomed 1]].\n\n**Failure** The creature becomes [[Conditions/Doomed|Doomed 2]] and takes 100 void damage.\n\n**Critical Failure** The creature is slain. As long as the wyrmwraith still exists, the slain creature can't be returned to life through any means."

  - name: "Divine Dispelling"
    desc: " (divine) An elder wyrmwraith's claws rend divine magic. Whenever an elder wyrmwraith hits a creature with a spectral claws Strike, the elder wyrmwraith can attempt a Religion check check to counteract an ongoing divine spell effect on the creature."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The elder wyrmwraith makes two claw Strikes and one jaws Strike in any order."

  - name: "Drain Life"
    desc: " (divine) When an elder wyrmwraith deals damage to a living creature with a spectral jaws or spectral claw Strike, the elder wyrmwraith gains 24 temporary Hit Points, and the creature must succeed at a DC 46 Fortitude check save or become [[Conditions/Drained|Drained 2]]. Further damage dealt by the elder wyrmwraith's spectral jaws or spectral claws Strikes increases the value of the drained condition by 2 on a failed save, to a maximum of drained 4."

  - name: "Ectoplasmic Form"
    desc: "`pf2:1` (divine) An elder wyrmwraith can push through the ectoplasmic veil to temporarily assume a physical form made of ectoplasm. The elder wyrmwraith loses the incorporeal trait for 1d4 rounds, though they can return to their incorporeal form as a free action before then. Once this ability ends, the elder wyrmwraith can't use this ability again for 1d4 rounds. While in their ectoplasmic form, the elder wyrmwraith's AC increases to 52 and they gain 125 temporary Hit Points. They lose their immunity to precision damage and all of their resistances. Their melee Strikes deal slashing and piercing damage, respectively, instead of void damage.\n\n[[Bestiary Effects/Effect_ Ectoplasmic Form (Physical)|Effect: Ectoplasmic Form (Physical)]]"

  - name: "Phase Lurch"
    desc: "`pf2:1` (divine,move) **Requirements** The wyrmwraith is in their ectoplasmic form\n* * *\n\n**Effect** As the Stride action, but the wyrmwraith can pass through walls or material obstacles as though they were incorporeal. They must begin and end their movement outside of any physical obstacles, and passing through solid material is difficult terrain."
 
```

```encounter-table
name: Elder Wyrmwraith
creatures:
  - 1: Elder Wyrmwraith
```



The most powerful of these monsters, elder wyrmwraiths, sometimes form spontaneously from legendary dragons haunted by an irrational fear of the afterlife, but most have simply existed for over a thousand years, growing in power all the while.

* * *

Wyrmwraiths rise from the souls of dragons who refuse to accept death or have an irrational fear of the afterlife.
