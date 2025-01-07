---
title: "Skrik Nettle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.om45aMmCQHeYIKuD" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Skrik Nettle"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Skrik Nettle"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[aberration]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Motion Sense (Precise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +16"
abilityMods: [4, 5, 2, -4, 4, 0]
speed: 10 feet,  fly 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +10, __Ref__ +17, __Will__ +14"
hp: 130
health:
  - name: ""
  - name: HP
    desc: "130, (fast healing 5); __Weaknesses__ piercing 5, slashing 5"
abilities_top:
  - name: ""

  - name: "Motionsense"
    desc: "  A flying skrik nettle can detect the movement of nearby creatures and objects from the tiny gusts of wind created by their movements. This is a precise sense at the listed range, but it works only against creatures and objects that moved through air in the previous round."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 5]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Spill Venom"
    desc: "`pf2:r`  **Trigger** The skrik nettle takes piercing or slashing damage\n* * *\n\n**Effect** The skrik nettle ejects its venom onto an adjacent creature. That creature is exposed to skrik nettle venom."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+17 (agile, finesse, reach 10 feet)\n__Damage__  2d8 + 6 piercing plus skrik-nettle-venom"

  - name: "Negate Levitation"
    desc: "`pf2:1` (primal) The skrik nettle attempts to counteract (with a modifier of +17) a single effect currently levitating a creature it can detect with its motionsense."

  - name: "Skrik Nettle Venom"
    desc: " (poison,primal) **Saving Throw** DC 27 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Clumsy|Clumsy 1]] and levitate upward 5 feet (1 round)\n\n**Stage 2** [[Conditions/Clumsy|Clumsy 2]] and levitate upward 10 feet (1 round)\n\nA levitating creature takes a -2 circumstance penalty to attack rolls. It can spend an Interact action to stabilize itself and negate this penalty for the remainder of its turn. If it's adjacent to a fixed object or stable terrain, it can move across the surface by climbing (if the surface is vertical) or crawling (if the surface is horizontal, such as a ceiling).\n\nA flying creature can move normally but still increases its altitude as appropriate from the venom. A creature that can't fly falls as soon as it recovers from skrik nettle venom."
 
```

```encounter-table
name: Skrik Nettle
creatures:
  - 1: Skrik Nettle
```



The expansive skies of the First World are home to skrik nettles-delicate, bizarre-looking creatures that resemble large jellyfishes. A fringe of brightly colored feathers circles their bodies, and long tendrils trail from their center, each ending in a snapping beak. Known for their eerie, chirping melodies, skrik nettles soar above the First World in flocks of a dozen or more, diligently scavenging for food in the fey realm's cutthroat ecosystem. When hunting or provoked, skrik nettles attack their foes by injecting them with a magical poison that causes the victim to float helplessly up into the sky. Skrik nettles continuously inject this poison into their helpless prey until it dies or is so high up that the skrik nettle needs only wait for the poison to end, its meal crashing helplessly to the ground below.

Skrik nettles that find their way to the Material Plane tend to be much more aggressive, for the planar energies that they find comforting and soothing on the First World are conspicuously absent. The first few minutes after a skrik nettle arrives on any plane but the First World tend to be filled with violence and fear, as the panicking creature lashes out at any nearby creatures in the mistaken notion that these others are somehow responsible for the discomforting change. After 10 minutes or so, assuming the skrik nettle survives its bout of violence, the creature calms down somewhat and does its best to acclimate to its new home. Yet even skrik nettles who find themselves marooned beyond the First World for years never lose their longing for home, and they instinctively seek out portals to this plane for the rest of their lives.
