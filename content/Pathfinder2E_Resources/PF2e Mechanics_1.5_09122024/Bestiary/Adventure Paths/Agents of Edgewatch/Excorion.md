---
title: "Excorion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.EiQyG9jN5C4bEaKg" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Excorion"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Excorion"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +17, Stealth: +16"
abilityMods: [4, 5, 4, -3, 1, 0]
speed: 35 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +17, __Ref__ +18, __Will__ +14"
hp: 160
health:
  - name: ""
  - name: HP
    desc: "160, void healing; __Immunities__  death effects,  disease,  mental,  paralyzed,  poison,  unconscious; __Weaknesses__ vitality 10, slashing 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Vein Walker"
    desc: "  The excorion moves about by way of hundreds of pulsating blood vessels, which stretch from its body in dozens of tight, ropy bundles and anchor it to the ground. An excorion cannot be Tripped, Shoved, or otherwise forcibly moved except by magic, and the excorion ignores difficult terrain (but not greater difficult terrain)."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (agile, finesse)\n__Damage__  2d8 + 8 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Bloody Spew"
    desc: "+18 (range increment 20 feet)\n__Damage__  3d6 + 4 bludgeoning"

  - name: "Bloody Handprint"
    desc: "`pf2:1`  The excorion plants a magical handprint on the target, marking them as chosen for death. The excorion makes a fist Strike against an adjacent creature; this does not count toward the excorion's multiple attack penalty. On a hit, the attack does no damage, but the creature becomes observed to every excorion within 60 feet, even if an excorion's line of sight would be blocked by a wall or other obstacle. This effect lasts until the handprint is washed off, which requires water and spending 3 actions to fully clean off."

  - name: "Vital Transfusion"
    desc: "`pf2:2`  **Requirements** The excorion has at least 70 Hit Points\n* * *\n\n**Effect** The excorion sacrifices itself and transfers its bloody, vital energy to a willing living creature within 30 feet. The excorion is immediately destroyed, and the targeted living creature heals a number of HP equal to half the excorion's remaining HP at the time that it used this ability.\n\nThe living creature is [[Conditions/Slowed|Slowed 1]] during its next turn as its body adjusts to the newly transfused blood and vital energy; the living creature also counts as an excorion for 1 minute for the purpose of seeing other excorions' Bloody Handprint marks."

  - name: "Vomit Blood"
    desc: "`pf2:1`  The excorion spews necrotic blood all over a foe it has grabbed. The grabbed creature must succeed at a DC 25 Fortitude check save or become [[Conditions/Sickened|Sickened 2]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Excorion
creatures:
  - 1: Excorion
```




