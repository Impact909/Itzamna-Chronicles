---
title: "Corpselight"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W4jqGfSE8yKDU5pN" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Corpselight"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #163: Ruins of Gauntlight"
name: "Corpselight"
level: "Creature 2"
rare_03: [[Rare]]
alignment: ""
size: "tiny"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[undead]]
trait_04: [[unholy]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision"
languages: "Common, Necril"
skills:
  - name: "Skills"
    desc: "Athletics: +7, Intimidation: +8, Stealth: +8"
abilityMods: [3, 4, 1, 1, 1, 2]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder #163: Ruins of Gauntlight_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +5, __Ref__ +10, __Will__ +7"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40, void healing; __Immunities__  death effects,  disease,  fear effects,  paralyzed,  poison,  precision,  unconscious"
abilities_top:
  - name: ""

  - name: "Corpse Sense (Precise) 30 feet"
    desc: "  A corpselight can sense dead bodies within range. This is a precise sense that functions through solid barriers less than 5 feet thick."

abilities_mid:
  - name: ""
  - name: "Sunlight Powerlessness"
    desc: "  A corpselight exposed to sunlight is [[Conditions/Stunned|Stunned 2]] and [[Conditions/Clumsy|Clumsy 2]], and cannot Claim a Corpse."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Wisp Form"
    desc: "  When a corpselight is reduced to 0 Hit Points while merged with a corpse, it is instead reduced to 1 Hit Point as the corpse collapses to the ground and the corpselight emerges in its wisp form.\n\nWhile in wisp form, a corpselight is Tiny and can take no actions other than Claim Corpse or Fly.\n\nA corpselight that starts its turn in wisp form must attempt a DC 16 Flat check at the end of its turn; if it fails, it loses 1 Hit Point. A corpselight reduced to 0 Hit Points while in wisp form is destroyed."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 ()\n__Damage__  1d8 + 6 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile)\n__Damage__  1d6 + 6 slashing"

  - name: "Claim Corpse"
    desc: "`pf2:1`  **Prerequisites** The corpselight is in wisp form and is adjacent to a Medium or Small corpse that hasn't been claimed by a corpselight in the past 24 hours\n* * *\n\n**Effect** The corpselight merges with the corpse, causes the corpse to Stand, and regains 3d6 healing Hit Points.\n\n[[Bestiary Effects/Effect_ Claim Corpse - Fleshy|Effect: Claim Corpse - Fleshy]]\n\n[[Bestiary Effects/Effect_ Claim Corpse - Skeletal|Effect: Claim Corpse - Skeletal]]"

  - name: "Death Light"
    desc: "`pf2:3` (emotion,fear,mental,occult) **Prerequisites** The corpselight is in a corpse\n* * *\n\n**Effect** The corpselight emits a sickly blue beam of light from its mouth and eyes in a 20-foot cone. All living creatures in this area must attempt a DC 18 Fortitude check saving throw. If at least 1 creature fails its save, the corpselight regains 2d6 healing Hit Points, gaining any that exceed its maximum as temporary Hit Points that last for 1 minute.\n\nThe corpselight can't use again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 1d6 void damage.\n\n**Failure** The creature takes 2d6 void damage and is [[Conditions/Frightened|Frightened 1]].\n\n**Critical Failure** The creature takes 4d6 void damage and is [[Conditions/Frightened|Frightened 3]]."
 
```

```encounter-table
name: Corpselight
creatures:
  - 1: Corpselight
```



A will-o'-wisp that starves to death might rise as a cold, blue, glowing sphere of spongy wetness-a corpselight. A corpselight instinctively seeks out a host corpse to dwell within, as its physical form quickly deteriorates if not hidden within a dead creature.
