---
title: "Bythos"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4v5D3eaB9cIA9n1w" 
tags:
  - pf2e/creature/type/aeon
  - pf2e/creature/type/lawful
  - pf2e/creature/type/monitor
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Bythos"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Bythos"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[aeon]]
trait_02: [[lawful]]
trait_03: [[monitor]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision"
languages: "envisioning"
skills:
  - name: "Skills"
    desc: "Arcana: +29, Athletics: +32, Deception: +25, Intimidation: +25, Nature: +30, Occultism: +29, Religion: +30, Stealth: +26"
abilityMods: [8, 4, 5, 7, 8, 5]
speed:  fly 35 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +25, __Ref__ +26, __Will__ +30; +1 status to all saves vs. magic"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245, regeneration 15 (deactivated by chaotic)"
abilities_top:
  - name: ""

  - name: "Envisioning"
    desc: "  When a bythos conveys information, it does so wordlessly through psychic projections. This acts as [[Bestiary Ability Glossary/Telepathy|Telepathy]] with a range of 100 feet but is understandable to all creatures regardless of whether they have a language.\n\nThe meaning to non-aeons can be vague and is often mysterious. A bythos can use this ability to communicate flawlessly with any other aeon on the same plane."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Chaotic)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Confusing Gaze"
    desc: " (aura,divine,emotion,incapacitation,mental,visual) 30 feet. A creature that ends its turn in the aura must attempt a DC 34 Will check save. If it fails, it's [[Conditions/Confused|Confused]] for 1 round (or 1d4 rounds on a critical failure)."

  - name: "Temporal Reversion"
    desc: "`pf2:0` (fortune) **Trigger** The bythos fails or critically fails a check\n\n**Frequency** once per day\n* * *\n\n**Effect** The bythos rerolls the triggering check and takes the better result."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+32 (magical, reach 10 feet)\n__Damage__  2d8 + 16 bludgeoning 2d8 cold 2d8 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +27; __8th __  _[[Spells/Augury|Augury (At will)]]_, _[[Spells/Teleport|Teleport]]_; __7th __  _[[Spells/Planar Tether|Dimensional Anchor]]_, _[[Spells/Planar Seal|Dimensional Lock]]_, _[[Spells/Haste|Haste]]_, _[[Spells/Interplanar Teleport|Plane Shift]]_; __6th __  _[[Spells/Slow|Slow]]_; __4th __  _[[Spells/Planar Tether|Dimensional Anchor (At will)]]_"

  - name: "Rituals"
    desc: "_Imprisonment (Temporal stasis only)_"

  - name: "Aging Strikes"
    desc: "`pf2:2` (divine) The bythos make two fist Strikes against a single target. If both Strikes hit, the target attempts a DC 37 Fortitude check save. Creatures that don't get weaker with age or don't age are immune (GM's discretion).\n\nIf a creature becomes clumsy 4, drained 4, and enfeebled 4 due to Aging Strikes, it dies of old age.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature becomes [[Conditions/Clumsy|Clumsy 1]], [[Conditions/Drained|Drained 1]], and [[Conditions/Enfeebled|Enfeebled 1]], or increases each of these conditions by 1. This effect is cumulative with other aging strikes from bythoses, to a maximum of clumsy 4, drained 4, and enfeebled 4.\n\n**Critical Failure** As failure, but the creature becomes [[Conditions/Clumsy|Clumsy 2]], [[Conditions/Drained|Drained 2]], and [[Conditions/Enfeebled|Enfeebled 2]], or increases these conditions by 2."

  - name: "Focused Gaze"
    desc: "`pf2:1` (concentrate) The bythos focuses its gaze on a creature it can see within 30 feet. The target must attempt a save against the bythos's confusing gaze. A bythos can't use this ability against the same creature more than once per turn."

  - name: "Temporal Flurry"
    desc: "`pf2:2`  The bythos makes four fist Strikes. Its multiple attack penalty increases normally with each attack."

  - name: "Temporal Strike"
    desc: "`pf2:2` (divine,incapacitation,teleportation) The bythos touches a creature or object to displace it from time. The target attempts a DC 37 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** Time flows around the target; the target is [[Conditions/Slowed|Slowed 1]] for 1 round.\n\n**Failure** The target disappears from the present moment and reappears in the same location 1d4 rounds later as if no time had passed for it. If a creature or object occupies that space when the target returns, the target appears in the closest available space to its original location.\n\n**Critical Failure** As failure, but the target is [[Conditions/Slowed|Slowed 1]] for an extra 1d4 rounds after it returns."
 
```

```encounter-table
name: Bythos
creatures:
  - 1: Bythos
```



The bythos is a guardian of space and time, and at all times seeks out those who misuse planar and temporal magic. A bythos is a roughly humanoid creature with four arms and a body made of swirling clouds and mist. Despite its appearance, its body feels like dry stone. A bythos seeks out paradoxes caused by irresponsible planar or dimensional travelers and repairs breaches where the barriers between planes have become thin or damaged. If the mortals responsible remain in the area and cannot be convinced to cease their activities, the bythos has no qualms about removing them. Using its ability to manipulate time, a bythos might cause an opponent to quickly die of old age as time speeds up around them, or cause a target to disappear from time and space.
