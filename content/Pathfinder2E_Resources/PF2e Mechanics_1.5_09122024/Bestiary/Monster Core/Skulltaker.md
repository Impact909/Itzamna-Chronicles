---
title: "Skulltaker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QS7Jp1k7l4WCPyjK" 
tags:
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
  - remaster
statblock: inline
name: "Skulltaker"
level: 18
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Skulltaker"
level: "Creature 18"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[undead]]
trait_02: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Truesight"
languages: "Necril; Skeletal Lore languages"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Intimidation: +35, Religion: +30, Stealth: +32, Skeletal Lore: +30"
abilityMods: [8, 6, 6, 2, 8, 7]
speed: 30 feet,  fly 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +31, __Ref__ +33, __Will__ +35; +1 status to all saves vs. vitality"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300, void healing; __Immunities__  cold,  death effects,  disease,  paralyzed,  poison,  unconscious,  bleed; __Resistances__ piercing 15, slashing 15"
abilities_top:
  - name: ""

  - name: "Skeletal Lore"
    desc: " (divine) A skulltaker taps into the memories of the creatures whose bones make up its body. This gives it the Skeletal Lore skill, which it can use to Recall Knowledge of any kind. In addition, it can speak and understand all the languages known by the creatures whose bones make up its body (typically including Common and the regional language of the skulltaker's home region).\n\nThe skulltaker can use Skeletal Lore as the primary skill check for the [[Spells/Collective Memories|Collective Memories]] ritual, and it can cast _collective memories_ without secondary casters."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Shard Storm"
    desc: " (air,aura,divine) 10 feet.\n\nA cloud of bone shards surrounds the skulltaker. When a creature moves into the emanation or begins its turn there, shard storm deals 4d6 slashing damage and 4d6 void damage to the creature, with a DC 40 Reflex check save.\n\nIf the creature has resistance or immunity to void damage, or an effect that protects it against death effects, or an effect that protects it against the doomed or drained condition, the creature must first succeed at a DC 40 Will check save or have all such benefits suppressed for 1 minute."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+35 (deadly 2d12, magical, reach 10 feet)\n__Damage__  3d10 + 14 piercing plus energy-drain 3d6 void plus energy-drain"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+35 (agile, deadly 2d12, magical, reach 15 feet)\n__Damage__  3d6 + 14 slashing plus energy-drain 3d6 void plus energy-drain"

  - name: "**Ranged** `pf2:1` Bone Javelin"
    desc: "+33 (magical, thrown 100 ft.)\n__Damage__  3d8 + 6 piercing 3d6 void"

  - name: "Divine Innate Spells"
    desc: "DC 40, attack +32; __8th __  _[[Spells/Desiccate|Desiccate (x2)]]_, _[[Spells/Execute|Execute (x2)]]_, _[[Spells/Punishing Winds|Punishing Winds (x2)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "Rituals"
    desc: "_Collective Memories_"

  - name: "Bonetaker"
    desc: " (divine) Whenever a creature dies within 60 feet of a skulltaker, the skulltaker draws a portion of the creature's bones into its shard storm.\n\nThe creature must succeed at a DC 40 Will check save or rise as a [[Monster Core/Skeletal Champion|Skeletal Champion]] in 1d4 rounds. These skeletal champions are controlled by the skulltaker."

  - name: "Splintered Ground"
    desc: "`pf2:1`  The skulltaker causes splintered bones to erupt from all solid surfaces in a 100-foot emanation, except for surfaces of worked stone. A creature moving through the bones takes 10 piercing damage and 10 void damage for every 5 feet of movement.\n\nThe first time each round a creature takes piercing damage from these splintered bones, it must succeed at a DC 40 Reflex check save or take a –10-foot circumstance penalty to all Speeds for 10 minutes, or a –15-foot circumstance penalty for 24 hours on a critical failure.\n\nThe bones remain in place until the skulltaker uses this action again or the bones are manually removed, which takes 10 minutes for each 5-foot square.\n\n[[Bestiary Effects/Effect_ Splintered Ground|Effect: Splintered Ground]]\n\n[[Bestiary Effects/Effect_ Splintered Ground (Critical Failure)|Effect: Splintered Ground (Critical Failure)]]"

  - name: "Vitality Drain"
    desc: " (divine) When a skulltaker hits with a melee Strike, the target must succeed at a DC 40 Fortitude check save or become [[Conditions/Drained|Drained 2]] and [[Conditions/Doomed|Doomed 1]]."
 
```

```encounter-table
name: Skulltaker
creatures:
  - 1: Skulltaker
```



Swirling down from misty peaks and through howling mountain passes like an evil wind, the vortex of bones known as a skulltaker is a terrible manifestation of the delirium and agony experienced by doomed climbers and lost trailblazers just before they met their end. In some places, a skulltaker is also known as a saxra.
