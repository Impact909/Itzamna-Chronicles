---
title: "Girtablilu Guardian"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.qQMPYawdpwX6YyLj" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Girtablilu Guardian"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Girtablilu Guardian"
level: "Creature 10"
rare_03: [[Rare]]
alignment: ""
size: "Large"
trait_01: [[beast]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Common, Girtablilu"
skills:
  - name: "Skills"
    desc: "Athletics: +22, Intimidation: +19, Religion: +20, Survival: +22"
abilityMods: [6, 4, 6, 3, 6, 3]
speed: 40 feet
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +18, __Will__ +22"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Shortbow|+2 Striking Flaming Shortbow]], [[Equipment/Temple Sword|+1 Striking Flaming Temple Sword]], [[Equipment/Steel Shield|Steel Shield]], [[Equipment/Hide Armor|+1 Hide Armor]], 20x [[Equipment/Arrows|Arrows]]"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Shield Block|Shield Block]]"
    desc: "`pf2:r`  **Trigger** The monster has its shield raised and takes damage from a physical attack.\n* * *\n\n**Effect** The monster snaps its shield into place to deflect a blow. The shield prevents the monster from taking an amount of damage up to the shield's Hardness. The monster and the shield each take any remaining damage, possibly breaking or destroying the shield."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+22 (agile)\n__Damage__  2d8 + 12 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+22 (reach 10 feet)\n__Damage__  2d6 + 12 piercing plus girtablilu-venom"

  - name: "**Melee** `pf2:1` Temple Sword"
    desc: "+23 (monk, trip)\n__Damage__  2d8 + 12 slashing 1d6 fire"

  - name: "**Ranged** `pf2:1` Shortbow"
    desc: "+22 (deadly d10, range increment 60 feet, reload 0)\n__Damage__  2d6 + 6 piercing 1d6 fire"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+9 bludgeoning, DC 26 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Desert Stride"
    desc: "  A girtablilu ignores natural difficult terrain in the desert."

  - name: "Girtablilu Venom"
    desc: " (poison) **Saving Throw** DC 28 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Enfeebled|Enfeebled 1]] (1 round)\n\n**Stage 2** 3d6 poison damage and enfeebled 1 (1 round)\n\n**Stage 3** 3d6 poison damage and [[Conditions/Enfeebled|Enfeebled 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Girtablilu Guardian
creatures:
  - 1: Girtablilu Guardian
```


Variant girtablilu sentry

Sentries patrol the outskirts of a girtablilu communities, watching for external threats like desert drakes, blue dragons, or adventuring parties set on reckless exploration of the girtablilus' sacred site.

* * *

Girtablilus are desert-dwelling guardians with the upper bodies of muscular humanoids and the lower bodies of massive scorpions. They are most often found defending ancient temples and religious artifacts with zealous fervor. Some believe they were created by a long-dead god millennia ago to act as guardians, but girtablilus consider the subject of their origin taboo and refuse to address the theory.

Because girtablilus accept a wide range of religions and belief systems, some outsiders believe they also worship their own ancient pantheon. Instead, girtablilus exclusively revere and protect sites dedicated to deities considered lost to civilization. In this way, they act as preservers of holy practices that have otherwise been forgotten beneath the desert's shifting sands.

Though girtablilus are used to explorers seeking entrance to the sites they defend, they might welcome those who earnestly wish to learn or offer reverence. A few even proudly share their beliefs with others, eager for the opportunity to preach to someone new. But girtablilus show no mercy to those who attempt to desecrate the sites and objects of their worship, or to those who would violate the tenets of their faith.

Girtablilus are skilled fighters who keep trained giant scorpions as pets, and they remain unmatched when it comes to fighting in the desert. They require relatively little food or water, and they rely on their stamina to outlast their enemies. When necessary, they can stalk their quarry for days or even weeks, coordinating with their pets to drive their prey in circles. Once exhausted, few foes can stand up to a girtablilu's physical prowess-or their deadly venom.
