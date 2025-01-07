---
title: "Black Scorpion"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.pdji1m0W3uxYKrhW" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Black Scorpion"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Black Scorpion"
level: "Creature 15"

alignment: ""
size: "grg"
trait_01: [[animal]]
modifier: 27
perception:
  - name: "Perception"
    desc: "+27; Darkvision, Tremorsense (Imprecise) 90 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +30"
abilityMods: [9, 4, 6, -5, 6, -4]
speed: 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 38
armorclass:
  - name: AC
    desc: "38; __Fort__ +29, __Ref__ +25, __Will__ +25"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 90 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pincer"
    desc: "+30 (agile, reach 30 feet)\n__Damage__  3d12 + 15 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+30 (reach 30 feet)\n__Damage__  3d8 + 15 piercing plus black-scorpion-venom"

  - name: "Black Scorpion Venom"
    desc: " (poison) **Saving Throw** DC 36 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d12 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 2** 3d12 poison damage, [[Conditions/Clumsy|Clumsy 2]], and [[Conditions/Slowed|Slowed 1]] (1 round)\n\n**Stage 3** 4d12 poison damage, [[Conditions/Clumsy|Clumsy 4]], and [[Conditions/Slowed|Slowed 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Greater Constrict|Greater Constrict]]"
    desc: "`pf2:1`  2d12+12 bludgeoning damage, DC 36 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC. A creature that fails this save falls [[Conditions/Unconscious|Unconscious]], and a creature that succeeds is then temporarily immune to falling unconscious from Greater Constrict for 1 minute."

  - name: "Rapid Stinging"
    desc: "`pf2:2`  The black scorpion makes three stinger Strikes, each against a different target. Its multiple attack penalty applies to each attack, but the penalty increases only after all the attacks have been made."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Black Scorpion
creatures:
  - 1: Black Scorpion
```



With a carapace the color of polished obsidian and a penchant for attacking villages, this humongous scorpion is one of the desert's most frightening predators. A black scorpion measures 60 feet from tip to the base of its stinger.
