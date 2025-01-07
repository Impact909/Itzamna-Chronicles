---
title: "Viper"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5hePtoqYgcauxS3m" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/-1
  - remaster
statblock: inline
name: "Viper"
level: -1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Viper"
level: "Creature -1"

alignment: ""
size: "tiny"
trait_01: [[animal]]
modifier: 5
perception:
  - name: "Perception"
    desc: "+5; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +5, Athletics: +1, Stealth: +5, Survival: +3"
abilityMods: [-3, 4, 0, -4, 1, -2]
speed: 20 feet,  climb 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +2, __Ref__ +7, __Will__ +5"
hp: 8
health:
  - name: ""
  - name: HP
    desc: "8"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Slink"
    desc: "`pf2:r`  **Trigger** A creature ends its movement adjacent to the viper or within the viper's space.\n* * *\n\n**Effect** The viper Strides, Climbs, or Swims up to 10 feet (or up to the relevant Speed, if that Speed is less than 10 feet). It must end its movement in a location that isn't within 5 feet of a foe. This movement doesn't trigger reactions."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+6 (agile, finesse, reach 0 feet)\n__Damage__  1d8 - 3 piercing plus viper-venom"

  - name: "Viper Venom"
    desc: " (poison) **Saving Throw** DC 16 Fortitude check\n* * *\n\n**Maximum Duration** 4 rounds\n\n**Stage 1** 1d8 poison (1 round)."
 
```

```encounter-table
name: Viper
creatures:
  - 1: Viper
```



Each member of this family of venomous snakes has long, hinged fangs that inject potent venom into their prey. Different vipers inject different types of venom, which might result in paralysis, extreme pain and swelling, blood clotting, or even the sudden stopping of the victim's heart.

* * *

Snakes come in an array of forms, from jungle-dwelling constrictors that wrap around their prey to venomous vipers with deadly bites. Regardless, all snakes consume their prey whole by unhinging their jaws and using powerful muscles to move the food down their throats and into their stomachs.
