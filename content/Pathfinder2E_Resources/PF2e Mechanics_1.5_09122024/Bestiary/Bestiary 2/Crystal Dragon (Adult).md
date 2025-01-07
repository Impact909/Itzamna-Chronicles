---
title: "Crystal Dragon (Adult)"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.KtuPGiaG1wTrxHgF" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2e/creature/type/good
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Crystal Dragon (Adult)"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Crystal Dragon (Adult)"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[earth]]
trait_03: [[elemental]]
trait_04: [[good]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision, Scent (Imprecise) 60 Feet, Tremorsense (Imprecise) 30 Feet"
languages: "Common, Draconic, Petran, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +24, Deception: +22, Intimidation: +22, Nature: +19, Stealth: +21, Survival: +20"
abilityMods: [7, 2, 5, 2, 3, 5]
speed: 50 feet,  burrow 35 feet,  fly 120 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +24, __Ref__ +19, __Will__ +20; +1 status to all saves vs. magic"
hp: 185
health:
  - name: ""
  - name: HP
    desc: "185; __Immunities__  paralyzed,  sleep; __Weaknesses__ sonic 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 90 feet. DC 30 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Twisting Tail"
    desc: "`pf2:r` (move) **Trigger** A creature within reach of the dragon's tail uses a move action or leaves a square during a move action it's using\n* * *\n\n**Effect** The dragon makes a tail Strike at the creature with a -2 penalty. If it hits, the dragon disrupts the creature's action."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+24 (reach 15 feet, sonic)\n__Damage__  2d8 + 13 slashing 3d6 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+24 (agile, magical, reach 10 feet)\n__Damage__  2d8 + 13 slashing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+22 (magical, reach 20 feet)\n__Damage__  1d10 + 13 slashing"

  - name: "Primal Innate Spells"
    desc: "DC 30, attack +22; __3rd __  _[[Spells/Dizzying Colors|Color Spray (x3)]]_, _[[Spells/Revealing Light|Glitterdust]]_, _[[Spells/Hypnotize|Hypnotic Pattern]]_\n__Cantrips__  __(5th)__ _[[Compendium.pf2e.spells-srd.Item.kl2q6JvBZwed4B6v|Dancing Lights]]_"

  - name: "Breath Weapon"
    desc: "`pf2:2` (primal) The dragon breathes a flurry of piercing crystals that deal 12d6 piercing damage in a 40-foot cone (DC 30 Reflex check save).\n\nThey can't use Breath Weapon again for 1d4 rounds."

  - name: "Crystallize Flesh"
    desc: " (primal) **Trigger** The crystal dragon damages a creature made of flesh with a jaws Strike\n\n**Frequency** once per day\n* * *\n\n**Effect** The dragon embeds transformative crystals in the creature's flesh. The creature must attempt a DC 30 Fortitude check save.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target is [[Conditions/Slowed|Slowed 1]] for 1 round as portions of its flesh turn crystalline.\n\n**Failure** The target is [[Conditions/Slowed|Slowed 1]] and must attempt a Fortitude save at the end of each of its turns; this ongoing save has the incapacitation trait. On a failed save, the slowed condition value increases by 1 (or by 2 on a critical failure). A successful save reduces the slowed condition value by 1. A creature unable to act due to the slowed condition from Crystallize Flesh is [[Conditions/Petrified|Petrified]] permanently, transforming into a crystalline statue. The effect ends if the creature is petrified or the slowed condition is removed.\n\n**Critical Failure** As failure, but the target is initially [[Conditions/Slowed|Slowed 2]]."

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The dragon makes two claw Strikes and one tail Strike in any order."

  - name: "Draconic Momentum"
    desc: "  The dragon recharges their Breath Weapon whenever they critically hit with a Strike."
 
```

```encounter-table
name: Crystal Dragon (Adult)
creatures:
  - 1: Crystal Dragon (Adult)
```



Good-natured but vain, crystal dragons are beautiful creatures with brilliant hides made of multicolored crystal and gemstone. Their beauty is a source of great pride but is also something of a weakness, as crystal dragons are easily angered by insults about their appearance. Despite their relatively benign natures when compared to other true dragons, crystal dragons can be short tempered and prone to finding insults where none were intended. Although their opinions are changeable, crystal dragons prefer orderly environments and are not fond of sudden interruptions or distractions.

Crystal dragons build their lairs in underground grottoes, where they cultivate environments of great beauty. Their exacting standards and vivid imaginations mean that they are always working to improve the appearance or layout of some part of their lair. These lairs are unique to each individual crystal dragon, but there are always plenty of reflective surfaces that allow the dragon to observe their own appearance. These range from crystals to reflecting pools to finely crafted mirrors, which are arranged throughout the lair in a pleasing array. Gifts of well-crafted or magical mirrors are an excellent way to curry favor with a crystal dragon.

Although crystal dragons are easily distracted by their sparkling collections or their vanity, they remain good-hearted creatures at the core and make friends quickly. While a crystal dragon tends to find evil creatures uncouth and unpleasant, any other nearby denizen or inhabitant of their home could become fast friends or beloved pets, depending upon the creature's capacity for conversation (and for providing the frequent praise and compliments that crystal dragons hunger for).
