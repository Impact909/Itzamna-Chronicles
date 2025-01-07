---
title: "Sunscale Serpent"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.8tr8Iv7SPGdQ2aAh" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2eMonster
  - pf2e/creature/level/14
  - remaster
statblock: inline
name: "Sunscale Serpent"
level: 14
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Sunscale Serpent"
level: "Creature 14"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[beast]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Low-Light Vision, Tremorsense (Imprecise) 100 Feet"
languages: "Common, Draconic; truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +25, Athletics: +25, Stealth: +33, Survival: +28"
abilityMods: [8, 4, 3, 1, 6, -1]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +25, __Ref__ +26, __Will__ +28"
hp: 251
health:
  - name: ""
  - name: HP
    desc: "251; __Immunities__  disease,  paralyzed,  poison,  precision; __Resistances__ all damage 14 (except force, ghost touch, spirit, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike (Tail Only)]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+28 (magical, reach 10 feet)\n__Damage__  3d8 + 11 force plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+28 (agile, magical, reach 15 feet)\n__Damage__  3d6 + 11 force plus push"

  - name: "Primal Innate Spells"
    desc: "DC 31, attack +0\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Bond with Mortal"
    desc: " (mental,primal) **Frequency** once per day\n* * *\n\n**Effect** The spirit guide spends 10 minutes to form a bond with a mortal creature. While the bond exists, the spirit guide increases their current and maximum Hit Points by 28, gains a +2 status bonus to their attack and damage rolls, and can communicate telepathically with the bonded mortal as long as the two beings are on the same plane. The spirit guide can only be bonded with one mortal at a time, and they can take this action again to end the bond or to form a new bond (which also ends the old bond). The bond also ends if the spirit guide or the mortal dies.\n\nThis bond strengthens the spirit guide's connection to the Universe. While bonded, the spirit guide loses the incorporeal and spirit traits, loses their immunity to disease, paralysis, and poison, along with their resistance to all damage, and changes their Strikes to deal the appropriate amount of physical damage (typically piercing or slashing) instead of force damage."

  - name: "Bonded Strike"
    desc: "`pf2:2`  **Requirements** The sunscale serpent is currently Bonded with a Mortal\n* * *\n\n**Effect** The sunscale serpent makes a jaws Strike. If this attack hits, the bonded mortal can spend their reaction to Strike the same target."

  - name: "Sun's Heat"
    desc: "`pf2:2`  The sunscale serpent Flies up to its fly Speed. All creatures directly below the spaces it moves through must succeed at a DC 31 Fortitude check save or be exposed to sun's touch poison. The serpent cannot fly further than 60 feet above the target or the poison becomes too dispersed in the fall to take effect."

  - name: "Sun's Touch"
    desc: " (poison) **Saving Throw** DC 34 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 6d8 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 8d6 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** 6d10 poison damage and [[Conditions/Fatigued|Fatigued]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d10+9 force and 2d10 fire, Rupture 32\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Unleash the Sun"
    desc: "`pf2:3`  **Requirements** The sunscale serpent is flying\n* * *\n\n**Effect** The sunscale serpent Flies up to its fly Speed, then crashes to the ground, releasing a wave of heat dealing 5d10 fire damage to all creatures within a 60-foot burst and searing their eyes with the erupting glory of its scales. Each creature in the area must attempt a DC 31 Reflex check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes half damage.\n\n**Failure** The creature takes full damage and is [[Conditions/Dazzled|Dazzled]] for 1 round.\n\n**Critical Failure** The creature takes full damage, is [[Conditions/Blinded|Blinded]] for 1 round, and dazzled for 1 minute."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Sunscale Serpent
creatures:
  - 1: Sunscale Serpent
```




