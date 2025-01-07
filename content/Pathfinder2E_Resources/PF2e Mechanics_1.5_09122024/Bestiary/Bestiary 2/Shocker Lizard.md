---
title: "Shocker Lizard"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mO6JDGa2aD4DJcOW" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Shocker Lizard"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Shocker Lizard"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Athletics: +5, Stealth: +8"
abilityMods: [1, 4, 3, -4, 3, 0]
speed: 35 feet,  climb 15 feet,  swim 15 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +7, __Ref__ +10, __Will__ +7"
hp: 32
health:
  - name: ""
  - name: HP
    desc: "32; __Immunities__  electricity"
abilities_top:
  - name: ""

  - name: "Greater Electrolocation"
    desc: " (electricity) A shocker lizard can sense minute electrical charges in living creatures, which it can use as a precise sense at a range of 20 feet. This distance increases to 100 feet against any creature that has used an electricity effect within the last minute."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+10 (agile, finesse)\n__Damage__  1d8 + 3 piercing"

  - name: "**Ranged** `pf2:1` Shock"
    desc: "+10 (nonlethal, range increment 5 feet)\n__Damage__  2d6 electricity"

  - name: "Amplify Voltage"
    desc: "`pf2:r`  **Trigger** A shocker lizard within 20 feet makes a shock Strike or uses Discharge\n* * *\n\n**Effect** The shocker lizard lends some of its electrical power to the nearby lizard. This either causes the other lizard's shock Strike to lose the nonlethal trait or increases the DC of its Discharge to 20."

  - name: "Discharge"
    desc: "`pf2:2` (electricity) The shocker lizard releases a blast of lightning from its body. Creatures within a 10-foot emanation take 3d6 electricity damage (DC 18 Reflex check save).\n\nThe shocker lizard can't use Discharge for 1d4 rounds."

  - name: "Shocking Burst"
    desc: "`pf2:3` (electricity,primal) The shocker lizard hunkers down and begins to spark with electricity, which it releases in a 10-foot emanation that deals 3d8 electricity damage (DC 18 Reflex check save).\n\nThe shocker lizard can't use Shocking Burst again for 1 minute.\n\nUp to four shocker lizards can combine their Shocking Bursts. In this case, the lizards can delay the release of their electricity until any other shocker lizard within 30 feet completes its Shocking Burst. The combined Shocking Bursts create an emanation with the combined area from all participating shocker lizards. For each additional shocker lizard that joins the burst, the damage increases by 3d8 and the save DC increases by 1 (to a maximum of four lizards dealing 12d8 damage with a DC 21 save)."
 
```

```encounter-table
name: Shocker Lizard
creatures:
  - 1: Shocker Lizard
```



These brightly colored reptiles share the rough size and pack mentality of guard dogs, roaming in small groups. Shocker lizards have specialized glands under their scales that accumulate static electricity, and they can unleash blasts of lightning strong enough to harm significantly larger foes. Though they're meek and docile when encountered alone, shocker lizards are significantly more aggressive in packs, when they can amplify each other's electrical attacks.

Shocker lizards are notoriously difficult to domesticate because they're dangerously hostile as part of a pack, but will also swiftly wither and die if kept alone in captivity without constant attention. A shocker lizard is 3 feet long and weighs 25 pounds.
