---
title: "Ndede"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MJr5oy9HkW6TksFw" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Ndede"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #190: The Choosing"
name: "Ndede"
level: "Creature 15"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +24, Athletics: +26, Crafting: +24, Deception: +29, Intimidation: +29, Occultism: +22, Stealth: +26"
abilityMods: [7, 5, 5, 3, 4, 6]
speed: 30 feet,  climb 30 feet,  fly 80 feet
sourcebook: "_Pathfinder #190: The Choosing_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +26, __Ref__ +24, __Will__ +27"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  disease,  sickened,  stunned"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Stench"
    desc: " (aura,olfactory) 30 feet. A creature entering the aura or starting its turn in the aura must succeed at a DC 34 Fortitude check save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] for as long as it's sickened on a critical failure).\n\nWhile within the aura, affected creatures take a -2 circumstance penalty to saves against disease and to recover from the sickened condition.\n\nA creature that succeeds at its save is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Stench|Effect: Stench]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 ()\n__Damage__  3d10 + 15 piercing plus shameful-loathing 1d10 mental plus shameful-loathing"

  - name: "**Melee** `pf2:1` Talon"
    desc: "+30 (agile)\n__Damage__  3d10 + 15 slashing plus grab"

  - name: "Occult Innate Spells"
    desc: "DC 36, attack +28; __6th __  _[[Spells/Animated Assault|Animated Assault]]_, _[[Spells/Dominate|Dominate]]_; __5th __  _[[Spells/Clairaudience|Clairaudience (At Will)]]_, _[[Spells/Clairvoyance|Clairvoyance (At Will)]]_, _[[Spells/Telekinetic Haul|Telekinetic Haul]]_, _[[Spells/Telekinetic Maneuver|Telekinetic Maneuver]]_, _[[Spells/Ventriloquism|Ventriloquism (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The popobawa can take on the appearance of a human or a Small or Medium bat. It loses its stench aura while transformed. In human form it also loses its Strikes but can make fist Strikes that deal the same amount of bludgeoning damage as its talon Strike.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Feed on Sorrow"
    desc: "`pf2:1` (concentrate,healing,occult,vitality) **Frequency** once per round\n* * *\n\n**Effect** The popobawa draws strength from the suffering of others. It regains 10 healing Hit Points for each enemy within 30 feet feet that has one of the following conditions, to a maximum of 40 Hit Points: [[Conditions/Confused|Confused]], [[Conditions/Doomed|Doomed]], [[Conditions/Dying|Dying]], [[Conditions/Enfeebled|Enfeebled]], [[Conditions/Fatigued|Fatigued]], [[Conditions/Frightened|Frightened]], [[Conditions/Sickened|Sickened]], [[Conditions/Slowed|Slowed]], [[Conditions/Stunned|Stunned]], [[Conditions/Stupefied|Stupefied]], or [[Conditions/Wounded|Wounded]]."

  - name: "Hallucinatory Haunting"
    desc: "  **Trigger** The popobawa moves an object with [[Spells/Telekinetic Hand|Telekinetic Hand]] or [[Spells/Telekinetic Haul|Telekinetic Haul]], controls a creature with [[Spells/Dominate|Dominate]], or casts [[Spells/Animated Assault|Animated Assault]]\n* * *\n\n**Effect** The popobawa casts [[Spells/Ghost Sound|Ghost Sound]] or [[Spells/Ventriloquism|Ventriloquism]], with the sound originating from the target or area of the spell."

  - name: "Shameful Loathing"
    desc: " (curse,emotion,mental,occult) A creature damaged by the popobawa's jaws is overcome with shame and self-hatred and must attempt a DC 36 Will check save.\n* * *\n\n**Success** The target is unaffected.\n\n**Failure** The target becomes [[Conditions/Stupefied|Stupefied 1]] until the curse is removed.\n\n**Critical Failure** As failure, but the target is also [[Conditions/Doomed|Doomed 1]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ndede
creatures:
  - 1: Ndede
```


Male popobawa

Cruel shapechangers, popobawas feed on negative emotions, particularly fear, despair, and anguish. Though they're dangerously strong carnivores that drink the blood of their victims, their greatest pleasure lies in mesmerizing victims to cause suffering and spread chaos. A popobawa moves about populated areas in disguise, seeking new victims and revisiting past victims to bask in their suffering, spreading gossip and incriminating innocents for its crimes while still relishing its own loathsome infamy.
