---
title: "Excorion Paragon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.BB6mry6aRE04uX3r" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Excorion Paragon"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #162: Ruins of the Radiant Siege"
name: "Excorion Paragon"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision"
languages: "Daemonic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Athletics: +32, Stealth: +32"
abilityMods: [6, 8, 7, -3, 4, 0]
speed: 40 feet
sourcebook: "_Pathfinder #162: Ruins of the Radiant Siege_"
ac: 41
armorclass:
  - name: AC
    desc: "41; __Fort__ +31, __Ref__ +32, __Will__ +26"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300, void healing; __Immunities__  paralyzed,  unconscious,  mental,  poison,  death effects,  disease; __Weaknesses__ vitality 15, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Trip Only)]]"
    desc: "`pf2:r`  [[Actions/Trip|Trip]] only\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Vein Walker"
    desc: "  The excorion moves about by way of hundreds of pulsating blood vessels, which stretch from its body in dozens of tight, ropy bundles and anchor it to the ground.\n\nAn excorion can't be [[Actions/Trip|Tripped]], [[Actions/Shove|Shoved]], or otherwise forcibly moved except by magic, and the excorion ignores difficult terrain (but not greater difficult terrain)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+34 (agile, finesse)\n__Damage__  3d8 + 14 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Bloody Spew"
    desc: "+34 (range increment 30 feet)\n__Damage__  5d6 + 7 bludgeoning"

  - name: "Blinding Bile"
    desc: "`pf2:2` (acid) The excorion paragon projects a mist of burning blood in a 10-foot cone.\n\nCreatures in the area take 10d8 acid damage and 5d8 bludgeoning damage (DC 37 Reflex check save).\n\nOn a failed save, an affected creature is also [[Conditions/Blinded|Blinded]] for 1 round (or 2 rounds on a critical failure).\n\nThe excorion can't use Blinding Bile again for 1d4 rounds."

  - name: "Vital Transfusion"
    desc: "`pf2:2`  **Requirements** The excorion has at least 200 Hit Points\n* * *\n\n**Effect** The excorion sacrifices itself and transfers its bloody, vital energy to a willing living creature within 30 feet. The excorion is immediately destroyed, and the targeted living creature heals a number of HP equal to half the excorion's remaining HP at the time that it used this ability.\n\nThe living creature is [[Conditions/Slowed|Slowed 1]] during its next turn as its body adjusts to the newly transfused blood and vital energy."

  - name: "Vomit Blood"
    desc: "`pf2:1`  The excorion spews necrotic blood all over a foe it has [[Conditions/Grabbed|Grabbed]].\n\nThe grabbed creature must succeed at a DC 39 Fortitude check save or become [[Conditions/Sickened|Sickened 2]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Excorion Paragon
creatures:
  - 1: Excorion Paragon
```




