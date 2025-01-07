---
title: "Skeletal Knight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.B5Jsy1CFNoBUeL1q" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Skeletal Knight"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #183: Field of Maidens"
name: "Skeletal Knight"
level: "Creature 8"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[mindless]]
trait_03: [[skeleton]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +18"
abilityMods: [6, 4, 3, -5, 0, 0]
speed: 20 feet
sourcebook: "_Pathfinder #183: Field of Maidens_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +17, __Ref__ +16, __Will__ +14"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110, void healing; __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Resistances__ cold 10, electricity 10, fire 10, piercing 10, slashing 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Lance|+1 Striking Lance]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Full Plate|Full Plate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Lance"
    desc: "+20 (deadly d8, jousting d6, magical, reach 10 feet)\n__Damage__  2d8 + 12 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 (agile, finesse)\n__Damage__  2d4 + 12 slashing"

  - name: "Lancer"
    desc: "  The skeletal knight uses a lance in one hand, even when it isn't mounted. If the skeletal knight critically hits a creature with its lance Strike, the target is [[Conditions/Clumsy|Clumsy 1]] until the start of the skeletal knight's next turn."
 
```

```encounter-table
name: Skeletal Knight
creatures:
  - 1: Skeletal Knight
```




