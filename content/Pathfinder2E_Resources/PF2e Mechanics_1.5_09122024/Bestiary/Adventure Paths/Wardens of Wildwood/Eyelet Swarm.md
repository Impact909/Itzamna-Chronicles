---
title: "Eyelet Swarm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.jFTJ2NaaAlYOcyfT" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/swarm
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Eyelet Swarm"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #202: Severed at the Root"
name: "Eyelet Swarm"
level: "Creature 7"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[swarm]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Draconic, Fey, Shadowtongue, Common; Can&#x27;t Speak Any Language"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Stealth: +18"
abilityMods: [0, 5, 0, 2, 4, 2]
speed: 5 feet,  fly 40 feet
sourcebook: "_Pathfinder #202: Severed at the Root_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +12, __Ref__ +18, __Will__ +15"
hp: 90
health:
  - name: ""
  - name: HP
    desc: "90; __Immunities__  precision,  swarm mind,  grabbed,  prone,  restrained; __Weaknesses__ area damage 5, splash damage 5; __Resistances__ bludgeoning 5, slashing 10, piercing 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Swarm Mind|Swarm Mind]]"
    desc: "  This monster doesn't have a single mind (typically because it's a swarm of smaller creatures), and is immune to mental effects that target only a specific number of creatures. It is still subject to mental effects that affect all creatures in an area."

  - name: "[[Bestiary Ability Glossary/Light Blindness|Light Blindness]]"
    desc: "  When first exposed to bright light, the monster is [[Conditions/Blinded|Blinded]] until the end of its next turn. After this exposure, light doesn't blind the monster again until after it spends 1 hour in darkness. However, as long as the monster is in an area of bright light, it's [[Conditions/Dazzled|Dazzled]]."

  - name: "Send Signal"
    desc: "`pf2:1`  The eyelet sends an emergency signal through its scrying sensor to a linked scrying station (see Witness) up to 10 miles away. This transmits the eyelet's distance and direction from the station at the time of sending."

  - name: "Witness"
    desc: "  The eyelet records whatever it perceives, storing it in an embedded, marble-sized sensor. The eyelet can record up to 1 hour of events, starting and stopping across a longer period. Removing the sensor erases its records. An eyelet can transfer everything it has recorded up to 10 miles to its linked scrying station, where the recordings are collected and can be viewed. Doing so empties the sensor so it can be used again. An eyelet can link, or sever its link, to a scrying station as a 10-minute activity with the concentrate trait."

attacks:
  - name: ""

  - name: "Swarming Cyclone"
    desc: "`pf2:1`  Each enemy in the swarm's space takes 4d6 bludgeoning damage (DC 25 Reflex check save). A creature that fails this save is [[Conditions/Stunned|Stunned 1]]."

  - name: "Unnerving Observation"
    desc: "`pf2:1` (emotion,fear,mental,occult) The eyelets focus their sensors on the same target. One enemy in the swarm's space takes 6d6 mental damage (DC 25 Will check save). On a failed save, the target is [[Conditions/Frightened|Frightened 2]] (or [[Conditions/Frightened|Frightened 3]] and [[Conditions/Fleeing|Fleeing]] for 1 round on a critical failure)."
 
```

```encounter-table
name: Eyelet Swarm
creatures:
  - 1: Eyelet Swarm
```



Hundreds of eyelets can swarm to overwhelm larger threats.

* * *

Eyelets are tiny, bat-like creatures with wings of shadow and magical scrying sensors embedded in their torsos. They use these eye-like sensors to record nearby events, gaining sustenance in the process.

## Scrying Station

Eyelets live in flocks, nesting at a central scrying station for safety and camaraderie. At these stations, the events the eyelets witness are stored and viewed, and the eyelets' scrying sensors are erased. Wild eyelets typically use abandoned buildings or sheltered cave systems as scrying stations. The eyelets in Gloaming Arbor work for Avathrael and are linked with the eyelet spire (area **T**).
