---
title: "Camarach"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6kHPSLAyBnK320F1" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Camarach"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Camarach"
level: "Creature 17"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[monitor]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Thoughtsense (Imprecise) 120 Feet"
languages: "Chthonian, Diabolic, Empyrean, Protean; telepathy 100 feet, tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +33, Deception: +36, Intimidation: +30, Religion: +31, Stealth: +28, Survival: +31"
abilityMods: [10, 5, 6, 6, 6, 9]
speed:  fly 60 feet,  swim 60 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 40
armorclass:
  - name: AC
    desc: "40; __Fort__ +31, __Ref__ +26, __Will__ +29"
hp: 320
health:
  - name: ""
  - name: HP
    desc: "320; __Resistances__ physical 15 (except bludgeoning)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Thoughtsense|Thoughtsense (Imprecise) 120 feet]]"
    desc: " (mental,occult) Thoughtsense allows a monster to sense all non-mindless creatures at the listed range."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (magical, reach 20 feet)\n__Damage__  3d10 + 18 piercing plus improved-grab"

  - name: "Occult Innate Spells"
    desc: "DC 43, attack +35; __9th __ (1 slots) _[[Spells/Project Image|Project Image (At Will) (See Project False Image)]]_; __8th __ (3 slots) _[[Spells/Hallucination|Hallucination (x3)]]_; __5th __ (3 slots) _[[Spells/Mind Probe|Mind Probe (x3)]]_\n__Constant__  __(7th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Disgorge Portal"
    desc: "`pf2:2` (light,occult) The camarach vomits a spray of coruscating light. This has the effect of a DC 42 [[Spells/Prismatic Spray|Prismatic Spray]], except that each creature is affected by one violet beam and one other beam (roll 1d6 instead of 1d8 to determine which other beam).\n\nThe camarach can't Disgorge a Portal again for 1d4 rounds."

  - name: "Exile"
    desc: "`pf2:1` (occult,teleportation) The camarach shunts one creature within its body through an inner portal to send it away.\n\nThe target must attempt a DC 38 Will check save.\n* * *\n\n**Critical Success** The creature is teleported to an open space it chooses within 30 feet of the camarach.\n\n**Success** The creature isn't teleported.\n\n**Failure** The creature is teleported to a random open space 1 mile from the camarach.\n\n**Critical Failure** The creature is teleported to a random other plane, as [[Spells/Interplanar Teleport|Interplanar Teleport]]."

  - name: "Fast Swallow"
    desc: "`pf2:r`  **Trigger** The camarach Grabs a creature\n* * *\n\n**Effect** The camarach uses Swallow Whole."

  - name: "Project False Image"
    desc: "  When the camarach casts project image, its illusory image can be another creature of its size or a structure of its size that features a large portal (such as a freestanding archway or a large hut with an open doorway)."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 3d10+9 bludgeoning damage, Rupture 34\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Camarach
creatures:
  - 1: Camarach
```




