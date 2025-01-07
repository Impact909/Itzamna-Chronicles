---
title: "Venexus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.iHz7vaaydldQm4F0" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/cold
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Venexus"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #176: Lost Mammoth Valley"
name: "Venexus"
level: "Creature 9"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[chaotic]]
trait_02: [[cold]]
trait_03: [[dragon]]
trait_04: [[evil]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision, Scent (Imprecise) 60 Feet"
languages: "Common, Draconic, Hallit"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Arcana: +17, Athletics: +21, Intimidation: +19, Stealth: +15"
abilityMods: [6, 2, 4, 2, 3, 2]
speed: 30 feet,  fly 120 feet
sourcebook: "_Pathfinder #176: Lost Mammoth Valley_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +21, __Ref__ +15, __Will__ +17; +1 status to all saves vs. magic"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  cold,  paralyzed,  sleep"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Primordial Flame|Primordial Flame]]"
abilities_mid:
  - name: ""
  - name: "Freezing Blood"
    desc: "`pf2:r` (arcane,cold) **Trigger** An adjacent creature deals piercing or slashing damage to Venexus\n* * *\n\n**Effect** Venexus's blood splatters onto the triggering creature, dealing 2d6 cold damage. A creature that takes cold damage in this way is [[Conditions/Slowed|Slowed 1]] for 1 round."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 25 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Mist Shroud"
    desc: " (arcane,aura,water) 10 feet. The _Primordial Flame_ continually heats the cold emanating from Venexus's body, surrounding the dragon in a thin veil of fog. Creatures in the aura are [[Conditions/Concealed|Concealed]], and other creatures are concealed to creatures in the area. Venexus's storm vision allows her to see through this concealment, however. If wind disperses the aura, it returns automatically at the start of Venexus's turn. The aura is suppressed in water."

  - name: "Storm Vision"
    desc: "  Inclement weather doesn't impair Venexus's vision; she ignores concealment from fog, mist, rain, and snowfall."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (cold, magical, reach 10 feet)\n__Damage__  2d10 + 10 piercing 1d6 cold"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, magical)\n__Damage__  2d8 + 10 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+20 (magical, reach 15 feet)\n__Damage__  2d6 + 8 bludgeoning"

  - name: "Arcane Innate Spells"
    desc: "DC 25, attack +17; __2nd __ (1 slots) _[[Spells/Mist|Obscuring Mist (At Will)]]_; __1st __ (1 slots) _[[Spells/Gust of Wind|Gust of Wind (At Will)]]_"

  - name: "Primal Innate Spells"
    desc: "DC 25, attack +17; __7th __  _[[Spells/Sunburst|Sunburst]]_\n__Cantrips__  __(5th)__ _[[Spells/Produce Flame|Produce Flame]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (arcane,cold) Venexus breathes a cloud of frost that deals 10d6 cold damage in a 40-foot cone (DC 28 Reflex check). She can't use Breath Weapon again for 1d4 rounds."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  Venexus makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  When Venexus scores a critical hit with a Strike, she recharges her Breath Weapon."

  - name: "Ice Climb 30 feet"
    desc: "  Venexus can climb on ice as though she had the listed climb Speed. She ignores difficult terrain and greater difficult terrain from ice and snow and doesn't risk falling when crossing ice."

  - name: "Shape Ice"
    desc: "`pf2:2` (arcane,water) Venexus magically reshapes a cube of ice or snow she touches, up to 10 feet across. Any creature standing atop the ice must succeed at a DC 15 Reflex check save or Acrobatics check. On a failure, the creature falls [[Conditions/Prone|Prone]] on the ice; on a critical failure, it falls off the ice entirely and is also prone."

  - name: "Snuff"
    desc: "`pf2:1` (arcane,water) Venexus releases a wave of sleet, which douses open flames within 30 feet. All non-magical fire is automatically extinguished. All creatures in the area suffering from persistent fire damage immediately attempt a DC 10 Flat check to end the persistent damage. If Snuff overlaps with an ongoing fire effect, Snuff attempts to counteract the fire effect."
 
```

```encounter-table
name: Venexus
creatures:
  - 1: Venexus
```


Female young white dragon


