---
title: "Vibrant Pup Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1qPEtYV01JSsVes7" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Vibrant Pup Swarm"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Vibrant Pup Swarm"
level: "Creature 11"

alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[swarm]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Tremorsense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +16"
abilityMods: [-2, 7, 5, -5, 5, -4]
speed: 30 feet,  burrow 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__ +24, __Ref__ +21, __Will__ +18"
hp: 140
health:
  - name: ""
  - name: HP
    desc: "140; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 5, piercing 10, slashing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Feel No Pain"
    desc: "`pf2:r`  **Trigger** The vibrant pup swarm is critically hit by a Strike\n* * *\n\n**Effect** The worker pups become insensitive to pain and leap to the front. The swarm gains 10 temporary Hit Points that last for 1 round."

  - name: "Reflective Skin"
    desc: " (aura,light,visual) 10 feet. Other creatures in the aura are [[Conditions/Dazzled|Dazzled]]. The aura automatically activates when the swarm is in bright light and deactivates in dim light or darkness."

attacks:
  - name: ""

  - name: "Focused Reflection"
    desc: "`pf2:2` (fire,light) **Requirements** The vibrant pup swarm is in bright light\n* * *\n\n**Effect** The swarm simultaneously turns to focus the light in an arcing beam, dealing 6d12 fire damage to all creatures in a 30-foot cone (DC 30 Reflex check save). A creature that fails its save is also [[Conditions/Blinded|Blinded]] for 1 round (or 1 minute on a critical failure). The swarm can't use Focused Reflection again for 1d4 rounds."

  - name: "Swarming Bites"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 2d6 piercing damage (DC 30 Reflex check save)."
 
```

```encounter-table
name: Vibrant Pup Swarm
creatures:
  - 1: Vibrant Pup Swarm
```




