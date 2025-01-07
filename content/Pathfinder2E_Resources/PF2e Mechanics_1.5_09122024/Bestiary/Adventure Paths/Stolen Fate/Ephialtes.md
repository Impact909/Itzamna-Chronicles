---
title: "Ephialtes"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nFB0MNVgyKUgnEwG" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2e/creature/type/velstrac
  - pf2eMonster
  - pf2e/creature/level/16
statblock: inline
name: "Ephialtes"
level: 16
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #191: The Destiny War"
name: "Ephialtes"
level: "Creature 16"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[lawful]]
trait_04: [[unholy]]
trait_05: [[velstrac]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Greater Darkvision, Truesight"
languages: "Common, Diabolic, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Athletics: +31, Deception: +30, Intimidation: +32, Medicine: +30, Religion: +30, Survival: +28, Torture Lore: +29"
abilityMods: [9, 5, 6, 5, 6, 6]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder #191: The Destiny War_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +30, __Ref__ +25, __Will__ +28; +1 status to all saves vs. magic"
hp: 299
health:
  - name: ""
  - name: HP
    desc: "299; __Immunities__  cold,  fear effects; __Weaknesses__ holy 15, silver 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "Painsight"
    desc: " (divine) A velstrac automatically knows whether a creature it sees has any of the [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], and [[Conditions/Wounded|Wounded]] conditions, as well as the value of those conditions."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 20 (Deactivated By Good or Silver)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Nowhere to Run"
    desc: " (aura,divine,fear,mental,visual) 30 feet. When a creature ends its turn in the aura, it feels a powerful sensation of hopelessness. The creature must succeed at a DC 34 Will check save or become [[Conditions/Slowed|Slowed 1]] ([[Conditions/Slowed|Slowed 2]] on a critical failure) for 1 round."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+33 (magical, reach 15 feet, unholy)\n__Damage__  3d6 + 13 piercing 2d6 bleed"

  - name: "**Melee** `pf2:1` Chain"
    desc: "+33 (disarm, magical, reach 15 feet, unholy)\n__Damage__  2d6 bleed plus grab 3d6 + 13 piercing plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Chilling Darkness|Chilling Darkness]]_, _[[Spells/Pinpoint|Discern Location]]_, _[[Spells/Umbral Journey|Shadow Walk]]_; __7th __  _[[Spells/Blur|Blur]]_, _[[Spells/Interplanar Teleport|Plane Shift (Self Only)]]_, _[[Spells/Silence|Silence (x3)]]_; __6th __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Planar Tether|Dimensional Anchor (At Will)]]_\n__Constant__  __(8th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d4+13 slashing, DC 37 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Exhale Chains"
    desc: "`pf2:2` (divine) The ephialtes exhales a tangle of barbed chains. All creatures in a 50-foot cone must attempt a DC 37 Reflex check save. The ephialtes can't Exhale Chains for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** It takes 8d6 piercing damage.\n\n**Failure** It takes 15d6 piercing damage, 2d6 persistent bleed damage, and is [[Conditions/Off-Guard|Off-Guard]] for 1 round.\n\n**Critical Failure** As failure, but 30d6 piercing damage, 2d6 persistent bleed damage, and is [[Conditions/Restrained|Restrained]] until they [[Actions/Escape|Escape]] (DC 37)."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,mental,visual) The ephialtes stares at a creature they can see within 30 feet. The creature must attempt a Will save against the nowhere to run aura. If it was already slowed, on a failed save its speed is reduced by 10 feet until the end of its next turn. After attempting this save, the targeted creature is then temporarily immune to Focus Gaze until the start of the ephialtes's next turn."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ephialtes
creatures:
  - 1: Ephialtes
```



Ephialtes velstracs are consummate and fearless hunters of the doomed and the damned.

## Ephialtes Prey

When they catch enough quarry, an ephialtes velstrac returns to the Shadow Plane, bringing victims for other velstracs to use for training or raw material. Velstracs respect ephialtes for their "generosity" in guiding and providing for others of their kind, yet are always wary about making assumptions about the limits of this generosity.
