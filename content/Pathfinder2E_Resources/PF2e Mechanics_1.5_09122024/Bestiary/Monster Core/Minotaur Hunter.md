---
title: "Minotaur Hunter"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bpReeQs8Zea1xFv5" 
tags:
  - pf2e/creature/type/beast
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/4
  - remaster
statblock: inline
name: "Minotaur Hunter"
level: 4
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Minotaur Hunter"
level: "Creature 4"

alignment: ""
size: "Large"
trait_01: [[beast]]
trait_02: [[humanoid]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Darkvision"
languages: "Jotun, Common"
skills:
  - name: "Skills"
    desc: "Athletics: +14, Intimidation: +9, Survival: +12"
abilityMods: [6, 0, 3, -2, 2, -1]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +13, __Ref__ +8, __Will__ +10"
hp: 70
health:
  - name: ""
  - name: HP
    desc: "70"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Greataxe|Greataxe]]"
  - name: "Perfect Orienteering"
    desc: "  A minotaur automatically critically succeeds at Survival checks to Sense Direction or Track."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Greataxe"
    desc: "+14 (reach 10 feet, sweep)\n__Damage__  1d12 + 8 slashing"

  - name: "**Melee** `pf2:1` Horn"
    desc: "+14 ()\n__Damage__  1d8 + 8 piercing"

  - name: "Axe Swipe"
    desc: "`pf2:2`  The minotaur swings their axe in a wide arc, making greataxe Strikes against any two foes who are adjacent to each other and within the minotaur's reach. The multiple attack penalty does not increase until after both attacks are resolved."

  - name: "Hunted Fear"
    desc: "`pf2:1`  The minotaur snorts and clomps as they hunt their prey, inspiring terror. The minotaur makes an Intimidation check to [[Actions/Demoralize|Demoralize]] all living creatures within 60 feet that can hear the minotaur but not see them. Roll once and apply the result to all creatures.\n\nIf the targets are in a maze or similarly difficult-to-navigate structure, the minotaur gains a +4 circumstance bonus to this check. Creatures that become frightened as a result also take a –2 circumstance penalty to Survival checks to avoid getting lost for 1 minute. Each target is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Hunted Fear|Effect: Hunted Fear]]"

  - name: "Powerful Charge"
    desc: "`pf2:2`  The minotaur Strides twice, then makes a horn Strike. If they moved at least 20 feet from their starting position, the Strike's damage is increased to 2d8+10."
 
```

```encounter-table
name: Minotaur Hunter
creatures:
  - 1: Minotaur Hunter
```



A minotaur is a large humanoid with bovine features such as horns, hooves, and a layer of hair that covers their entire body. Their head also resembles that of a bull or cow, though with eyes that brim with curiosity or fury, depending on the minotaur's temperament. Though often mistaken for aggressive brutes due to their size and reputation, many minotaurs are skilled artisans who spend much of their lives perfecting their craft. Minotaur communities tend to be insular and are found at the heart of a cunning labyrinth or within a tangle of underground caverns.

The myth many minotaurs like to tell of their origin involves a stonemason living in ancient Iblydos. After accidentally insulting a hero-god, he was cursed to become the first minotaur. He then retreated into a series of caves beneath a temple he had built, but continued his work, sculpting stone statues for any who dared to brave the subterranean passages.

Sometimes, a lone minotaur is compelled, exiled, or chooses to live alone within a maze, a warren, or old ruins. This solitude drives them to become a monstrous tormentor who delights in hunting any who stumble across their lair. They slowly close in on their prey, thrilling in the terror of the hunted becoming lost within corridors the minotaur knows all too well. Only then does the minotaur charge in for the kill, cutting foes down with powerful strikes or impaling them on their sharp horns. Unfortunately, the world tends to judge all minotaurs by the stories of these lone, vicious hunters.
