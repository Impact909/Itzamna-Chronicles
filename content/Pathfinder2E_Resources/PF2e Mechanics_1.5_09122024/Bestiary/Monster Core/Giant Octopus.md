---
title: "Giant Octopus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Zo0BK6m36F9gYhfd" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/8
  - remaster
statblock: inline
name: "Giant Octopus"
level: 8
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Giant Octopus"
level: "Creature 8"

alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +20, Stealth: +17"
abilityMods: [6, 3, 4, -4, 3, -2]
speed: 15 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +16, __Ref__ +17, __Will__ +15"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Resistances__ cold 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Arm"
    desc: "+20 (agile, reach 15 feet)\n__Damage__  2d8 + 9 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Beak"
    desc: "+20 ()\n__Damage__  2d8 + 9 piercing plus giant-octopus-venom"

  - name: "Compression"
    desc: "  A giant octopus can move through a gap at least 2 feet wide without Squeezing, and can [[Actions/Squeeze|Squeeze]] through a gap at least 1 foot wide."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+9 bludgeoning, DC 26 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Giant Octopus Venom"
    desc: " (poison) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 1]], and off-guard (1 round)\n\n**Stage 3** 2d6 poison damage, [[Conditions/Clumsy|Clumsy 2]], and off-guard (1 round)"

  - name: "Ink Cloud"
    desc: "`pf2:1`  The octopus emits a cloud of black ink in a 30-foot emanation. This cloud has no effect outside of water. Creatures inside the cloud are [[Conditions/Undetected|Undetected]] and can't use their sense of smell. The cloud dissipates after 1 minute.\n\nThe octopus can't use Ink Cloud again for 2d6 rounds."

  - name: "Jet"
    desc: "`pf2:2` (move) The octopus moves up to 200 feet in a straight line through the water without triggering reactions."

  - name: "Writhing Arms"
    desc: "`pf2:2`  The giant octopus makes up to four Strikes with different arms, each against a different target. Each attack counts separately for the octopus's multiple attack penalty, but the penalty doesn't increase the until the octopus has made all the attacks.\n\nIf the octopus subsequently uses the [[Bestiary Ability Glossary/Grab|Grab]] action, it can Grab any number of creatures it hit with Writhing Arms."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Octopus
creatures:
  - 1: Giant Octopus
```



Giant octopuses are found in the heart of deep, dark oceans. Clever and adaptable, they hunt and devour all manner of animals. Despite growing up to 16 feet long, a giant octopus can compress its body to squeeze through small gaps as long as there's room for its beak.

Giant octopuses favor shipwrecks, coral reefs, or underwater caverns as lairs, where they can take advantage of narrow confines for protection. Like their smaller kin, they're fond of adorning and decorating their lairs with found objects—many of which, in the giant octopus's case, are also magical weapons, shields, or works of art salvaged from sunken ships or fallen adventurers.
