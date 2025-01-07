---
title: "Wight Commander"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.w8Q6VTnMyKJBdApA" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wight
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Wight Commander"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Wight Commander"
level: "Creature 12"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[wight]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision"
languages: "Common, Necril; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Intimidation: +25, Warfare Lore: +25"
abilityMods: [6, 3, 4, 5, 3, 3]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 32
armorclass:
  - name: AC
    desc: "32 (34 with shield raised); __Fort__ +24, __Ref__ +19, __Will__ +21"
hp: 220
health:
  - name: ""
  - name: HP
    desc: "220, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longsword|+1 Striking Longsword]], [[Equipment/Steel Shield|Adamantine Shield]], [[Equipment/Full Plate|Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Final Spite"
    desc: "`pf2:r` (auditory,divine) **Trigger** The wight commander is reduced to 0 Hit Points\n* * *\n\n**Effect** The wight commander blows a battered war horn before being destroyed. The unnerving blast summons reinforcements, raising 1d4 corpses in a 200-foot emanation as [[Monster Core/Wight|Wights]]."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Longsword"
    desc: "+27 (magical, versatile p)\n__Damage__  2d8 + 14 slashing plus drain-life"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+26 (agile)\n__Damage__  2d8 + 14 slashing plus drain-life"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +21\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Coordinated Strike"
    desc: "  The wight commander flanks with an ally as long as the target is within both their reaches, even if commander and ally aren't on opposite sides."

  - name: "Drain Life"
    desc: " (divine) When the hunter wight damages a living creature using an unarmed attack or their bound weapon, they gain 12 temporary Hit Points, and the creature must succeed at a DC 29 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the hunter wight's unarmed and bound weapon attacks increases the value of the drained condition by 1 on a failed save, to a maximum of drained 4."

  - name: "Spawn Wight Soldier"
    desc: " (divine) A living humanoid killed by a wight commander's weapon or claw Strike rises as a wight of the commander's level or lower, most often a hunter wight or prowler wight, after 1d4 rounds. This spawn is under the command of the wight commander that killed them. They don't have drain life or spawn wight soldier and are [[Conditions/Clumsy|Clumsy 2]] for as long as they're a wight spawn. If the creator of the wight spawn dies, the wight spawn becomes a fully autonomous wight; they regain their free will, gain drain life and spawn wight soldier, and are no longer clumsy."

  - name: "Tactical Direction"
    desc: "`pf2:2` (auditory) Each wight ally in a 30-foot emanation gains the [[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]] reaction until the end of their next turn."
 
```

```encounter-table
name: Wight Commander
creatures:
  - 1: Wight Commander
```



When the beloved leader of a military unit is raised as a wight, sometimes the spirits of their comrades return with them, creating a gestalt being of impeccable tactical acumen.

* * *

Wights are undead beings of spite who primarily stalk places related to death.
