---
title: "Damibwa"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.V9yLhLyrFTzMOsUv" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Damibwa"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #170: Spoken on the Song Wind"
name: "Damibwa"
level: "Creature 4"

alignment: ""
size: "Medium"
trait_01: [[animal]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Echolocation 60 Feet, Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +12, Stealth: +10, Survival: +10"
abilityMods: [4, 4, 3, -4, 2, 0]
speed: 30 feet,  swim 30 feet
sourcebook: "_Pathfinder #170: Spoken on the Song Wind_"
ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__ +11, __Ref__ +14, __Will__ +8"
hp: 62
health:
  - name: ""
  - name: HP
    desc: "62"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Deep Breath"
    desc: "  A damibwa can hold its breath for 5 minutes."

  - name: "Echolocation 60 feet"
    desc: "  A damibwa's hearing is a precise sense at the listed range."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+14 ()\n__Damage__  2d8 + 4 piercing plus grab"

  - name: "Fetch"
    desc: "`pf2:1` (attack,move) **Requirements** The damibwa has a Small or smaller creature grabbed in water\n* * *\n\n**Effect** The damibwa attempts an Athletics check check against the creature's Fortitude DC.\n* * *\n\n**Critical Success** The damibwa moves up to its swim Speed, dragging the [[Conditions/Grabbed|Grabbed]] creature along with it.\n\n**Success** The damibwa moves up to half its swim Speed, dragging the grabbed creature along with it.\n\n**Failure** The damibwa doesn't move and the creature isn't dragged.\n\n**Critical Failure** The damibwa no longer has the creature grabbed."

  - name: "Predatory Dive"
    desc: "`pf2:2` (move) **Requirements** The damibwa is in or adjacent to water\n* * *\n\n**Effect** The damibwa moves up to double its swim Speed, descending at least 10 feet, and then makes a jaws Strike. If it was [[Conditions/Undetected|Undetected]] at the start of predatory dive, it remains undetected until after the attack."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Damibwa
creatures:
  - 1: Damibwa
```



Damibwas are domesticated hounds capable of detecting prey or predators via echolocation thanks to their exceptionally large ears and keen hearing. Adept swimmers, damibwas have sleek bodies, short limbs, webbed feet, and long muscular tails that enable them to maneuver underwater with grace and speed.

Trained as specialized hunting hounds, damibwas primarily catch fish, although they're also adept at diving for lobsters, crabs, and clams. While hunting, damibwas wait near the water's edge, typically on a boat or along the shore, listening for choice prey. When they detect prey in range, they dive down below the water, catch the animal in their jaws, and drag it back up to the surface. When large or dangerous aquatic predators approach, damibwas retreat to land and howl a warning, making them desirable guard dogs in coastal or riverside communities. Damibwas rarely attack terrestrial creatures unless they're threatened and unable to make an escape.

Damibwas are popular pets along rivers, lakes, and swamps throughout Golarion, particularly in the River Kingdoms, Wanshou, and the canals of Nantambu in the Mwangi Expanse. Some Erutaki in Avistan's far north hunt seals alongside a particular hardy breed covered in thick fur and a layer of blubber. They are only universally called damibwas in the Mwangi Expanse, and are often called "diving dogs" in other regions.
