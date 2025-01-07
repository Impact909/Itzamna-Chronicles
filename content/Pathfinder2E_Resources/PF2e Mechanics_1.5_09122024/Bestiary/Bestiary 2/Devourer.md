---
title: "Devourer"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WTfN3QH9dESWGRkI" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Devourer"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Devourer"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Chthonian, Common, Diabolic, Empyrean, Necril"
skills:
  - name: "Skills"
    desc: "Arcana: +21, Deception: +21, Intimidation: +23, Occultism: +23, Stealth: +19"
abilityMods: [7, 3, 5, 5, 4, 5]
speed: 30 feet,  fly 30 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +20, __Ref__ +18, __Will__ +24; +1 status to all saves vs. magic"
hp: 175
health:
  - name: ""
  - name: HP
    desc: "175, (void healing); __Immunities__  death effects,  disease,  paralyzed,  poison,  spell deflection,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Spell Deflection"
    desc: " (divine,mental) A spellcaster who targets a devourer with a mental spell, [[Spells/Banishment|Banishment]], [[Spells/Seize Soul|Seize Soul]], [[Spells/Divine Decree|Divine Decree]], [[Spells/Divine Wrath|Divine Wrath]], [[Spells/Possession|Possession]], [[Spells/Spirit Blast|Spirit Blast]], or [[Spells/Spirit Song|Spirit Song]] can attempt a counteract check to free a soul the devourer has trapped with Devour Soul. If this counteract attempt succeeds, the trapped soul is released (though the creature remains dead), and the devourer can't use any soul charges from that creature.\n\nDevourers are otherwise immune to these spells."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, reach 10 feet)\n__Damage__  2d10 + 13 slashing plus drain-life"

  - name: "Occult Innate Spells"
    desc: "DC 31, attack +21; __6th __  _[[Spells/Never Mind|Feeblemind]]_, _[[Spells/Truesight|True Seeing]]_; __4th __  _[[Spells/Confusion|Confusion]]_, _[[Spells/Suggestion|Suggestion]]_; __3rd __  _[[Spells/Bind Undead|Bind Undead]]_, _[[Spells/Paralyze|Paralyze]]_; __2nd __  _[[Spells/Death Knell|Death Knell]]_; __1st __  _[[Spells/Harm|Harm]]_"

  - name: "Rituals"
    desc: "_Create Undead_"

  - name: "Devour Soul"
    desc: "`pf2:2` (death,divine) The devourer touches a creature within reach, dealing 8d6 void damage (DC 31 Fortitude check save). If a creature is slain by this attack, its soul becomes trapped within the devourer. While its soul is trapped, a creature can't be resurrected except by powerful magic such as a [[Spells/Wish|Wish]] spell. Destroying the devourer or successfully counteracting Devour Soul (see spell deflection) releases the soul. The devourer can hold only one soul at a time.\n\nA soul has 5 soul charges per level of the originating creature (see the soul spells ability below). The devourer can expend these charges to cast spells. If the soul is freed and the creature returns to life, the creature is [[Conditions/Drained|Drained 1]] for every 5 soul charges expended. If reduced to 0 soul charges, the soul is consumed and can be restored to life only by powerful magic such as _wish_."

  - name: "Drain Life"
    desc: " (divine) When the devourer damages a living creature with its claw Strike, the devourer gains 10 temporary Hit Points and the creature must succeed at a DC 24 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the devourer increases the condition value by 1 on a failed save, to a maximum of drained 4."

  - name: "Soul Spells"
    desc: "  A devourer casts occult innate spells, but to do so it must expend a number of soul charges equal to the spell's rank (similar to casting a spell using charges from a staff). It can heighten any spell to a maximum of 6th level by expending more charges as it Casts the Spell. When encountered, a devourer typically has one trapped soul with 10 soul charges."
 
```

```encounter-table
name: Devourer
creatures:
  - 1: Devourer
```



When fiends and powerful evil spellcasters are lost beyond the farthest reaches of the multiverse, they sometimes return as horrific undead called devourers that consume the souls of the living to fuel their arcane machinations. Their bodies are ruined and rebuilt, hollow and twisted, even as their minds undergo a spiritual transformation. They gain the ability to bind other souls to their own and drain their essence for magical power, yet can never be sated in their pursuit of it. Seething masses of distorted ghostly shapes surge within their hollow rib cages-manifestations of the devourers' most recently consumed souls.
