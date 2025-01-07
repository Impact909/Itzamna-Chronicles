---
title: "Skinslough"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.HXYBVyJ70nwqt127" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Skinslough"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #207: The Resurrection Flood"
name: "Skinslough"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[amphibious]]
trait_02: [[undead]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +12"
abilityMods: [5, 2, 4, 2, 2, -4]
speed: 25 feet,  swim 20 feet
sourcebook: "_Pathfinder #207: The Resurrection Flood_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +14, __Ref__ +8, __Will__ +11"
hp: 72
health:
  - name: ""
  - name: HP
    desc: "72, hard to target, void healing; __Immunities__  bleed,  death effects,  disease,  paralyzed,  poison,  unconscious; __Weaknesses__ cold 6; __Resistances__ bludgeoning 6, piercing 6"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Hard to Target"
    desc: "  With their loose, shifting skin, a skinslough's vital organs are difficult to locate. Each time a skinslough would take precision damage or extra damage from a critical hit, it attempts a DC 5 Flat check. On a success, the additional damage is negated."

  - name: "Slough"
    desc: "`pf2:r`  **Trigger** The skinslough gains a persistent damage condition or becomes [[Conditions/Grabbed|Grabbed]], [[Conditions/Immobilized|Immobilized]], or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The skinslough sheds part of its skin and attempts a DC 5 Flat check to end the condition."

  - name: "Void Healing"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+13 (agile, disarm)\n__Damage__  2d8 + 5 bludgeoning plus sloughing-sickness"

  - name: "**Ranged** `pf2:1` Skin Net"
    desc: "+13 (range 30 feet)\n__Damage__ "

  - name: "Skin Net"
    desc: "`pf2:1` (attack,disease) The skinslough interacts to pull off part of its skin and throw it at a creature within 30 feet, making a ranged attack with a +12 modifier. If it hits, the target takes a –10-foot circumstance penalty to its Speeds for 1 round and must make a DC 18 Fortitude check save. If the skinslough critically hits, the target gets a result one degree of success worse than the outcome of its Fortitude save.\n\n[[Bestiary Effects/Effect_ Skin Net|Effect: Skin Net]]\n* * *\n\n**Critical Success** As success, and the creature automatically succeeds at saving throws against the skinslough's Skin Net for 24 hours.\n\n**Success** The target is unaffected except for the penalty to Speed.\n\n**Failure** The target is also [[Conditions/Sickened|Sickened 1]].\n\n**Critical Failure** The target is also [[Conditions/Sickened|Sickened 2]]."

  - name: "Sloughing Sickness"
    desc: " (disease,void) This horrifying disease can make a target's skin slough away.\n\n**Saving Throw** DC 18 Fortitude check\n\n**Stage 1** carrier with no ill effect (1 hour)\n\n**Stage 2** 2d4+4 void damage and [[Conditions/Clumsy|Clumsy 1]] (1 day)\n\n**Stage 3** 4d4+4 void damage, clumsy 1, and [[Conditions/Stupefied|Stupefied 1]] (1 day)."
 
```

```encounter-table
name: Skinslough
creatures:
  - 1: Skinslough
```




