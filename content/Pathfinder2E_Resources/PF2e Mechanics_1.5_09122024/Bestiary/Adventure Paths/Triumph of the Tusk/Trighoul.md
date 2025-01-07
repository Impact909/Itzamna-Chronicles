---
title: "Trighoul"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pT1WXQRXjz1p1QhI" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Trighoul"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #208: Hoof, Cinder, and Storm"
name: "Trighoul"
level: "Creature 8"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[aberration]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Aklo, Common, Necril, Orcish"
skills:
  - name: "Skills"
    desc: "Acrobatics: +18, Athletics: +16, Deception: +17, Stealth: +18"
abilityMods: [4, 6, 3, 4, 3, 3]
speed: 45 feet
sourcebook: "_Pathfinder #208: Hoof, Cinder, and Storm_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +13, __Ref__ +19, __Will__ +16"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100, Tentacle HP 20, tentacle regrowth"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Pain Sensitivity"
    desc: "  When a trighoul's tentacle is severed, it becomes [[Conditions/Stunned|Stunned 1]]. Its Speed is reduced by 15 feet until the tentacle is regrown."

  - name: "Tentacle Regrowth"
    desc: "  A trighoul ordinarily has three tentacles. A creature can attempt to sever a tentacle by specifically targeting it and dealing damage equal to the tentacle's Hit Points. A tentacle that isn't severed completely returns to full Hit Points at the end of any creature's turn. A severed trighoul tentacles regrows, restored to full Hit Points, after [[/gmr 1d4 #rounds]]{1d4 rounds}."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+20 (agile, finesse, reach 10 feet)\n__Damage__  2d6 + 6 bludgeoning plus improved-grab 1d6 piercing plus improved-grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 (agile, finesse)\n__Damage__  2d6 + 6 piercing"

  - name: "**Ranged** `pf2:1` Spit"
    desc: "+20 (acid, range increment 20 feet, splash)\n__Damage__  3 acid 2d8 + 9 acid"

  - name: "Puppet Show"
    desc: "`pf2:1` (concentrate,manipulate) `pf2:1` to `pf2:3`\n\n**Requirements** The trighoul is using Puppeteer Corpse\n* * *\n\n**Effect** The trighoul manipulates up to three corpses to silently Impersonate the living. A creature that fails to detect the deception is [[Conditions/Off-Guard|Off-Guard]] to the trighoul's corpse Strike. The deception ends immediately after the trighoul attacks."

  - name: "Puppeteer Corpse"
    desc: "`pf2:1` (manipulate) **Requirements** The trighoul is [[Conditions/Hidden|Hidden]], and there's at least one corpse within 10 feet\n* * *\n\n**Effect** The trighoul attaches a tentacle to the corpse of a Large to Small creature. That tentacle replaces its Strike with a melee corpse Strike that deals bludgeoning damage equal to the total damage dealt by its tentacle. A controlled corpse is destroyed when it takes 20 Hit Points of damage. The trighoul can detach from a corpse as a single action with the manipulate trait."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Trighoul
creatures:
  - 1: Trighoul
```



Despite the name given by orcs of the Dirt Sea, the trighoul is not a ghoul at all, but a mutagenic abomination. Its three tentacles bristle with hundreds of neural spines that let it "glide" across the sands at high speed and manipulate the nervous system of a corpse through the spinal column. Trighouls were originally created over a thousand years ago by fleshwarpers aligned with the Whispering Tyrant, giving them to raiders as weapons. While the use of trighouls is now regarded with shame and disgust, some still take advantage of the creatures to lure enemies to their deaths using the corpses of their slain comrades.

## Puppetmaster Serum

Orc alchemists familiar with fleshwarping techniques have synthesized an elixir called puppetmaster extract. The elixir transforms the drinker's limb into a tentacle that can temporarily animate the dead. One must take great care when crafting the serum, as incorrectly mixed batches have been known to dissolve organs from within, cause permanent paralysis, and grow tentacles in unwanted places.
