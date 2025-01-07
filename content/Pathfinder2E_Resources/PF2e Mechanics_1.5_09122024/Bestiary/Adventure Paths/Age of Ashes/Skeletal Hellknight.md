---
title: "Skeletal Hellknight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.OYAGLbpv9UHuBpdn" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/lawful
  - pf2e/creature/type/skeleton
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Skeletal Hellknight"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #145: Hellknight Hill"
name: "Skeletal Hellknight"
level: "Creature 2"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[lawful]]
trait_03: [[skeleton]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Common, Diabolic"
skills:
  - name: "Skills"
    desc: "Athletics: +9, Intimidation: +7"
abilityMods: [4, 2, 3, -1, 0, 1]
speed: 25 feet,  climb 25 feet
sourcebook: "_Pathfinder #145: Hellknight Hill_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +9, __Ref__ +8, __Will__ +4"
hp: 25
health:
  - name: ""
  - name: HP
    desc: "25, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Halberd|+1 Halberd]], [[Equipment/Half Plate|Half Plate]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Halberd"
    desc: "+11 (reach 10 feet, versatile s)\n__Damage__  1d10 + 4 piercing plus invoke-reckoning"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d6 + 4 slashing"

  - name: "Command Skeletons"
    desc: " (divine) The skeletal Hellknight can direct the actions of the nearby skeleton guards, commanding them to perform tactics such as flanking foes and focusing their attacks on specific targets. As long as the skeletal Hellknight is active and commanding the skeletons, they gain the [[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]] reaction."

  - name: "Invoke Reckoning"
    desc: "`pf2:r` (divine,mental) **Trigger** The skeletal Hellknight hits a foe with a Strike.\n* * *\n\n**Effect** The skeletal Hellknight causes the creature struck to endure the pain of an Order of the Nail's reckoning-a rite of mortification Hellknights of that order use to focus their minds. The creature struck feels as if nails are being driven into their body, and must succeed at a DC 17 Will check save or be [[Conditions/Stunned|Stunned 1]] from the pain. On a critical failure, the pain manifests as actual puncture wounds, dealing an additional 2d6 piercing damage to the victim."
 
```

```encounter-table
name: Skeletal Hellknight
creatures:
  - 1: Skeletal Hellknight
```




