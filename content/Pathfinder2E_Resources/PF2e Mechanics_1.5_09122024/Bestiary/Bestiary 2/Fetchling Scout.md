---
title: "Fetchling Scout"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gPLiPBaKAWkmGq0e" 
tags:
  - pf2e/creature/type/fetchling
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Fetchling Scout"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Fetchling Scout"
level: "Creature 1"

alignment: ""
size: "Medium"
trait_01: [[fetchling]]
trait_02: [[humanoid]]
trait_03: [[shadow]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Darkvision"
languages: "Common, Shadowtongue"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Athletics: +4, Deception: +5, Diplomacy: +5, Society: +3, Stealth: +7, Thievery: +7"
abilityMods: [1, 4, 2, 0, 0, 2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +5, __Ref__ +9, __Will__ +5"
hp: 18
health:
  - name: ""
  - name: HP
    desc: "18"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Dagger|Dagger]], [[Equipment/Chain Shirt|Chain Shirt]]"
abilities_mid:
  - name: ""
  - name: "Shadow Blending"
    desc: "  When the fetchling scout is [[Conditions/Concealed|Concealed]] as a result of dim light, the flat check to target them has a DC of 7, not 5."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Dagger"
    desc: "+9 (agile, finesse, versatile s)\n__Damage__  1d4 + 1 piercing"

  - name: "**Ranged** `pf2:1` Dagger"
    desc: "+9 (agile, finesse, thrown 10 ft., versatile s)\n__Damage__  1d4 + 1 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 15, attack +5; __1st __  _[[Spells/Illusory Disguise|Illusory Disguise]]_"

  - name: "Shadow Stride"
    desc: "`pf2:1` (illusion,occult,shadow) **Requirements** The fetchling is in dim light\n* * *\n\n**Effect** The fetchling Strides. They have a +10-foot status bonus to their Speed during this Stride. The DC from shadow blending increases to DC 11 Flat check during this Stride, and the fetchling remains [[Conditions/Concealed|Concealed]] by dim light until the end of the movement, even if they leave dim light during the Stride."

  - name: "[[Bestiary Ability Glossary/Sneak Attack|Sneak Attack]]"
    desc: "  The fetchling scout's Strikes deal an additional 1d6 precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."
 
```

```encounter-table
name: Fetchling Scout
creatures:
  - 1: Fetchling Scout
```



The people known today as fetchlings are a distinct ancestry descended from generations of humans who became trapped ages ago on the Shadow Plane. No longer human at all, these people, who call themselves kayals, have become monochromatic in coloration, with flesh tones and hair colors varying between white, black, and all shades of gray. Their limbs are lithe and willowy, and their eyes are generally solid yellow, yellow-green, or white, though a rare few have a purple or blue glow.

Fetchlings have developed their own complex societies in the Shadow Plane, often under the tolerance of or in servitude to the strange, malignant creatures there, such as the sinister velstracs or the enigmatic d'ziriaks. While individual fetchlings can be any alignment, they are all survivors in a harsh environment, which leads to a tendency toward pragmatism. Fetchling clothing mimics the regions they dwell in, with drab colors tending toward darker shades. When they trade with humans or other societies on the Material Plane, they often wear masks or concealing clothing to hide their appearance.

Typical fetchling communities are insular and swiftly close ranks in the event of an intruder. Though individual fetchlings don't mind traveling to and blending in with other societies to facilitate trade, they often hide or even react defensively if they have their own visitors. When one considers the nature of the other denizens of the Shadow Plane, however, this tendency to assume the worst of interlopers might make sense to some.

Fetchlings are not as common on the Material Plane; most of those who dwell there are loners by choice who have left their home to seek out adventure elsewhere, exiles who were banished from their homelands, or planar castaways with no ability to return to the Shadow Plane. This last category, the lost and stranded, are the most likely to be found in larger groups. In cities of significant size, one can sometimes even find a small community of a few dozen or more fetchlings living among humans, although they often do so subtly by dyeing their hair, wearing brightly colored clothing, and utilizing layers of makeup to hide their pallid complexions.
