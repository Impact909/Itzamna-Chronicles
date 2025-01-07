---
title: "Lantern Archon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.SJznPcAYB27TjYcA" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/good
  - pf2e/creature/type/holy
  - pf2e/creature/type/lawful
  - pf2eMonster
  - pf2e/creature/level/1
statblock: inline
name: "Lantern Archon"
level: 1
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Lantern Archon"
level: "Creature 1"

alignment: ""
size: "Small"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[good]]
trait_04: [[holy]]
trait_05: [[lawful]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Diabolic, Draconic, Empyrean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Diplomacy: +6, Religion: +6"
abilityMods: [-5, 3, 1, -1, 1, 1]
speed:  fly 40 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +6, __Ref__ +10, __Will__ +4"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Weaknesses__ unholy 3; __Resistances__ fire 3"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Retributive Strike"
    desc: "`pf2:r`  **Damage Reduction** 3\n\nA lantern archon can also make a Retributive Strike with its light ray.\n* * *\n\n**Trigger** An enemy damages the monster's ally, and both are within 15 feet of the monster.\n* * *\n\n**Effect** The ally gains resistance to all damage against the triggering damage equal to 2 + the monster's level. If the foe is within reach, the monster makes a melee Strike against it."

attacks:
  - name: ""

  - name: "**Ranged** `pf2:1` Light Ray"
    desc: "+8 (agile, fire, holy, magical, range increment 30 feet)\n__Damage__  1d4 fire 1d4 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 17, attack +9; __4th __  _[[Spells/Read Omens|Read Omens]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At Will) (Evil Only)]]_, _[[Spells/Heal|Heal]]_\n__Cantrips__  __(1st)__ _[[Spells/Light|Light]]_"

  - name: "Gestalt"
    desc: "`pf2:3` (concentrate,divine,holy) Nine lantern archons can use this activity, all within 1 round of the first, to merge together to form a composite being for 7 rounds that appears as a glowing warrior of light.\n\nThe [[Bestiary 1/Lantern Archon (Gestalt)|Gestalt]] has the base statistics of a legion archon (AC, saving throws, attacks, skills, Speeds, and so on) but the spells and special abilities of a lantern archon. Additionally, it has a ranged light ray Strike (Light Ray +18, Damage 3d4 fire and 3d4 spirit), and the bonus from its Lantern of Hope increases to +3.\n\nWhen the gestalt separates, its remaining Hit Points are divided evenly among the lantern archons, and if the gestalt had fewer than 9 HP, some of the lantern archons die."

  - name: "Lantern of Hope"
    desc: "`pf2:1` (concentrate,divine,mental) The lantern archon shines as a beacon of hope.\n\nGood allies within 30 feet gain a +1 status bonus to damage rolls and to saving throws against [[Spells/Wave of Despair|Wave of Despair]].\n\n[[Bestiary Effects/Effect_ Lantern of Hope|Effect: Lantern of Hope]]"
 
```

```encounter-table
name: Lantern Archon
creatures:
  - 1: Lantern Archon
```



Friendly, curious, and eternally optimistic, lantern archons embody the virtue of hope. They are formed of living light given corporeal shape, and they serve as beacons, guiding mortals out of their darkest moments and toward the path of righteousness. Their luminous bodies can flicker with the subtlety of a candle flame or flare up like a torch. Lantern archons can control all aspects of their light as easily as other creatures control their facial expressions, leading them to change color, twinkle, and otherwise dim and brighten in time with their actions and words. While effervescent and chipper in conversation, lantern archons are impressively stoic mobile support troops and guardians in times of conflict, and are capable of uniting to form powerful warriors of light called gestalts.

* * *

Archons are guardians of Heaven and enemies of chaos and evil. They openly fight back the spread of fiends but also quietly nurture the seeds of virtue within mortals, teaching the denizens of the Material Plane how to act with honor and integrity, enact just laws, and cast off sin and temptation.

Archons live in the immense seven-tiered mountain of Heaven. They manifest in the Garden at the mountain's peak from mortal souls who answer a mysterious voice. There they swear to forever serve the cause of justice and transform into their new archon forms. Intensely orderly in their metamorphosis, new archons begin as lantern archons or other lesser forms, transforming into ever-greater archons as their virtue and achievements grow. Each archon represents a particular virtue, such as hope, charity, justice, or courage, and they gain strength in the presence of mortals who exemplify this virtue. Due to their extremely lawful nature, archons sometimes find themselves at odds with azatas.
