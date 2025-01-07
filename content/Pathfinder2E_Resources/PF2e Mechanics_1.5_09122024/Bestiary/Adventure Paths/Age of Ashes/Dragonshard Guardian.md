---
title: "Dragonshard Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.t9cLHY0NdZ89l8Xj" 
tags:
  - pf2e/creature/type/construct
  - pf2eMonster
  - pf2e/creature/level/22
statblock: inline
name: "Dragonshard Guardian"
level: 22
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #150: Broken Promises"
name: "Dragonshard Guardian"
level: "Creature 22"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[construct]]
modifier: 39
perception:
  - name: "Perception"
    desc: "+39; Darkvision, Truesight"
languages: ""
skills:
  - name: "Skills"
    desc: "Arcana: +30"
abilityMods: [10, 8, 9, -5, 7, -5]
speed: 30 feet
sourcebook: "_Pathfinder #150: Broken Promises_"
ac: 48
armorclass:
  - name: AC
    desc: "48; __Fort__ +39, __Ref__ +36, __Will__ +33"
hp: 430
health:
  - name: ""
  - name: HP
    desc: "430; __Immunities__  mental,  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  nonlethal attacks,  paralyzed,  poison,  sickened,  spirit,  unconscious,  vitality,  void; __Weaknesses__ sonic 24; __Resistances__ fire 24, physical 24 (except adamantine bludgeoning)"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 42 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+41 (magical, reach 15 feet)\n__Damage__  6d10 + 8 piercing 2d10 bleed"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+41 (agile, magical, reach 10 feet)\n__Damage__  9d6 + 8 slashing"

  - name: "Innate Arcane Spells"
    desc: "DC 44, attack +36\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,fire) The construct breathes in one of two ways, then can't use Breath Weapon again for 1d4 rounds.\n\n- Flame (arcane, evocation, fire) A blast of flame deals 15d10 fire damage to all creatures in a 60-foot cone (DC 45 Reflex check save). This fire damage does not harm objects or constructs.\n\n- Weakening Gas (arcane, necromancy) A cloud of gold-flecked gas forces each creature in a 60-foot cone to attempt a DC 45 Fortitude check save; the effect lasts 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Enfeebled|Enfeebled 2]].\n\n**Failure** The creature is [[Conditions/Enfeebled|Enfeebled 5]].\n\n**Critical Failure** The creature is [[Conditions/Enfeebled|Enfeebled 8]]."

  - name: "Reverberating Revenge"
    desc: "`pf2:r` (arcane,fire) **Trigger** The dragonshard guardian takes cold, fire, electricity, or sonic damage from a non-dragonshard guardian source\n* * *\n\n**Effect** The dragonshard guardian's body absorbs the energy entirely, preventing the damage from harming the construct. Its body reverberates and transforms the absorbed energy before projecting it outward in a 60-foot burst.\n\nEach creature within the burst takes an amount of fire damage equal to the amount of energy damage absorbed by the triggering attack, including any damage resisted by the guardian's resistances and additional damage from its weakness (DC 45 Reflex check save).\n\nThis fire damage doesn't harm objects or constructs."
 
```

```encounter-table
name: Dragonshard Guardian
creatures:
  - 1: Dragonshard Guardian
```



Created by Mengkare and powered by a shard of the _[[Equipment/Orb of Dragonkind|Orb of Gold Dragonkind]]_, this construct is made of sculpted crystal draped in a beautiful gold filigree frame.
