---
title: "Xulgath Gutrager"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.QnwsSPspGQHPdmkf" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/xulgath
  - pf2eMonster
  - pf2e/creature/level/10
statblock: inline
name: "Xulgath Gutrager"
level: 10
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #154: Siege of the Dinosaurs"
name: "Xulgath Gutrager"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[chaotic]]
trait_02: [[evil]]
trait_03: [[humanoid]]
trait_04: [[xulgath]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Draconic, Sakvroth"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +22, Stealth: +20"
abilityMods: [4, 6, 7, -2, 1, -1]
speed: 40 feet
sourcebook: "_Pathfinder #154: Siege of the Dinosaurs_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +23, __Ref__ +22, __Will__ +17"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Resistances__ acid 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Caustic Fog"
    desc: " (acid,aura) 10 feet. Whenever a gutrager is within another xulgath's stench aura, a fog appears around the gutrager; creatures in the fog (including the gutrager) can see as normal, but they are [[Conditions/Concealed|Concealed]] from creatures outside the fog. Non-xulgaths that begin their turn in the fog take 2d6 acid damage. Strong winds suppress this ability."

  - name: "Self-Detonate"
    desc: "`pf2:2` (acid) **Requirements** The gutrager has 45 or fewer HP\n* * *\n\n**Effect** The gutrager compresses its gut and explodes in a burst of viscera, dying instantly and dealing 8d8 acid damage to creatures and unattended objects in a 20-foot emanation centered on the gutrager (DC 31 Reflex check save)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 ()\n__Damage__  2d6 + 8 piercing 2d6 acid"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+23 (agile, finesse)\n__Damage__  2d8 + 8 slashing"

  - name: "**Ranged** `pf2:1` Bile Jet"
    desc: "+23 (acid, range increment 60 feet)\n__Damage__  4d8 + 7 acid"

  - name: "Corrosive Kiss"
    desc: "`pf2:2` (acid) **Frequency** once per round\n* * *\n\n**Effect** The gutrager propels its esophagus out of its body to deliver an acidic blow. It makes an unarmed Strike against a creature or unattended object within 30 feet with a +23 attack bonus.\n\nOn a hit, the target takes 2d6+8 bludgeoning damage plus 4d6 acid damage.\n\nOn a critical hit, the target also takes 2d6 persistent acid damage.\n\nThe gutrager is [[Conditions/Clumsy|Clumsy 1]] for 1 round as it re-coils its esophagus."
 
```

```encounter-table
name: Xulgath Gutrager
creatures:
  - 1: Xulgath Gutrager
```



Xulgath gutragers exhibit more extreme developments along the same physiological path as their bilebearer cousins (_Pathfinder Adventure Path #151: The Show Must Go On_). They are stockier and faster, with necks and limbs corded with muscle. They are also denser, with multiple stomachs full of fluids even more caustic than those of the bilebearer. Like the bilebearer, gutragers lack the distinctive stench typical of most xulgaths.

A gutrager's torso conceals its most disturbing feature-a densely coiled esophagus. Pressurized bladders and a muscular throat allow the gutrager to propel its esophagus outward in an explosion of yellow flesh and acidic bile; caustic stomach acid coating the esophagus makes even brief physical contact with the organ dangerous. As a last resort, the gutrager can intentionally accelerate the corrosion in its esophagus, releasing vile acid in a burst that also ends its life.
