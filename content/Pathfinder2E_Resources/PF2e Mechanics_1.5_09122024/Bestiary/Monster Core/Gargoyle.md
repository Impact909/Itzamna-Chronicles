---
title: "Gargoyle"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.xcioVkK9kKZRvbz5" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/earth
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Gargoyle"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Gargoyle"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[earth]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Darkvision"
languages: "Common, Petran"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +9, Stealth: +12"
abilityMods: [3, 2, 3, -2, 2, -2]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +13, __Ref__ +10, __Will__ +10"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  bleed; __Resistances__ physical 5 (except adamantine)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Clawed Feet"
    desc: "`pf2:r` (attack) **Trigger** The gargoyle is Flying, and a creature moves into an adjacent square below it.\n* * *\n\n**Effect** The gargoyle makes a claw Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+13 ()\n__Damage__  2d8 + 3 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+13 (agile)\n__Damage__  2d6 + 3 slashing"

  - name: "Statue"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the gargoyle appears to be a statue. It has an automatic result of 32 on Deception checks and DCs to pass as a statue."
 
```

```encounter-table
name: Gargoyle
creatures:
  - 1: Gargoyle
```



Gargoyles are monstrous hunters made of elemental stone. They use their resemblance to decorative statues to hide in plain sight in cities during the day and descend upon unlucky pedestrians at night. Their most common form is that of a horned humanoid with bat-like wings, but individual gargoyles show a great deal of variation, with some appearing more or less humanoid and others resembling no known creature. A gargoyle's features are not fixed; city-dwelling gargoyles who remain in the same locale long enough slowly morph, day by day, to match the style of the local architecture. These patient monsters can stay disguised for long stretches of time as they patiently await an opportunity to strike.

Gargoyles tend to be lone hunters, though sometimes they band into fearsome groups called wings for protection or sport. On rare occasions, wings become relatively stable communities, and gargoyles in wings may even ally with other creatures such as demons and intelligent aberrations, though these alliances exist on a razor's edge. The majority of gargoyles are treacherous, vindictive, and petty—traits that preclude lasting partnerships. Almost all have some subject they spend days mulling over while in statue form. Some are collectors, focusing on anything from books to grim trophies, while others are ritualistic or overly passionate about niche intellectual subjects or certain artistic motifs. These tendencies often contribute to the dissolution of wings as individuals with conflicting focuses clash.

## Sanctified Roosts

In addition to their appearances matching their environment, gargoyles that position themselves on temples or other consecrated ground slowly succumb to the influence of that location. These gargoyles gain the holy or unholy trait, as do their unarmed Strikes. A gargoyle roosting on a temple of Asmodeus, for example, will eventually gain the unholy trait along with changes to their personality that bring it more in line with the god's ethos. Holy gargoyles are also possible, although gargoyles at such locations often abandon their roosts as their changing personality conflicts with their need to hunt.
