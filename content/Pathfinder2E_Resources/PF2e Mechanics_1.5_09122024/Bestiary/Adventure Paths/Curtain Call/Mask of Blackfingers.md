---
title: "Mask of Blackfingers"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.otVh6xQeJHzFM1c2" 
tags:
  - pf2e/creature/type/fiend
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Mask of Blackfingers"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Mask of Blackfingers"
level: "Creature 16"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[fiend]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[unholy]]
modifier: 32
perception:
  - name: "Perception"
    desc: "+32; Darkvision"
languages: "Common; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +31, Athletics: +28, Crafting: +29, Deception: +30, Diplomacy: +30, Intimidation: +30, Religion: +28, Society: +27, Stealth: +33, Thievery: +31, Norgorber Lore: +31"
abilityMods: [6, 9, 5, 5, 6, 6]
speed: 30 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +33, __Will__ +28"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+2 Greater Striking Shortsword, +2 Resilient Leather Armor, Faith Tattoo (True)"
  - name: "Constant Spells"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Reactive Strike"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Secretive Tattoos"
    desc: "  The mask keeps their faith tattoo hidden (typically by wearing gloves to cover the palm). To use it as a divine focus, they must first Interact to uncover the tattoo. The tattoo then stays uncovered until the mask Interacts to cover it up. A mask's faith tattoo only allows for the casting of [[Spells/Harm|Harm]]. Upon the mask's death, the tattoo disappears."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+33 (agile, finesse, magical, versatile p)\n__Damage__  3d6 + 14 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Heal|Heal (x3)]]_, _[[Spells/Shadow Blast|Shadow Blast]]_, _[[Spells/Toxic Cloud|Toxic Cloud]]_; __7th __  _[[Spells/Cleanse Affliction|Cleanse Affliction]]_, _[[Spells/Divine Decree|Divine Decree]]_, _[[Spells/Slither|Slither]]_; __6th __  _[[Spells/Sending|Sending (x3)]]_, _[[Spells/Spellwrack|Spellwrack]]_; __4th __  _[[Spells/Invisibility|Invisibility (x3)]]_, _[[Spells/Silence|Silence (x3)]]_\n__Cantrips__  __(8th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Message|Message]]_\n__Constant__  __(8th)__ _[[Spells/Truesight|Truesight]]_, _[[Spells/Truespeech|Truespeech]]_"

  - name: "Aspect's Agony"
    desc: "  When a mask of Norgorber Strikes a foe with a weapon, they inflict an additional 1d6 persistent poison damage. As long as a creature is taking this persistent damage, they're [[Conditions/Off-Guard|Off-Guard]]."

  - name: "Evaporate Poison"
    desc: "`pf2:1` (divine,poison) **Frequency** once per day\n* * *\n\n**Effect** The mask blows out a breath and targets a creature within 30 feet that is currently poisoned or is taking persistent poison damage. The target must attempt a DC 37 Fortitude check save as the mask attempts to transmute the poison afflicting them into toxic vapor.\n* * *\n\n**Critical Success** The poison effect on the target immediately ends.\n\n**Success** The poison effect on the target immediately ends, but toxic vapor fills one of the target's adjacent squares, chosen by the mask. A creature in this square is exposed to brimstone fumes; the toxic vapor then vanishes.\n\n**Failure** As success, but the toxic vapor fills a 5-foot emanation around the target, exposing all creatures in the area (including the target) to brimstone fumes; the toxic vapor then vanishes.\n\n**Critical Failure** As failure, but the toxic vapor fills a 10-foot emanation around the target, and the poison effect or persistent poison damage the target is suffering does not end."

  - name: "Sneak Attack"
    desc: "  A mask of Norgorber deals 2d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]."
 
```

```encounter-table
name: Mask of Blackfingers
creatures:
  - 1: Mask of Blackfingers
```



These masks focus on the use of poisons to spread Norgorber's will.

* * *

When a powerful worshipper catches Norgorber's eye, he sometimes transforms that worshipper into one of his masks—supernatural incarnations who become powerful proxies to their god but sacrifice their free will.

## Other Ancestries

Most of the masks of Norgorber are human, but not all. A mask's statistics don't change if it's a Small creature, and they gain increased space and reach if they're Large or larger. Change ancestry traits as needed, but Speed and languages are unchanged. All masks of Norgorber possess darkvision granted them by their deity. Whether or not you grant a mask additional ancestry-based abilities is left to you to decide.

## Masks and the Afterlife

When a worshipper becomes a mask, they technically die and travel to the Boneyard to be judged by Pharasma, but in this case, the process is almost instantaneous. When Norgorber chooses someone to become a mask, a swift and nearly instantaneous blurring of the creature is the only indication of their change. Like most fiends, masks are immortal unless slain through violence or misadventure. Once slain, a mask's body decays as normal, and after a variable amount of time has passed, their soul returns to the Great Beyond to accrete its quintessence into Norgorber's realm of Duskfathom.
