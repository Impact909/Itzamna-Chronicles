---
title: "Oregorger"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WFsWcGchMSACn6Nc" 
tags:
  - pf2e/creature/type/elemental
  - pf2e/creature/type/metal
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Oregorger"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Rage of Elements"
name: "Oregorger"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[elemental]]
trait_02: [[metal]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Talican"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +25"
abilityMods: [8, 2, 7, -1, 3, 3]
speed: 30 feet,  burrow 20 feet,  fly 20 feet
sourcebook: "_Pathfinder Rage of Elements_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +24, __Ref__ +17, __Will__ +20"
hp: 245
health:
  - name: ""
  - name: HP
    desc: "245; __Immunities__  bleed,  paralyzed,  poison,  sleep; __Resistances__ acid 10, electricity 10"
abilities_top:
  - name: ""

  - name: "Rust Vision"
    desc: "  An oregorger ignores the concealed condition from rust clouds."

abilities_mid:
  - name: ""
  - name: "Caustic Rust"
    desc: " (acid,aura) 5 feet.\n\nThe oregorger continually leaks tiny fragments of partially digested rust into the air around it. Any creature that ends its turn in the aura takes 2d6 acid damage with a DC 27 Reflex check save. A creature that critically fails is also [[Conditions/Sickened|Sickened 1]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Adamantine Bite"
    desc: "+23 (adamantine, reach 10 feet)\n__Damage__  2d12 + 12 piercing plus devour-metal"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile)\n__Damage__  2d6 + 12 slashing"

  - name: "Devour Metal"
    desc: "  Any time the oregorger scores a critical hit with an adamantine bite attack, it deals the same amount of damage to any metal armor worn by the target, automatically bypassing any Hardness lower than 10. If a creature uses the Shield Block reaction with a metal shield against an oregorger's adamantine bite, the shield is automatically broken, but no other item takes damage from that attack. Unattended metal items automatically take full damage from an oregorger's adamantine bite attack, ignoring their Hardness if it's lower than 10."

  - name: "Searing Spew"
    desc: "`pf2:2` (acid) The oregorger belches forth a cloud of caustic, rusted debris from its maw, filling a cube adjacent to itself that's 10-foot line feet on each side. Any creature in this area takes 6d6 acid + 6d6 slashing damage (DC 30 Reflex check). The ground under the cloud is difficult terrain for 1 hour, after which the shrapnel crumbles to dust.\n\nThe oregorger can't use Searing Spew again for 1d4 rounds, but the ability recharges if the oregorger damages an item with devour metal."
 
```

```encounter-table
name: Oregorger
creatures:
  - 1: Oregorger
```



Oregorgers are hulking, four-limbed brutes with bodies of raw primal metals accreted in layers. Driven entirely by an insatiable drive to consume metal, an oregorger stops at nothing to greedily devour as much metal as it can and expel it as caustic rust.
