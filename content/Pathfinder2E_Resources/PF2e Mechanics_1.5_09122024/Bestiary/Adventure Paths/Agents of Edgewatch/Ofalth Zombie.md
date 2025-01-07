---
title: "Ofalth Zombie"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.i8qxANNFfa9M4UyA" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2e/creature/type/mindless
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2e/creature/type/zombie
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Ofalth Zombie"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Ofalth Zombie"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[evil]]
trait_03: [[mindless]]
trait_04: [[undead]]
trait_05: [[unholy]]
trait_06: [[zombie]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +20"
abilityMods: [7, 3, 6, -5, 0, 2]
speed: 30 feet
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +18, __Ref__ +11, __Will__ +13"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious,  mental; __Weaknesses__ vitality 10, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Corpse Wallow"
    desc: "  The ofalth zombie gains fast healing 2 as long as it is in the Catacombs or another area with a high concentration of dead."

  - name: "Rotting Aura"
    desc: " (aura,disease) 10 feet. The zombie emits an aura of rot and disease that causes wounds to fester and turn sour. Any living creature that starts its turn within 10 feet of the Ofalth Zombie and is not at full Hit Points takes 1d6 damage as its wounds fester.\n\nCreatures that take a critical hit from the Ofalth Zombie also take this damage immediately.\n* * *\n\n_Note: This ability lists a DC 24 in the source, but the glossary ability lacks a save to make._"

  - name: "Slow"
    desc: "  The ofalth zombie is permanently [[Conditions/Slowed|Slowed 1]] and can't use reactions."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+18 (reach 10 feet)\n__Damage__  2d8 + 11 bludgeoning plus wretched-weeps"

  - name: "**Ranged** `pf2:1` Fling Offal"
    desc: "+17 (range increment 30 feet)\n__Damage__  2d6 + 11 bludgeoning plus wretched-weeps"

  - name: "Bury in Offal"
    desc: "`pf2:1`  The ofalth zombie makes a fling offal Strike and compares the attack roll result to the AC of any foes within the area of a 15-foot cone emanating from the ofalth zombie. This counts as two attacks for the ofalth zombie's multiple attack penalty.\n\nThe ofalth zombie can't use Bury in Offal again until it moves at least 10 feet to a different space."

  - name: "Wretched Weeps"
    desc: " (disease) **Saving Throw** DC 22 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 day)\n\n**Stage 2** 2d8 bleed every hour and [[Conditions/Enfeebled|Enfeebled 1]] (1 day)\n\n**Stage 3** 2d8 bleed every hour and [[Conditions/Enfeebled|Enfeebled 2]] (1 day)"
 
```

```encounter-table
name: Ofalth Zombie
creatures:
  - 1: Ofalth Zombie
```




