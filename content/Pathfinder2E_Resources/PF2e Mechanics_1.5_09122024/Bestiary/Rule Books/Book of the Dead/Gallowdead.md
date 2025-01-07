---
title: "Gallowdead"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jSTW4N2sAMYiNAlD" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Gallowdead"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Gallowdead"
level: "Creature 15"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Acrobatics: +27, Athletics: +29, Intimidation: +26, Stealth: +27"
abilityMods: [8, 4, 5, 2, 4, 5]
speed: 25 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +28, __Ref__ +25, __Will__ +27"
hp: 280
health:
  - name: ""
  - name: HP
    desc: "280, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Chain|+2 Striking Spiked Chain]], [[Equipment/Full Plate|+2 Resilient Full Plate]]"
  - name: "Eyes of the Tyrant"
    desc: "  Gallowdead are the eyes and ears of the Whispering Tyrant, so Tar-Baphon can see through them at any time as long as they're on the same plane of existence as him."

abilities_mid:
  - name: ""
  - name: "Aura of Whispers"
    desc: " (auditory,aura,divine,fear,mental) 30 feet. A gallowdead is surrounded by an aura of blasphemous whispers. A creature who hears them understands them to be mutterings of its most closely guarded secrets and private failings laid bare. A creature that first enters the area must attempt a DC 34 Will check save. Regardless of the result of the saving throw, the creature is temporarily immune to aura of whispers for 1 minute. The frightened condition from this aura can't be reduced while in the aura.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]] and [[Conditions/Stunned|Stunned 1]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]] and [[Conditions/Stunned|Stunned 3]]."

  - name: "Chains of the Dead"
    desc: "  The spiked chain of a gallowdead is wrapped around and through their body, imbuing it with foul necromantic powers. The spiked chain can't be disarmed, deals an additional weapon die of damage, and has a greater reach while wielded by the gallowdead."

  - name: "Gallow Curse"
    desc: " (curse,divine) Those who destroy gallowdead are subject to a powerful death curse. When a creature reduces a gallowdead to 0 HP, the creature must attempt a DC 34 Will check save. A creature that fails this saving throw is [[Conditions/Doomed|Doomed 1]] and can't remove the condition until the curse has been lifted."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+31 (disarm, reach 20 feet, trip)\n__Damage__  3d8 + 14 slashing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+29 (agile)\n__Damage__  3d12 + 14 slashing"

  - name: "Chain Capture"
    desc: "`pf2:r`  **Trigger** The gallowdead critically hits a target with their spiked chain\n* * *\n\n**Effect** The gallowdead attempts an Athletics check to [[Actions/Grapple|Grapple]] the target. On a success, the gallowdead can also pull the target adjacent toward them to the distance the gallowdead chooses. Most often, a gallowdead chooses to pull a creature close enough that it's in their reach and out of defensive position, but so the creature still can't reach the gallowdead's body. At the start of the gallowdead's next turn, if the target hasn't Escaped, the target takes the damage of a spiked chain Strike, and the chain releases the creature."

  - name: "Charge Chain"
    desc: " (divine,void) **Frequency** once per round\n* * *\n\n**Effect** The gallowdead imbues their chain with necromantic power. The gallowdead chooses to make their next Strike with the chain this turn either deal an additional 4d6 void damage or have 120-foot reach."
 
```

```encounter-table
name: Gallowdead
creatures:
  - 1: Gallowdead
```



The first gallowdead were hung from enormous, hooked chains from atop the Whispering Tyrant's prison, Gallowspire, and magically bonded to their chains after death. After Gallowspire's destruction, the gallowdead who remained were left to wander the ruins.
