---
title: "Shadow Drake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Y6FkOVCEus88GHMa" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2e/creature/type/shadow
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Shadow Drake"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Shadow Drake"
level: "Creature 2"

alignment: ""
size: "tiny"
trait_01: [[chaotic]]
trait_02: [[dragon]]
trait_03: [[evil]]
trait_04: [[shadow]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Stealth: +8, Thievery: +8"
abilityMods: [1, 4, 1, -1, 0, 2]
speed: 15 feet,  fly 60 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +7, __Ref__ +10, __Will__ +6"
hp: 28
health:
  - name: ""
  - name: HP
    desc: "28; __Immunities__  paralyzed,  sleep; __Weaknesses__ fire 5"
abilities_top:
  - name: ""

  - name: "Light Blindness"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "Shadow Blend"
    desc: "  The shadow drake's form shifts and blends reflexively with surrounding shadows. A shadow drake gains an additional reaction each round, but it can use this reaction only for Shadow Evade."

  - name: "Shadow Evade"
    desc: "  **Trigger** A creature attacks the shadow drake while it is in an area of dim light\n* * *\n\n**Effect** The shadow drake further obscures its position. The attacker must succeed at a DC 11 Flat check check in order to affect the shadow drake, as if the drake were [[Conditions/Hidden|Hidden]] for the triggering attack."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (finesse)\n__Damage__  1d10 + 3 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+11 (agile, finesse)\n__Damage__  1d8 + 3 bludgeoning"

  - name: "Draconic Frenzy"
    desc: "`pf2:2`  The shadow drake makes one bite Strike and two tail Strikes in any order."

  - name: "Shadow Breath"
    desc: "`pf2:2` (arcane,cold,shadow) A shadow drake spits a ball of black liquid that explodes into a cloud of frigid black shadow. This attack has a range of 40 feet and explodes in a 5-foot-radius burst. Creatures within the burst take 3d6 cold damage (DC 18 Reflex check save). The explosion of shadow also snuffs out mundane light sources the size of a torch, lantern, or smaller, and attempts to counteract magical light with a +10 counteract modifier.\n\nThe shadow drake can't use Shadow Breath again for 1d6 rounds."

  - name: "Speed Surge"
    desc: "`pf2:1`  **Frequency** three times per day\n* * *\n\n**Effect** The shadow drake Strides or Flies twice."
 
```

```encounter-table
name: Shadow Drake
creatures:
  - 1: Shadow Drake
```



Shadow drakes are typically among the smallest and least powerful of their species. Most stand as tall and long as house cats and have charcoal-colored scales and membranous wings just translucent enough to pass for shadows. Attracted to shiny materials, they employ deception, teamwork, and even rudimentary traps to create opportunities to make off with ill-gotten gains. Shadow drakes have a particular fascination and admiration for umbral dragons-a notable exception to the norm for drakes and dragons.
