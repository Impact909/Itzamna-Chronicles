---
title: "Chakanaj"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ft3w6A8MgXSg3iTl" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/sahkil
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Chakanaj"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Adventure: Night of the Gray Death"
name: "Chakanaj"
level: "Creature 14"
rare_03: [[Rare]]
alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[fiend]]
trait_03: [[sahkil]]
trait_04: [[unholy]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Truesight"
languages: "Chthonian, Diabolic, Empyrean, Requian; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Deception: +27, Intimidation: +25, Religion: +25, Stealth: +30, Thievery: +26"
abilityMods: [0, 8, 4, 2, 5, 7]
speed: 10 feet,  fly 40 feet
sourcebook: "_Pathfinder Adventure: Night of the Gray Death_"
ac: 36
armorclass:
  - name: AC
    desc: "36; __Fort__ +22, __Ref__ +28, __Will__ +25"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  fear effects; __Weaknesses__ holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Ear for Secrets"
    desc: "  A chakanaj knows when a creature within 30 feet lies unless that creature critically succeeds on its Perception check to lie to the chakanaj. This ability doesn't reveal the truth."

  - name: "Easy to Call"
    desc: "  A sahkil's level is considered 2 lower for the purpose of being conjured by the [[Spells/Binding Circle|Binding Circle]] ritual (and potentially other rituals, at the GM's discretion), but is always free to attack or leave instead of negotiate unless the primary caster's check is a critical success."

  - name: "Retaliate"
    desc: "`pf2:r`  **Trigger** A creature within the chakanaj's reach attacks its host **Requirements** The chakanaj is Bonded with a Host\n* * *\n\n**Effect** The chakanaj makes a leg Strike against the triggering creature. If the chakanaj was Impersonating clothing when it makes this strike, the Impersonation ends."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Leg"
    desc: "+29 (agile, finesse, magical, unholy)\n__Damage__  3d6 + 14 slashing 2d6 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +26; __7th __  _[[Spells/Fear|Fear (At Will)]]_, _[[Spells/Mask of Terror|Mask of Terror (At Will) (Self Only)]]_; __5th __ (3 slots) _[[Spells/Illusory Object|Illusory Object]]_\n__Cantrips__  __(7th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Guidance|Guidance]]_\n__Constant__  __(7th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Bond with Host"
    desc: "`pf2:1` (concentrate,move) **Requirements** The chakanaj is adjacent to a willing creature\n* * *\n\n**Effect** The chakanaj enters the space of the creature (thereafter called its host) and covers a suitable surface on the host, such as the face or back. The chakanaj occupies the same space as its host and moves with its host. It doesn't impair the host's senses or movement. While worn, the chakanaj establishes a constant[[Spells/Share Life|Share Life]] effect with its host. Attacks that target the chakanaj target the host instead, but use the higher AC or saving throw values between the chakanaj and the host. Area effects apply to both the chakanaj and the host, as normal for an area of effect."

  - name: "Interpose"
    desc: "`pf2:1`  **Requirements** The chakanaj is Bonded with a Host\n* * *\n\n**Effect** The chakanaj interposes itself between the host and its foes, granting its host a +2 circumstance bonus to AC until the start of the chakanaj's next turn.\n\n[[Bestiary Effects/Effect_ Interpose|Effect: Interpose]]"

  - name: "Peel Away"
    desc: "`pf2:1` (concentrate,move) **Requirements** The chakanaj is Bonded with a Host\n* * *\n\n**Effect** the chakanaj removes itself from its host, peeling off the host's body and enters an adjacent space."

  - name: "Skip Between"
    desc: "`pf2:1` (divine,teleportation) The chakanaj sahkil moves from the Material Plane to the Ethereal Plane or vice versa, with the effects of [[Spells/Ethereal Jaunt|Ethereal Jaunt]] except the effect has an unlimited duration and can be Dismissed. A summoned sahkil can't use Skip Between."
 
```

```encounter-table
name: Chakanaj
creatures:
  - 1: Chakanaj
```




