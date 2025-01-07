---
title: "Eseneth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7oB16jihkuGQ6OtT" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/psychopomp
  - pf2eMonster
  - pf2e/creature/level/17
statblock: inline
name: "Eseneth"
level: 17
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #186: Ghost King&#x27;s Rage"
name: "Eseneth"
level: "Creature 17"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[monitor]]
trait_02: [[psychopomp]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Lifesense 120 Feet"
languages: "Chthonian, Diabolic, Empyrean, Requian"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Athletics: +33, Medicine: +31, Stealth: +33, Boneyard Lore: +29, Sewing Lore: +35"
abilityMods: [8, 8, 5, 6, 4, 2]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder #186: Ghost King&#x27;s Rage_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +28, __Ref__ +32, __Will__ +27"
hp: 290
health:
  - name: ""
  - name: HP
    desc: "290; __Immunities__  death effects,  disease; __Resistances__ void 15, poison 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 120 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Sudden Stitch"
    desc: "`pf2:r`  **Trigger** A creature within the eseneth's reach successfully Strikes the eseneth\n* * *\n\n**Effect** The eseneth attempts to [[/act grapple]] the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spirit Needle"
    desc: "+33 ()\n__Damage__  3d10 + 14 piercing plus improved-grab,spirit-touch"

  - name: "**Ranged** `pf2:1` Spirit Needle"
    desc: "+33 (thrown 30 ft.)\n__Damage__  3d10 + 14 piercing plus spirit-touch"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __8th __  _[[Spells/Spirit Blast|Spirit Blast (x3)]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __2nd __  _[[Spells/Invisibility|Invisibility (At Will, Self Only)]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "Mend Soul"
    desc: "`pf2:1` (manipulate) **Frequency** once per round\n* * *\n\n**Effect** The eseneth restores 25 healing HP to itself or an incorporeal creature it has [[Conditions/Grabbed|Grabbed]]."

  - name: "Seize Soul"
    desc: "`pf2:1` (attack,incapacitation) The eseneth tries to yank the soul out of the body of a creature they've [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]. The eseneth attempts an Athletics check check against the target's Fortitude DC.\n* * *\n\n**Critical Success** The eseneth grabs the target's soul. The body is released and is [[Conditions/Paralyzed|Paralyzed]] for 2 rounds. When the body ceases being paralyzed, its soul returns instantly and the target wakes. The soul—grabbed by the eseneth—is incorporeal, is [[Conditions/Invisible|Invisible]], has a fly Speed equal to the creature's Speed, and otherwise has all the same statistics. It can't attack, cast spells, or attempt any skill checks that require a physical body other than checks to [[Actions/Escape|Escape]], and it must always maintain line of effect to its body.\n\n**Success** As critical success, but the paralysis ends after 1 round.\n\n**Failure** The target remains grabbed or restrained, but its soul remains in its body.\n\n**Critical Failure** The grab ends."

  - name: "Shred Soul"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The eseneth deals 3d10+14 force damage to an incorporeal creature they've [[Conditions/Grabbed|Grabbed]]."

  - name: "Spirit Grasp"
    desc: "  An eseneth can [[Actions/Grapple|Grapple]] incorporeal creatures despite being corporeal. The eseneth uses their Athletics check to [[/act grapple]] incorporeal creatures as normal but can't use Athletics for other actions against incorporeal creatures, like [[Actions/Shove|Shove]] or [[Actions/Trip|Trip]]."

  - name: "Spirit Touch"
    desc: "  A eseneth's Strikes affect incorporeal creatures with the effects of a _[[Equipment/Ghost Touch|Ghost Touch]]_ property rune and deal 2d6 void damage to living creatures and 2d6 vitality damage to undead."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Eseneth
creatures:
  - 1: Eseneth
```



Eseneths, commonly known as soul-stitchers, are dispassionate surgeons who repair damaged souls.

* * *

Psychopomps preside over death and the cycle of souls.
