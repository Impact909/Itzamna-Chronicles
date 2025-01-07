---
title: "Maliadi"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5kwre7eNlJyC5hCV" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Maliadi"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Lost Omens: The Mwangi Expanse"
name: "Maliadi"
level: "Creature 17"

alignment: ""
size: "grg"
trait_01: [[beast]]
trait_02: [[evil]]
trait_03: [[lawful]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Scent (Imprecise) 60 Feet, Truesight"
languages: "Aklo, Common, Draconic, Mwangi"
skills:
  - name: "Skills"
    desc: "Athletics: +36, Deception: +28, Intimidation: +28, Nature: +29, Survival: +29"
abilityMods: [9, 3, 9, 1, 6, 3]
speed: 30 feet,  swim 20 feet
sourcebook: "_Pathfinder Lost Omens: The Mwangi Expanse_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +34, __Ref__ +25, __Will__ +28"
hp: 285
health:
  - name: ""
  - name: HP
    desc: "285; __Immunities__  fire,  death effects; __Resistances__ physical ranged attacks 20"
abilities_top:
  - name: ""

  - name: "Deep Breath"
    desc: "  The maliadi can hold its breath for 1 day."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Collar of Fire"
    desc: " (fire,primal) The maliadi has resistance 20 to physical ranged attacks, such as arrows, bolts, javelins, and thrown rocks, as such attacks are magically diverted through its collar of fire.\n\nNonmagical weapons and ammunition affected by this ability are incinerated and destroyed."

  - name: "Counterspelling Wall"
    desc: "`pf2:r` (fire,primal) **Trigger** A creature within 100 feet of the maliadi that the maliadi can see Casts a Spell that targets the maliadi\n* * *\n\n**Effect** The maliadi casts one of its innate [[Spells/Wall of Fire|Wall of Fire]] spells, with a duration of 1 round.\n\nIf the spell that triggered this reaction passes through the wall of fire, the wall attempts to counteract it, with a counteract modifier of +28."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (deadly d12, magical, reach 20 feet)\n__Damage__  3d12 + 19 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+35 (agile, magical, reach 20 feet)\n__Damage__  3d10 + 17 bludgeoning"

  - name: "Innate Primal Spells"
    desc: "DC 38, attack +30; __9th __  _[[Spells/Wall of Fire|Wall of Fire (x3)]]_, _[[Spells/Wall of Stone|Wall of Stone (x3)]]_; __8th __  _[[Spells/Fire Shield|Fire Shield]]_, _[[Spells/Volcanic Eruption|Volcanic Eruption]]_; __4th __  _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Vapor Form|Gaseous Form]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Produce Flame|Produce Flame]]_\n__Constant__  __(8th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_ __(7th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Capsize"
    desc: "`pf2:1`  The maliadi tries to capsize an adjacent aquatic vessel of its size or smaller.\n\nThe maliadi must succeed at a DC 35 Athletics check check (reduced by 5 for each size smaller the vessel is than the maliadi) or the pilot's Sailing Lore DC, whichever is higher."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The maliadi can take on the appearance of any Large, Huge, or Gargantuan animal. This doesn't change its Speed or Strikes.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "River Form"
    desc: "`pf2:3`  The maliadi takes on the form of a stretch of river, with the effects of [[Spells/Migration|Migration]], except the maliadi can only affect itself, appears as a section of a flowing river that takes up the same space as the maliadi, and can't leave the ground."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d10+17 bludgeoning damage, Rupture 35\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 38 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Maliadi
creatures:
  - 1: Maliadi
```



A maliadi resembles a massive hippopotamus surrounded by a collar of flame. Maliadis are arrogant and tyrannical, and demand tribute from everyone they encounter-whether lone travelers or entire villages-to avert destruction. Many pay them off, for maliadis can hurl parts of their flaming collars to form geysers of flame or fiery walls, and they're also powerful shapeshifters.
