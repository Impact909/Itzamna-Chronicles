---
title: "Corpseroot"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.E3VgvoUXeGJgbbXi" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Corpseroot"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Corpseroot"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Arboreal, Fey, Necril; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Stealth: +18"
abilityMods: [7, 3, 5, -2, 3, 2]
speed: 20 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +24, __Ref__ +18, __Will__ +18"
hp: 225
health:
  - name: ""
  - name: HP
    desc: "225, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ axe vulnerability 10, fire 10; __Resistances__ bludgeoning 10, piercing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Axe Vulnerability"
    desc: "  The corpseroot takes 10 additional damage from axes."

  - name: "Blight"
    desc: " (aura,poison,primal) 30 feet. A plant entering or starting its turn in the corpseroot's aura begins to wither and must succeed at a DC 27 Fortitude check save or become [[Conditions/Sickened|Sickened 2]] ([[Conditions/Sickened|Sickened 4]] on a critical failure). A plant that succeeds is temporarily immune for 1 minute.\n\nA plant that stays in the aura for 7 consecutive days must succeed at a DC 27 Fortitude check save or die. If the plant was a creature or tree, it rises as a corpseroot. The newly risen corpseroot can't create more corpseroots but has all other corpseroot abilities. Plants that are neither magical nor creatures automatically fail saves against blight."

  - name: "Plant"
    desc: "  When it isn't in danger, the corpseroot spends 1 minute rooting to the earth, becoming planted in place. While the corpseroot is planted and immobile, creatures must actively [[Actions/Seek|Seek]] and succeed at a DC 36 Perception check check (DC 40 Perception check in forests) to detect the corpseroot's true nature."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Branch"
    desc: "+24 (reach 15 feet)\n__Damage__  3d12 + 10 bludgeoning"

  - name: "**Melee** `pf2:1` Root"
    desc: "+24 (agile, reach 20 feet, trip)\n__Damage__  3d8 + 10 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Rotten Fruit"
    desc: "+20 (range increment 20 feet, splash)\n__Damage__  3d4 + 7 bludgeoning 2d6 poison"

  - name: "Take Root"
    desc: "`pf2:1` (primal) **Frequency** once per round\n\n**Requirements** The corpseroot has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The corpseroot buries its roots into the creature, dealing 1d6+11 piercing damage and draining the target's life force (DC 30 Fortitude check). On a failure, the creature is [[Conditions/Drained|Drained 1]] (or increases the value by 1 if already drained), and the corpseroot regains 10 healing HP. If this would make a creature drained 5, the creature dies."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Corpseroot
creatures:
  - 1: Corpseroot
```



Corpseroots are rotten, undead trees that grow bright-red poisonous fruit and spread blight to surrounding plants, transforming healthy trees into new corpseroots. These cunning killers drain the life from creatures through their root systems, posing as dead trees until their victims come within reach.

Corpseroots most commonly form from rotten husks of trees that died from supernatural blights, making them common threats in the Fangwood and Fierani forests. The most powerful are ancient trees used as shrines and sacrificial altars, their roots absorbing the blood, flesh, and terror of those condemned under their boughs. Some of these ancient corpseroots still command the respect and devotion of the cults that inadvertently created them.
