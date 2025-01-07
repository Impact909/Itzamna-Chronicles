---
title: "Death Drider"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jIZapEonmDeCCenf" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Death Drider"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #155: Lord of the Black Sands"
name: "Death Drider"
level: "Creature 13"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 24
perception:
  - name: "Perception"
    desc: "+24; Darkvision"
languages: "Elven, Necril, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +30, Athletics: +28, Intimidation: +24, Stealth: +30"
abilityMods: [6, 8, 4, -1, 5, 4]
speed: 30 feet,  climb 30 feet
sourcebook: "_Pathfinder #155: Lord of the Black Sands_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +24, __Ref__ +26, __Will__ +23"
hp: 235
health:
  - name: ""
  - name: HP
    desc: "235, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Sack of Spiders"
    desc: "`pf2:r`  **Trigger** The death drider is reduced to 0 Hit Points\n* * *\n\n**Effect** The death drider explodes in a shower of spiders. Each adjacent creature must succeed at a DC 31 Reflex check save or take 3d6 piercing damage and be exposed to death drider venom."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+27 ()\n__Damage__  4d6 + 13 piercing plus death-drider-venom"

  - name: "**Ranged** `pf2:1` Web"
    desc: "+27 (range increment 30 feet)\n__Damage__ "

  - name: "Death Drider Venom"
    desc: " (poison) The drained condition persists after the poison's duration ends\n\n**Saving Throw** DC 32 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d8 poison damage and [[Conditions/Drained|Drained 1]] (1 round)\n\n**Stage 2** 3d8 poison damage and [[Conditions/Drained|Drained 2]] (1 round)\n\n**Stage 3** 4d8 poison damage and drained 2 (1 round)"

  - name: "Hungering Web"
    desc: "  A creature hit by a death drider's web attack is [[Conditions/Immobilized|Immobilized]] and stuck to the nearest surface ([[Actions/Escape|Escape]] DC 31). Each round thereafter until it breaks free, the creature takes 3d6 piercing damage(DC 31 Reflex check save) and, on a failed save, is exposed to death drider venom."
 
```

```encounter-table
name: Death Drider
creatures:
  - 1: Death Drider
```


Variant drider


