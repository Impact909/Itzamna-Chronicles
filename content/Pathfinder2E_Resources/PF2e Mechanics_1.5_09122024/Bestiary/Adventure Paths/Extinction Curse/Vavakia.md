---
title: "Vavakia"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6cpdijUOpPdqFOr1" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/demon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Vavakia"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #156: The Apocalypse Prophet"
name: "Vavakia"
level: "Creature 18"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[chaotic]]
trait_02: [[demon]]
trait_03: [[evil]]
trait_04: [[fiend]]
trait_05: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision, Truesight"
languages: "Chthonian, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +35, Deception: +32, Intimidation: +34, Religion: +30, Stealth: +32"
abilityMods: [9, 4, 6, 4, 6, 6]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder #156: The Apocalypse Prophet_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +32, __Ref__ +28, __Will__ +30; +1 status to all saves vs. magic"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350; __Weaknesses__ cold iron 15, holy 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Ranseur|+2 Greater Striking Ranseur]], [[Equipment/Breastplate|Breastplate]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 60 feet. DC 37 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Restoration Vulnerability"
    desc: "  A vavakia is repulsed by the restoration of souls.\n\nThe demon takes 3d10+10 mental damage the first time each round that a creature within 100 feet of it is restored to life or loses the [[Conditions/Doomed|Doomed]] condition."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ranseur"
    desc: "+36 (disarm, magical, reach 25 feet, unholy)\n__Damage__  3d10 + 17 piercing plus grab 1d10 acid plus grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (magical, reach 15 feet, unholy)\n__Damage__  2d8 bleed plus smoking-wound 3d8 + 17 piercing plus smoking-wound"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+35 (agile, magical, reach 15 feet, unholy)\n__Damage__  3d10 + 17 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+35 (backswing, magical, reach 20 feet, unholy)\n__Damage__  3d12 + 17 bludgeoning plus stunning-tail"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __9th __  _[[Spells/Massacre|Massacre]]_, _[[Spells/Power Word Stun|Power Word Stun]]_; __8th __  _[[Spells/Divine Aura|Divine Aura]]_, _[[Spells/Divine Wrath|Divine Wrath (At Will)]]_, _[[Spells/Earthquake|Earthquake]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Constant__  __(9th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Abyssal Pact_"

  - name: "Smoking Wound"
    desc: "  A creature damaged by the vavakia's jaws is [[Conditions/Sickened|Sickened 1]] from the rank smell of vapors from the wound."

  - name: "Soulfire Breath"
    desc: "`pf2:2` (death,divine,void) The vavakia exhales ghostly green fire in a 60-foot cone.\n\nLiving creatures in the area take 20d6 void damage (DC 42 Reflex check save). A good creature that fails this save is becomes [[Conditions/Stupefied|Stupefied 2]] for 1 minute ([[Conditions/Stupefied|Stupefied 4]] on a critical failure).\n\nA creature slain by Soulfire Breath can't be resurrected except by powerful magic such as a [[Spells/Wish|Wish]] spell.\n\nThe vavakia can't use Soulfire Breath again for 1d4 rounds."

  - name: "Soulfire Inhalation"
    desc: "`pf2:1` (divine,healing) **Requirements** The vavakia's last action was Soulfire Breath\n* * *\n\n**Effect** The vavakia inhales and regains 10 healing Hit Points for each creature damaged by its Soulfire Breath. Any excess healing is gained as temporary Hit Points, which remain for 1 minute."

  - name: "Stunning Tail"
    desc: " (incapacitation) If the vavakia critically hits with its tail Strike, the target must succeed at a DC 40 Fortitude check save or be [[Conditions/Stunned|Stunned]] for 1 round (1d4 rounds on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Large or smaller, claw, DC 40 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Vavakia
creatures:
  - 1: Vavakia
```



Juggernauts of destruction, vavakias are formed from the souls of mortals who extract, enslave, or consume the souls of others.
