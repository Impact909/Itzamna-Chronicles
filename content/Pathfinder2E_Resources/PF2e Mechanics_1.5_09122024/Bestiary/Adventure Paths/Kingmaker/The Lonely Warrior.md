---
title: "The Lonely Warrior"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.NPmUpiKBxjYL8FVD" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/wight
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "The Lonely Warrior"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "The Lonely Warrior"
level: "Creature 6"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[undead]]
trait_04: [[unholy]]
trait_05: [[wight]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Hallit, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Intimidation: +11, Religion: +9, Stealth: +12"
abilityMods: [4, 2, 4, 1, 3, 3]
speed: 25 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 23
armorclass:
  - name: AC
    desc: "23 25 with shield raised; __Fort__ +15, __Ref__ +13, __Will__ +14"
hp: 106
health:
  - name: ""
  - name: HP
    desc: "106, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bastard Sword|Broken +1 Cold Iron Flaming Bastard Sword]], [[Equipment/Wooden Shield|Wooden Shield]], [[Equipment/Chain Mail|Chain Mail]]"
abilities_mid:
  - name: ""
  - name: "Final Spite"
    desc: "`pf2:r`  **Trigger** The Lonely Warrior is reduced to 0 Hit Points\n* * *\n\n**Effect** The Lonely Warrior makes a Strike before being destroyed. It doesn't gain any temporary HP from drain life on this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bastard Sword"
    desc: "+18 (magical, two-hand d12)\n__Damage__  1d8 + 7 slashing plus drain-life"

  - name: "Cairn Wight Spawn"
    desc: " (divine) A living humanoid slain by the Lonely Warrior's weapon or claw Strike rises as a [[Monster Core/Wight|Spawned Wight]] after [[/gmr 1d4 #rounds]]{1d4 rounds}. This spawned wight is under the command of the Lonely Warrior. It doesn't have drain life or cairn wight spawn and is [[Conditions/Clumsy|Clumsy 2]] for as long as it is a spawned wight. If its creator dies, the spawned wight becomes a full-fledged, autonomous cairn wight; it regains its free will, gains drain life and cairn wight spawn, and is no longer clumsy."

  - name: "Drain Life"
    desc: " (divine) When The Lonely Warrior damages a living creature with a melee Strike, using an unarmed attack or its bound weapon, The Lonely Warrior gains 5 temporary Hit Points and the creature must succeed at a DC 21 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the cairn wraith increases the drained condition value by 1 on a failed save, to a maximum of drained 4."

  - name: "Funereal Dirge"
    desc: "`pf2:2` (auditory,divine,emotion,fear,mental) The cairn wight chants a low, haunting melody. Living creatures within 50 feet must attempt a DC 21 Will check save.\n\nThe cairn wight can't chant a new Funereal Dirge for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 2]] and takes a -2 status penalty to saving throws against drain life.\n\n[[Bestiary Effects/Effect_ Funereal Dirge|Effect: Funereal Dirge]]"

  - name: "Lonely Dirge"
    desc: "`pf2:2` (auditory,divine,emotion,fear,mental) The Lonely Warrior's funeral dirge is somewhat different from the standard cairn wight dirge: its droning, unnerving chant forces living creatures within 50 feet to attempt a DC 24 Will check save. The Lonely Warrior can't chant a new Lonely Dirge for 1d4 rounds.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Stupefied|Stupefied 1]] by gnawing pangs of loneliness until the end of its next turn.\n\n**Failure** The target is stupefied 1 for 1 hour.\n\n**Critical Failure** The target is stupefied 1 for 24 hours and takes a -2 status penalty to saves against drain life."
 
```

```encounter-table
name: The Lonely Warrior
creatures:
  - 1: The Lonely Warrior
```


Variant cairn wight

Jealous guardians of tombs, barrows, and sepulchers, cairn wights usually spawn from necromantic rituals. For those mortals who cannot abide the thought of separation from their earthly possessions, the undead existence offered by transformation into a cairn wight can be tempting. Perhaps as frequently, particularly avaricious and wealthy royalty or merchants seek out victims to transform into cairn wights to guard their precious wealth for all time.

Only in the rarest instances is the greed of a mortal strong enough to spontaneously transform them into a cairn wight without a dark ritual or the intercession of a powerful divine being. On those occasions, however, the resultant wight exhibits unmatched viciousness and likely owns rare treasure indeed.

As guardians of material possessions, cairn wights are supernaturally bound to the armaments they wore during the ritual used to create them. They can spread their necromantic powers into the weapons they wield. A slash from a cairn wight's sword channels life from the victim into the wight.
