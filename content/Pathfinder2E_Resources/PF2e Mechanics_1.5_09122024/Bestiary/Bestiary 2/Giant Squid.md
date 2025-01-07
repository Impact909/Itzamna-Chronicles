---
title: "Giant Squid"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZHPxxsLmH48Z4BnF" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Giant Squid"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Giant Squid"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +20, Stealth: +18"
abilityMods: [7, 3, 4, -4, 6, -2]
speed:  swim 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +15, __Ref__ +18, __Will__ +21"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Resistances__ cold 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+21 ()\n__Damage__  2d12 + 11 piercing"

  - name: "**Melee** `pf2:1` Barbed Tentacles"
    desc: "+21 (agile, reach 25 feet)\n__Damage__  2d10 + 11 slashing plus grab"

  - name: "**Melee** `pf2:1` Arm"
    desc: "+21 (agile, reach 10 feet)\n__Damage__  2d8 + 11 bludgeoning plus improved-grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d10+10 bludgeoning damage, DC 25 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Jet"
    desc: "`pf2:2` (move) The giant squid moves up to 200 feet in a straight line through the water without triggering any reactions."

  - name: "Ravenous Embrace"
    desc: "`pf2:2`  The giant squid makes up to four arm Strikes, each with a different arm and against a different target. The giant squid then makes a beak Strike against one creature that it [[Conditions/Grabbed|Grabbed]] during Ravenous Embrace. Each arm Strike counts separately for the squid's multiple attack penalty, but the penalty doesn't increase until the squid has made all of its arm Strikes; the beak Strike uses the multiple attack penalty as normal."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Giant Squid
creatures:
  - 1: Giant Squid
```



Dwelling deep within the oceans, this huge cephalopod grows up to 45 feet in length and can weigh up to 600 pounds. Its arms and tentacles are lined with hundreds of hooks and suckers, allowing it to seize its prey with ease.
