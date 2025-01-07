---
title: "Oracle of Zagresh"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.36Yya055F66TMJ09" 
tags:
  - pf2e/creature/type/dromaar
  - pf2e/creature/type/human
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/orc
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Oracle of Zagresh"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Oracle of Zagresh"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[dromaar]]
trait_02: [[human]]
trait_03: [[humanoid]]
trait_04: [[orc]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; "
languages: "Common, Orcish"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Intimidation: +20, Religion: +19, Stealth: +18"
abilityMods: [4, 2, 2, 1, 3, 6]
speed: 25 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +16, __Ref__ +18, __Will__ +20"
hp: 172
health:
  - name: ""
  - name: HP
    desc: "172, curse of the destroyer&#x27;s bloodlust"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "10x [[Equipment/Javelin|Javelin]], [[Equipment/Orc Necksplitter|+1 Striking Orc Necksplitter]], [[Equipment/Scale Mail|+1 Scale Mail]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Ferocity|Ferocity]]"
    desc: "`pf2:r`  **Trigger** The monster is reduced to 0 HP.\n* * *\n\n**Effect** The monster avoids being knocked out and remains at 1 HP, but its [[Conditions/Wounded|Wounded]] value increases by 1. When it is Wounded 3, it can no longer use this ability"

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Orc Necksplitter"
    desc: "+23 (forceful, magical, sweep)\n__Damage__  2d8 + 6 slashing"

  - name: "**Ranged** `pf2:1` Javelin"
    desc: "+21 (thrown 30 ft.)\n__Damage__  2d6 + 6 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (acid, agile)\n__Damage__  2d8 + 6 slashing plus destructive-touch"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 (acid)\n__Damage__  2d8 + 6 piercing plus destructive-touch"

  - name: "Divine Spontaneous Spells"
    desc: "DC 29, attack +21; __5th __ (2 slots) _[[Spells/Crisis of Faith|Crisis of Faith]]_, _[[Spells/Spiritual Armament|Spiritual Armament]]_; __4th __ (3 slots) _[[Spells/Divine Wrath|Divine Wrath]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_; __3rd __ (3 slots) _[[Spells/Bane|Bane]]_, _[[Spells/Blindness|Blindness]]_, _[[Spells/Crisis of Faith|Crisis of Faith]]_; __2nd __ (3 slots) _[[Spells/Deafness|Deafness]]_, _[[Spells/Revealing Light|Revealing Light]]_, _[[Spells/Spiritual Armament|Spiritual Armament]]_; __1st __ (3 slots) _[[Spells/Bane|Bane]]_, _[[Spells/Runic Body|Runic Body]]_, _[[Spells/Runic Weapon|Runic Weapon]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Forbidding Ward|Forbidding Ward]]_, _[[Spells/Guidance|Guidance]]_, _[[Spells/Shield|Shield]]_, _[[Spells/Stabilize|Stabilize]]_"

  - name: "Divine Focus Spells"
    desc: "2 Focus Points, DC 28, attack +20; __5th __  _[[Spells/Battlefield Persistence|Battlefield Persistence]]_, _[[Spells/Call to Arms|Call to Arms]]_"

  - name: "Curse of the Destroyer's Bloodlust"
    desc: "  After a turn where the oracle of Zagresh doesn't make a Strike, she takes a –2 status penalty to her AC and saving throws until she makes another Strike. During this penalty, she gains a +2 status bonus to her Strikes and fast healing 5."

  - name: "Destructive Touch"
    desc: "  **Requirements** Zagresh's Gaze is active\n* * *\n\n**Effect** The oracle's hands and tusks ooze acid, making a soft sizzling noise and dealing an additional 1d6 acid damage to her unarmed attacks."

  - name: "Zagresh's Gaze"
    desc: "`pf2:1`  **Frequency** once per day\n* * *\n\n**Effect** The oracle of Zagresh throws aside her weapons and focuses on the pure divine power of destruction. She attempts a DC 27 Will check save. On a success, she gains access to her claw and jaws Strikes. This effect lasts [[/gmr 1d4 #rounds]]{1d4 rounds}."
 
```

```encounter-table
name: Oracle of Zagresh
creatures:
  - 1: Oracle of Zagresh
```




