---
title: "Thanatotic Titan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.vXSH7fSH7eMnQoR8" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/titan
  - pf2eMonster
  - pf2e/creature/level/22
statblock: inline
name: "Thanatotic Titan"
level: 22
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Thanatotic Titan"
level: "Creature 22"
rare_03: [[Rare]]
alignment: ""
size: "grg"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[titan]]
modifier: 36
perception:
  - name: "Perception"
    desc: "+36; Darkvision, Truesight"
languages: "Chthonian, Common, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +45, Crafting: +41, Deception: +36, Intimidation: +38, Religion: +38, Stealth: +36"
abilityMods: [10, 4, 9, 8, 6, 8]
speed: 40 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 46
armorclass:
  - name: AC
    desc: "46; __Fort__ +37, __Ref__ +34, __Will__ +35; +4 status to all saves vs. mental or divine"
hp: 540
health:
  - name: ""
  - name: HP
    desc: "540; __Immunities__  death effects,  disease"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Halberd|+3 Greater Striking Halberd]], [[Equipment/Full Plate|+2 Greater Resilient Full Plate]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Special)]]"
    desc: "`pf2:r`  The titan can use their Attack of Opportunity when a creature within their reach uses a concentrate action, in additional to its normal trigger. They disrupt actions on any hit, not just a critical hit—including triggering concentrate actions.\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Impossible Stature"
    desc: " (aura,divine,illusion,mental) 100 feet. Titans warp perception and distance around them to seem even larger and more imposing. A creature that enters or begins its turn within the emanation must succeed at a DC 45 Will check save or its movement toward the titan is movement over difficult terrain (greater difficult terrain on a critical failure) for 1 round."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Halberd"
    desc: "+42 (magical, reach 40 feet, versatile s)\n__Damage__  4d10 + 25 piercing"

  - name: "**Melee** `pf2:1` Foot"
    desc: "+39 (agile, reach 30 feet)\n__Damage__  4d8 + 20 bludgeoning"

  - name: "**Ranged** `pf2:1` Rock"
    desc: "+39 (brutal, range increment 200 feet)\n__Damage__  3d12 + 20 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 45, attack +37; __10th __  _[[Spells/Massacre|Massacre]]_, _[[Spells/Falling Stars|Meteor Swarm]]_; __8th __  _[[Spells/Dispel Magic|Dispel Magic (At Will)]]_, _[[Spells/Spiritual Epidemic|Spiritual Epidemic (At Will)]]_, _[[Spells/Suggestion|Suggestion (At Will)]]_; __7th __  _[[Spells/Spell Turning|Spell Turning]]_; __6th __  _[[Spells/Scrying|Scrying (x3)]]_; __5th __  _[[Spells/Sending|Sending]]_\n__Constant__  __(10th)__ _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Planar Ally_, _Resurrect_"

  - name: "Godslayer"
    desc: " (divine) **Trigger** The titan damages a creature capable of using divine spells or abilities\n* * *\n\n**Effect** The creature must attempt a DC 45 Will check save.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature can't use divine spells or abilities for 1 round and is [[Conditions/Frightened|Frightened 2]]. Only powerful non-divine magic, such as [[Spells/Wish|Wish]], can undo this effect.\n\n**Failure** As success, but the duration is 1 minute.\n\n**Critical Failure** As success, but the duration is unlimited."

  - name: "[[Bestiary Ability Glossary/Throw Rock|Throw Rock]]"
    desc: "`pf2:1`  If a titan's rock Strike isn't a critical failure, the rock explodes, dealing 10d6 damage of a damage type of the titan's choice to all creatures in a 20-foot burst (DC 45 Reflex check save).\n* * *\n\nThe monster picks up a rock within reach or retrieves a stowed rock and throws it, making a ranged Strike."

  - name: "Titanic Charge"
    desc: "`pf2:2`  The titan Strides twice and makes a melee Strike. If the Strike hits, the titan can cast [[Spells/Earthquake|Earthquake]] centered on the target as a free action."

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Huge or smaller, foot, DC 45 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."

  - name: "Wide Cleave"
    desc: "`pf2:2`  The titan makes a melee weapon Strike against each foe within their reach. This counts as three attacks for the titan's multiple attack penalty."
 
```

```encounter-table
name: Thanatotic Titan
creatures:
  - 1: Thanatotic Titan
```



Thanatotic titans served as assassins in the war against the deities. They learned to sever their targets' divine connections, murdering mortal priests and divine heralds alike. Thanatotic titans were locked away in the Abyss, but some have freed themselves and crept out from the Abyss so they might continue their sprees of murder and mayhem. To this day, they seek out the faithful for slaughter.

* * *

Created by ancient deities long before the rise of mortal ancestries, titans united and attempted to overthrow their deific progenitors. The resulting war still figures prominently throughout mortal myths, in which most titans were cast down and imprisoned for eons.
