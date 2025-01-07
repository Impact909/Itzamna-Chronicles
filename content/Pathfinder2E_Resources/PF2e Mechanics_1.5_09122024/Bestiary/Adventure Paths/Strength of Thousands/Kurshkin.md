---
title: "Kurshkin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.n0cm2rTId4eibs5J" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2e/creature/type/gremlin
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Kurshkin"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #169: Kindled Magic"
name: "Kurshkin"
level: "Creature 3"
rare_03: [[Unique]]
alignment: ""
size: "tiny"
trait_01: [[evil]]
trait_02: [[fey]]
trait_03: [[gremlin]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Kholo, Sakvroth"
skills:
  - name: "Skills"
    desc: "Arcana: +8, Crafting: +8, Deception: +8, Nature: +8, Stealth: +11, Thievery: +9"
abilityMods: [-2, 4, 1, 1, -1, 3]
speed: 25 feet
sourcebook: "_Pathfinder #169: Kindled Magic_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +8, __Ref__ +11, __Will__ +8"
hp: 50
health:
  - name: ""
  - name: HP
    desc: "50; __Weaknesses__ cold iron 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortbow|Shortbow]], [[Equipment/Shortsword|Shortsword]], 60x [[Equipment/Arrows|Arrows]]"
abilities_mid:
  - name: ""
  - name: "Unluck Aura"
    desc: " (aura,mental,misfortune,primal) 20 feet. Creatures other than animals, gremlins, and gnolls in the aura become extremely unlucky (DC 20 Will check save; creature must roll this Will save twice and take the worse result). On a successful save, the creature is temporarily immune to pugwampi unluck auras for 24 hours. On a failure, the creature must roll twice and take the worse result on all checks as long as it is within the aura.\n\n[[Bestiary Effects/Effect_ Unluck Aura|Effect: Unluck Aura]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Shortsword"
    desc: "+12 (agile, finesse, magical, versatile s)\n__Damage__  1d6 + 4 piercing"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+12 (deadly d10, magical, range increment 60 feet, reload 0)\n__Damage__  1d6 piercing"

  - name: "Innate Primal Spells"
    desc: "DC 20, attack +12; __2nd __  _[[Spells/Speak with Animals|Speak with Animals (At Will)]]_; __1st __ (2 slots) _[[Spells/Gust of Wind|Gust of Wind]]_, _[[Spells/Spider Sting|Spider Sting]]_\n__Cantrips__  __(2nd)__ _[[Spells/Prestidigitation|Prestidigitation]]_"

  - name: "Collateral Damage"
    desc: "`pf2:r`  **Trigger** A Strike critically misses Kurshkin\n* * *\n\n**Effect** Kurshkin redirects the strike to an adjacent creature. The attacker rerolls the Strike against that creature."

  - name: "Lucky Stabs"
    desc: "  Kurshkin deals an additional 1d6 damage with her melee Strikes against creatures affected by her unluck aura."

  - name: "Natural Thief"
    desc: "  When attacking with a finesse melee weapon, Kurshkin adds her Dexterity modifier to damage rolls instead of her Strength modifier."
 
```

```encounter-table
name: Kurshkin
creatures:
  - 1: Kurshkin
```




