---
title: "Crying Cicada"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MJ2SHTuN9OJG4bnK" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Crying Cicada"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Howl of the Wild"
name: "Crying Cicada"
level: "Creature 3"

alignment: ""
size: "Small"
trait_01: [[animal]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; "
languages: ""
skills:
  - name: "Skills"
    desc: "Deception: +12, Stealth: +10, Survival: +8"
abilityMods: [2, 4, 5, -5, 1, 3]
speed: 15 feet,  fly 30 feet
sourcebook: "_Pathfinder Howl of the Wild_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +10, __Ref__ +12, __Will__ +7"
hp: 48
health:
  - name: ""
  - name: HP
    desc: "48; __Immunities__  poison"
abilities_top:
  - name: ""

  - name: "Steal Voice"
    desc: "`pf2:2` (auditory) **Requirements** An enemy creature has spoken since the crying cicada's last turn\n* * *\n\n**Effect** The crying cicada learns and mimics the sound of its opponent's voice. It can't make new sentences, but it can choose to repeat select parts of the phrases it has heard. All non-cicada creatures within 30 feet, other than the owner of the stolen voice, must succeed at a DC 19 Will check save to disbelieve the mimicry."

abilities_mid:
  - name: ""
  - name: "Wings Flat"
    desc: "  When the crying cicada is still and perched on a tree, it blends seamlessly into the environment. It has an automatic result of 30 on Deception checks and DCs to pass as part of the tree."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Proboscis"
    desc: "+9 ()\n__Damage__  1d8 + 5 piercing 1d4 poison"

  - name: "**Melee** `pf2:1` Slam"
    desc: "+9 ()\n__Damage__  1d6 + 4 bludgeoning plus crying-cicada-poison"

  - name: "Crying Cicada Poison"
    desc: " (inhaled,poison) **Saving Throw** DC 19 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 1d6 poison damage plus [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 2** 1d6 poison damage plus [[Conditions/Slowed|Slowed 2]] (1 round)\n\n**Stage 3** 2d6 poison damage plus slowed 2 and [[Conditions/Stupefied|Stupefied 1]] (1 round)."

  - name: "Sob"
    desc: "`pf2:1` (auditory,emotion,mental) The crying cicada mimics the noise of a wounded animal or crying child. Non-cicada creatures within a 150-foot emanation must attempt a DC 19 Will check save or be distressed by the pleas for help. The effect lasts for 1 round, but if the cicada uses this ability again on subsequent rounds, it extends the duration by 1 round for all affected creatures. Once a creature succeeds at any save against Sob, that creature is temporarily immune to Sob for 24 hours.\n* * *\n\n**Success** The creature is unaffected.\n\n**Failure** The creature believes an animal or child needs help somewhere nearby. The creature is [[Conditions/Fascinated|Fascinated]], and it must spend each of its actions to [[Actions/Seek|Seek]] or move closer to the cicada as expediently as possible, while avoiding obvious dangers. If the creature is adjacent to the cicada, it stays still and doesn't act."

  - name: "Wing Flurry"
    desc: "`pf2:1`  The crying cicada beats its wings together, exposing all creatures within a 10-foot burst to crying cicada poison."
 
```

```encounter-table
name: Crying Cicada
creatures:
  - 1: Crying Cicada
```



These small insects are a nuisance and danger to small villages within Brevoy, taking over entire forests and blending in with the foliage. Also known as calling beetles, due to their ability to mimic and repeat the voices of their previous victims, crying cicadas wait for passersby to lure into the trees, fascinating their victims with their cries before fluttering their wings to release toxic dust. Once a target is near death, crying cicadas will take flight from the trees and land on the body to feed.

The scale dust of crying cicadas can be turned into an effective ingested poison, but obtaining a cicada and harvesting these scales is so dangerous that most would-be poisoners simply die in the process. Even finding the insects is dangerous enough; crying cicadas' natural stealth and dark coloration make them difficult to locate among the trees of a forest, and following their cries often leads one to fall victim to the very creatures they're hunting.

The longer a colony of crying cicadas stays in a forest, the wider their collection of cries grows. Often, a young colony will be able to replicate only the sounds of small, dying creatures, but larger, more established colonies will have the ability to mimic the sounds of children and dragons.
