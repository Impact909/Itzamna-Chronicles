---
title: "Reginald Vancaskerkin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mk6mRwnRQDijRkdh" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Reginald Vancaskerkin"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #161: Belly of the Black Whale"
name: "Reginald Vancaskerkin"
level: "Creature 18"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
trait_02: [[evil]]
trait_03: [[humanoid]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; "
languages: "Chthonian, Common, Daemonic, Diabolic, Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +32, Deception: +34, Diplomacy: +34, Occultism: +31, Religion: +28, Thievery: +29, Absalom Lore: +31, Engineering Lore: +31"
abilityMods: [6, 3, 0, 5, 2, 8]
speed: 25 feet
sourcebook: "_Pathfinder #161: Belly of the Black Whale_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +26, __Ref__ +29, __Will__ +28"
hp: 350
health:
  - name: ""
  - name: HP
    desc: "350; __Weaknesses__ electricity 15, orichalcum 15; __Resistances__ physical 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Clockwork Reconstruction"
    desc: "  Each time Reginald is reborn in his lair, his machines graft him with a new clockwork modification. He chooses one of his abilities with the clockwork trait. He gains access to this ability but can't use any of his other clockwork abilities. He can't choose the same ability twice in a row. He begins with Ink Blood active."

  - name: "Ink Blood"
    desc: "`pf2:r` (clockwork,poison) Reginald's body is filled with toxic ink\n* * *\n\n**Trigger** An adjacent creature Strikes Reginald with a melee weapon or unarmed attack and deals damage\n\n**Effect** The creature is exposed to Reginald's poison ink."

  - name: "Secret of Rebirth"
    desc: " (occult) If a creature with less than 5 Secret Knowledge points reduces Reginald to 0 HP (or dealt the last damage to him before he dies from using Overdrive Engine), Reginald's body dissipates into a puddle of ink and releases a black wave of psychic energy. Each creature within 30 feet is bathed in a torrent of forbidden secrets and gains 1 Secret Knowledge point. Reginald's body reforms 1d6 rounds later in his sanctum at full health at a location of his choosing (typically the Pool of Secrets, area **L11**). This ability activates automatically with no action necessary on Vancaskerkin's behalf."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bronze Fist"
    desc: "+34 (agile, magical)\n__Damage__  3d12 + 14 bludgeoning"

  - name: "**Ranged** `pf2:1` Steel Quill"
    desc: "+31 (agile, magical, thrown 20 ft.)\n__Damage__  3d8 + 14 piercing"

  - name: "Breath Weapon"
    desc: "`pf2:2` (clockwork,magical,poison) Reginald's lungs are equipped with ink canisters, allowing him to spew a 60-foot line of ink that deals 9d6 poison damage (DC 39 Reflex check save; on a failure, the creature is also subjected to Reginald's poison ink)."

  - name: "Overdrive Engine"
    desc: " (clockwork) Reginald is equipped with clockwork organs to power his body\n* * *\n\n**Requirements** Reginald has 175 Hit Points or fewer\n\n**Effect** Reginald gains 200 temporary Hit Points, a +15-foot status bonus to Speed, and a +2 status bonus to melee attack rolls. His body begins to overheat, spewing steam that deals 9d6 fire damage at the beginning of his turn to all creatures within 30 feet (DC 40 Reflex check save). After 2 rounds, Reginald explodes, dealing 19d6 fire damage to all creatures within 60 feet (DC 40 Reflex check save). Reginald dies. For the purposes of his Secret of Rebirth ability, the last creature to damage Reginald counts as killing him."

  - name: "Poison Ink"
    desc: " (poison) Reginald is immune to the toxic ink that flows through his veins\n\n**Saving Throw** DC 38 Fortitude check\n\n**Maximum Duration** 10 rounds\n\n**Stage 1** 3d6 poison and [[Conditions/Sickened|Sickened 1]] (1 round)\n\n**Stage 2** 4d6 poison [[Conditions/Sickened|Sickened 2]] (1 round)."

  - name: "Quill Cannon"
    desc: "`pf2:2` (clockwork) Reginald is equipped with a cannon and hundreds of steel quills. He makes two steel quill attacks against every creature in a 60-foot cone, ignoring the multiple attack penalty until after all attacks are made. He can't use Quill Cannon again for 1d4 rounds."

  - name: "Reflective Plating"
    desc: "`pf2:1` (clockwork,occult) Reginald engages his defensive plating, which casts [[Spells/Spell Turning|Spell Turning]] on him (counteract modifier +32)."

  - name: "Slither"
    desc: "  With his body composed of ink and gears, Reginald can move through tight spaces as if he were a Tiny creature, treating them as difficult terrain."
 
```

```encounter-table
name: Reginald Vancaskerkin
creatures:
  - 1: Reginald Vancaskerkin
```




