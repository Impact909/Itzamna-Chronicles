---
title: "Peryton"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LQy6gw0P93SdlHE0" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Peryton"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Peryton"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[beast]]
trait_02: [[chaotic]]
trait_03: [[evil]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +11, Intimidation: +11, Stealth: +11"
abilityMods: [4, 3, 2, 0, 5, 3]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +8, __Ref__ +11, __Will__ +13"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Antler"
    desc: "+14 (deadly d8)\n__Damage__  1d12 + 7 piercing"

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+14 (agile)\n__Damage__  1d8 + 7 slashing"

  - name: "Heart Ripper"
    desc: "`pf2:1` (attack,emotion,fear,visual) The peryton rips out the heart of an adjacent corpse with their jaws. The creature must have died in the last minute. As the peryton rips the heart free and swallows it whole, they regain 2d6 healing HP, and any non-peryton that witnesses this event must succeed at a DC 21 Will check save or become [[Conditions/Frightened|Frightened 1]] (or [[Conditions/Frightened|Frightened 2]] on a critical failure)."

  - name: "Mimic Shadow"
    desc: "`pf2:1` (emotion,fear,occult,shadow) **Requirements** The target must be casting a shadow\n* * *\n\n**Effect** The peryton Flies, going no higher than 20 feet over the target creature. The target creature must succeed at a DC 21 Will check save or the peryton's shadow changes to match that cast by the target creature. With their shadow so transformed, the peryton gains a +2 status bonus to attack and damage rolls against that creature.\n\nIn addition, each time the peryton successfully Strikes that creature, the creature must succeed at a DC 21 Will check save or become [[Conditions/Frightened|Frightened 1]], or increase its frightened condition by 1 if it's already frightened. This is an emotion and fear effect. The shadow remains transformed for 1 hour or until the peryton Mimics a Shadow again, whichever comes first."
 
```

```encounter-table
name: Peryton
creatures:
  - 1: Peryton
```



The peryton is an amalgam of horror, merging the features of a stag, wolf, and hawk. They love using shadows to stalk their victims before ripping out their still-beating hearts and relishing the dying pulse as they swallow them whole, so the doomed victims spends their last moments watching as their flesh is consumed.

Despite perytons' animalistic appearance and brutal behavior, they are viciously cunning and as intelligent as humans. Their preferred tactic is to find a lone traveler and stalk it from on high. Most perytons are loners who loathe all other creatures. These feelings extend to other perytons as well, and adult males attack each other on sight as surely as they attack anything else.

Once per year, perytons mate. The males offer up hearts they have collected from humanoids to attract females. Those that manage to secure a mate rarely survive long though, as their mating ritual is short and violent. Female perytons generally abandon their eggs after laying them, so newly hatched perytons must fend for themselves from the moment they emerge.

A lone peryton typically builds a nest in a rocky overhang or an exceptionally tall and strong tree where they can observe nearby lands. Although they aren't particularly interested in wealth, perytons do like to collect small objects from their victims. During those times between hunts, they sometimes study these trophies in order to relive the memories of victims' last moments and the taste of victims' hearts.
