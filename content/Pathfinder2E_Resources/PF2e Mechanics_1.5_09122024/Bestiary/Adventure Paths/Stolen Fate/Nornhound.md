---
title: "Nornhound"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SLBZD5KX3m5Ry9rJ" 
tags:
  - pf2e/creature/type/fey
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Nornhound"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #192: Worst of All Possible Worlds"
name: "Nornhound"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[fey]]
trait_02: [[lawful]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Greater Darkvision, Scent (Precise) 120 Feet, Truesight"
languages: "Common, Fey, Jotun; tongues"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +35, Deception: +31, Diplomacy: +31, Intimidation: +33, Occultism: +30"
abilityMods: [9, 4, 8, 4, 6, 5]
speed: 40 feet,  fly 40 feet
sourcebook: "_Pathfinder #192: Worst of All Possible Worlds_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +34, __Ref__ +28, __Will__ +30"
hp: 421
health:
  - name: ""
  - name: HP
    desc: "421, regeneration 15 (deactivated by cold iron); __Weaknesses__ cold iron 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Sense Fate"
    desc: " (fortune) A nornhound automatically rolls a 20 when it rolls initiative."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Cold Iron)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Beyond Fate"
    desc: "  A nornhound can ignore any fortune or misfortune effects that affect them. If they're forced to roll twice as part of such an effect, they can take whichever die result they prefer, even if the effect would normally force them to choose one of the results."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (magical)\n__Damage__  3d12 + 17 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+33 (agile, magical, reach 15 feet)\n__Damage__  3d8 + 17 bludgeoning plus knockdown"

  - name: "**Ranged** `pf2:1` Temporal Blast"
    desc: "+33 (magical, range increment 120 feet)\n__Damage__  6d8 force"

  - name: "Occult Innate Spells"
    desc: "DC 37, attack +29; __9th __  _[[Spells/Cast into Time|Cast into Time]]_; __8th __  _[[Spells/Inevitable Disaster|Inevitable Disaster]]_, _[[Spells/Teleport|Teleport (Self Only, At Will)]]_; __6th __  _[[Spells/Slow|Slow]]_\n__Cantrips__  __(9th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(10th)__ _[[Spells/Truespeech|Tongues]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (mental,primal) The nornhound unleashes a blast of temporal energy in a 30-foot cone that deals 15d8 mental damage (DC 40 Will check save). Creatures that fail their save become [[Conditions/Confused|Confused]] for 1 round. The nornhound can't use Breath Weapon again for 1d4 rounds."

  - name: "Follow the Thread"
    desc: "  A nornhound is permanently [[Conditions/Quickened|Quickened]]. It can use its extra action only to Step or Stride."

  - name: "Pack Attack"
    desc: "  The nornhound's Strikes deal 1d6 extra damage to creatures within reach of at least two of its allies."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d12+10 bludgeoning, Rupture 36\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Time Bound"
    desc: "`pf2:3`  The nornhound jumps into the air, releasing multiple blasts of temporal energy. The nornhound leaps to a point within 60 feet. It can make up to three temporal blast Strikes at any point during this movement, each against a different target. These attacks count toward the nornhound's multiple attack penalty, but the multiple attack penalty doesn't increase until after all the attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Nornhound
creatures:
  - 1: Nornhound
```



While norns typically keep to themselves, only consulting their triumvirate or occasionally other fellow norns, they sometimes require servants to further their goals or protect their homes. Nornhounds are massive wolves spun from the old, tattered threads of fate, usually moments of time that norns severed to end a life. These wolves gain a portion of the same power over fate that norns do and serve their norn masters with unflinching loyalty.

## Nornhound Packs

Long-lived or powerful norns sometimes spin multiple nornhounds and keep entire packs as guardians. These packs make quick work of intruders and also gain additional powers when working together. Much like a norn triumvirate, a norn pack can their powers to affect the flow of time in a localized area or even stop time outright.
