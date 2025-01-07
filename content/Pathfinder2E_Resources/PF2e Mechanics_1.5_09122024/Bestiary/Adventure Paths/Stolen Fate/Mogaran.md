---
title: "Mogaran"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.I3Bs7wPH6Gqq4Quc" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Mogaran"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Mogaran"
level: "Creature 17"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Truesight"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +33, Deception: +30, Intimidation: +30, Religion: +28, Stealth: +28"
abilityMods: [8, 3, 5, 4, 5, 5]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +30, __Ref__ +26, __Will__ +30; +1 status to all saves vs. magic"
hp: 325
health:
  - name: ""
  - name: HP
    desc: "325; __Weaknesses__ cold iron 15, holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Crystal Implant"
    desc: " (divine,mental) The wolf-head shaped crystal implanted in Mogaran's brow pulses with shadowy energy at the start of each of his turns. Any PC who's legendary in Arcana, Occultism, or Religion and sees this can attempt a DC 36 check using one of those skills (DC 36 Arcana check, DC 36 Occultism check, or DC 36 Religion check); on a success, they realize the crystal is manipulating Mogaran's actions in some way. If the crystal is destroyed or deactivated, Mogaran regains control of his actions. The crystal functions as a 19th-level magic item for the purposes of dispel magic, but it can also be destroyed by specifically targeting it (AC 40; Hardness 20; HP 90). Alternately, a character can pry the crystal from Mogaran's brow with a successful DC 36 Athletics check check, which takes an Interact action, but only if Mogaran is [[Conditions/Immobilized|Immobilized]]."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 35 Will check\n\nThis aura is suppressed as long as Mogaran's crystal implant is functioning.\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Restoration Vulnerability"
    desc: "  Mogaran is repulsed by the restoration of souls. He takes 3d10+10 mental damage the first time each round a creature within 100 feet of him is restored to life or loses the [[Conditions/Doomed|Doomed]] condition."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 15 feet, unholy)\n__Damage__  2d8 bleed plus smoking-wound 3d6 + 14 piercing plus smoking-wound 1d6 spirit plus smoking-wound"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+33 (agile, magical, reach 15 feet, unholy)\n__Damage__  1d6 spirit 3d10 + 14 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (backswing, magical, reach 20 feet, unholy)\n__Damage__  1d6 spirit plus stunning-tail 3d12 + 14 bludgeoning plus stunning-tail"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Massacre|Massacre]]_, _[[Spells/Power Word Stun|Power Word Stun]]_; __8th __  _[[Spells/Divine Aura|Divine Aura]]_, _[[Spells/Divine Wrath|Divine Wrath (At Will)]]_, _[[Spells/Earthquake|Earthquake]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(9th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "[[Actor.RLuLdBW6SSs9u2hL.Item.oe15nn62zh9y60Wn|Smoking Wound]]"
    desc: "  A creature damaged by Mogaran's jaws is [[Conditions/Sickened|Sickened 1]] from the rank smell of vapors from the wound."

  - name: "Soulfire Breath"
    desc: "`pf2:2` (death,divine,void) Mogaran exhales ghostly green fire in a 60-foot cone. Living creatures in the area take 18d6 void damage (DC 38 Reflex check save). A good creature that fails this save becomes [[Conditions/Stupefied|Stupefied 2]] for 1 minute ([[Conditions/Stupefied|Stupefied 4]] on a critical failure). A creature slain by Soulfire Breath can't be resurrected except by powerful magic such as a wish spell. Mogaran can't use Soulfire Breath again for 1d4 rounds."

  - name: "Soulfire Inhalation"
    desc: "`pf2:1` (divine,healing) **Requirements** Mogaran's last action was Soulfire Breath\n* * *\n\n**Effect** Mogaran inhales and regains 10 Hit Points for each creature damaged by his Soulfire Breath. Any excess healing is gained as temporary Hit Points, which remain for 1 minute."

  - name: "Stunning Tail"
    desc: " (incapacitation) If Mogaran critically hits with his tail Strike, the target must succeed at a DC 38 Fortitude check save or be [[Conditions/Stunned|Stunned]] for 1 round (1d4 rounds on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, claw, DC 38 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Mogaran
creatures:
  - 1: Mogaran
```


Male weakened vavakia

Juggernauts of destruction, vavakias are formed from the souls of mortals who extract, enslave, or consume the souls of others.
