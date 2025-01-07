---
title: "Blackfingers"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7Atb4QcTsz606lQu" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Blackfingers"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Blackfingers"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[unholy]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Greater Darkvision"
languages: "Common, Diabolic; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Crafting: +38, Deception: +35, Intimidation: +35, Medicine: +37, Occultism: +38, Religion: +35, Stealth: +37, Norgorber Lore: +38, Vyre Lore: +38"
abilityMods: [6, 7, 9, 10, 7, 6]
speed: 40 feet,  climb 30 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +37, __Ref__ +35, __Will__ +33"
hp: 360
health:
  - name: ""
  - name: HP
    desc: "360; __Immunities__  poison; __Weaknesses__ holy 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+3 Greater Striking Corrosive Keen Returning Dagger, Key Ring, 2x Elixir of Rejuvenation, 10x Vyre's Bliss, Red Hand's Satchel"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Consumed by Bloodlust"
    desc: "`pf2:r` (emotion,mental) **Frequency** once per day;\n\n**Duration** 1 minute\n\n**Trigger** Blackfingers damages a creature\n* * *\n\n**Effect** Murderous instinct consumes Blackfingers' mind. He gains a +2 status bonus to attacks and damage with his dagger, but is [[Conditions/Stupefied|Stupefied 2]] and cannot use concentrate abilities. If he brings a creature to 0 Hit Points while consumed by bloodlust, he gains 20 temporary Hit Points, and this effect ends."

  - name: "Poison Sense (Precise) 30 feet"
    desc: "  Blackfingers senses any poisoned creature. He can spend an action with the concentrate trait to determine the poison's type and current stage."

  - name: "Venomous Aura"
    desc: " (aura,occult,poison) 60 feet. Each creature that enters or starts its turn within the area must succeed at a DC 39 Fortitude check saving throw or gain weakness 10 to poison (weakness 15 on a critical failure). Worshippers of Norgorber are immune, as are those who drank any poison in area **C3**."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+34 ()\n__Damage__  4d10 + 16 piercing plus blackfingers-venom"

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+38 (agile, finesse, magical, versatile s)\n__Damage__  3d4 + 16 piercing plus blackfingers-venom 1d6 acid plus blackfingers-venom"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+38 (agile, magical, thrown 10 ft., versatile s)\n__Damage__  4d8 + 15 piercing plus blackfingers-venom"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __10th __  _[[Spells/Toxic Cloud|Toxic Cloud]]_; __9th __  _[[Spells/Slither|Slither (Spiders Instead of Snakes)]]_, _[[Spells/Vision of Death|Vision of Death]]_; __8th __  _[[Spells/Disappearance|Disappearance]]_; __5th __  _[[Spells/Hallucination|Hallucination (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Blackfingers' Venom"
    desc: " (divine,incapacitation,poison) Blackfingers' dagger is constantly coated with the same insidious toxin that drips from his fangs, and recoats his dagger instantly each time after he Strikes\n\n**Saving Throw** DC 42 Fortitude check\n\n**Maximum Duration** 4 hours\n\n**Stage 1** 3d6 poison damage\n\n**Stage 2** 3d6 poison damage and [[Conditions/Slowed|Slowed 1]] (1 round),\n\n**Stage 3** 4d6 poison and [[Conditions/Slowed|Slowed 2]] (1 round)\n\n**Stage 4** [[Conditions/Paralyzed|Paralyzed]] for 1d4 hours."

  - name: "Change Shape"
    desc: "`pf2:1` (arcane,concentrate,polymorph) Blackfingers can take the shape of a Tiny spider. This doesn't change his Speed or jaws Strike, but prevents him from making dagger Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Enhance Poison"
    desc: " (divine) **Frequency** once per round\n* * *\n\n**Effect** Blackfingers causes the save DC of a dose of poison he holds in a hand (or that coats a weapon he holds) to increase to DC 42 until the start of his next turn."

  - name: "Sneak Attack"
    desc: "  Blackfingers deals 3d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]."

  - name: "Stab! Stab! Stab! Stab!"
    desc: "`pf2:3`  **Requirements** Blackfingers is Consumed by Bloodlust\n* * *\n\n**Effect** Blackfingers lashes out and makes four dagger Strikes against adjacent targets at his current attack modifier but with a –2 penalty. Each attack counts toward his multiple attack penalty but the penalties don't apply until the end of this activity. On each successful hit he restores 15 healing Hit Points. Consumed by Bloodlust's effects then end."
 
```

```encounter-table
name: Blackfingers
creatures:
  - 1: Blackfingers
```


Male variant karumzek


