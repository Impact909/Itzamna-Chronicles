---
title: "Sabosan"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.H3cfvIo8GiwJLtg8" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/5
statblock: inline
name: "Sabosan"
level: 5
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Sabosan"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Echolocation 20 Feet, Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Chthonian, Mwangi"
skills:
  - name: "Skills"
    desc: "Acrobatics: +16, Athletics: +11, Stealth: +16"
abilityMods: [4, 5, 2, -1, 1, 0]
speed: 25 feet,  fly 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +11, __Ref__ +14, __Will__ +10"
hp: 78
health:
  - name: ""
  - name: HP
    desc: "78"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spear|Spear]]"
  - name: "Echolocation 20 feet"
    desc: "  A sabosan can use their hearing as a precise sense at the listed range."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+15 (finesse)\n__Damage__  2d10 + 4 piercing 1 bleed"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+15 (agile, finesse)\n__Damage__  2d8 + 4 slashing plus grab"

  - name: "**Melee** `pf2:1` Spear"
    desc: "+15 ()\n__Damage__  1d6 + 7 piercing"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+16 (thrown 20 ft.)\n__Damage__  1d6 + 7 piercing"

  - name: "Drain Blood"
    desc: "`pf2:1`  **Requirements** The sabosan has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The sabosan drains blood from the creature. The creature must succeed at a DC 23 Fortitude check save or become [[Conditions/Drained|Drained 1]]. The sabosan gains a number of temporary Hit Points equal to the number of Hit Points lost by the creature."

  - name: "Fell Shriek"
    desc: "`pf2:2` (auditory) The sabosan emits a deafening cry in a 30-foot cone. Non-sabosan creatures in this area must each succeed at a DC 23 Fortitude check save or be [[Conditions/Deafened|Deafened]] for 1 minute."

  - name: "Powerful Charge"
    desc: "`pf2:2`  The sabosan Strides up to double their Speed and then makes a claw Strike. If the sabosan moved at least 20 feet, they deal an additional 1d6 damage on a hit."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sabosan
creatures:
  - 1: Sabosan
```



Sabosans are intelligent, bat-like humanoids who live in warm forests and drink the blood of other creatures, particularly people. They have thin, emaciated torsos and broad, leathery wings that can reach a span of almost 20 feet. Sabosans' heads, necks, shoulders, and upper chests are covered with red or dark-brown fur that obscures their stretched-thin flesh. Though their ears are large and pointed like a bat's and they can echolocate as bats do, their vision is also quite strong, enough so that they can use it to easily track quarry in low light.

Some naturalist scholars believe that sabosans are distant descendants of humans who were afflicted with vampirism but managed to avoid succumbing to undeath. Others posit they were once a cult of demon worshippers whose dark rites transformed them into their current forms. No matter their true origins, sabosans have infamous reputations among towns and cities south of Golarion's equator. Even mere rumors of sabosans in an area are enough to set off city-wide hunts, and the truly superstitious aren't above setting fires near every grotto, nook, and foxhole they come across in order to smoke out the nocturnal creatures.

Sabosans hunt during the twilight hours or just after dark, when their echolocation gives them an edge over sleeping prey. They are capable hunters but indiscriminating when it comes to food sources; their rapid metabolisms means sabosans must eat nearly 20 pounds of meat and fruit per day, supplemented, of course, with copious amounts of blood.

Sabosans' obscure faith reveres two deities: the slain Demon Lord Vyriavaxus, Lord of Shadows, and the nearly forgotten sun god Easivra. Vyriavaxus has an obvious link with the creatures, with his appearance as a giant bat, but their connection to the sun god hints at a complex depth in sabosan beliefs.
