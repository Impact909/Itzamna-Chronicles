---
title: "Chupacabra"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.tc30rR9I88LBCAih" 
tags:
  - pf2e/creature/type/beast
  - pf2eMonster
  - pf2e/creature/level/3
  - remaster
statblock: inline
name: "Chupacabra"
level: 3
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Chupacabra"
level: "Creature 3"

alignment: ""
size: "Small"
trait_01: [[beast]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Aklo; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Athletics: +9, Stealth: +9"
abilityMods: [3, 4, 2, -3, 2, -2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +9, __Ref__ +11, __Will__ +7"
hp: 45
health:
  - name: ""
  - name: HP
    desc: "45"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (finesse)\n__Damage__  1d10 + 5 piercing plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+11 (agile, finesse)\n__Damage__  1d6 + 5 slashing"

  - name: "Pounce"
    desc: "`pf2:1`  The chupacabra Strides and makes a Strike at the end of that movement. If the chupacabra began this action [[Conditions/Hidden|Hidden]], it remains hidden until after this ability's Strike."

  - name: "Suck Blood"
    desc: "`pf2:1`  **Requirements** The chupacabra has a creature [[Conditions/Grabbed|Grabbed]]\n* * *\n\n**Effect** The chupacabra sucks blood from the grabbed creature. The chupacabra gains the [[Conditions/Quickened|Quickened]] condition for 1 minute and can use the extra action only for Strike and Stride actions.\n\nA chupacabra can't Suck Blood again while it is quickened in this way.\n\nA creature that has its blood drained by a chupacabra is [[Conditions/Drained|Drained 1]] until it receives healing (of any kind or amount)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Chupacabra
creatures:
  - 1: Chupacabra
```



These notorious predators have an undeniable thirst for blood. Chupacabras prefer to prey on the weak and slow, often hiding in wait and watching potential prey for long periods before attacking. Spry and stealthy, they most often make their homes in areas of high grass and protective rock, their slightly reflective scales allowing them to blend in well with such surroundings.

Chupacabras prefer to eat lone travelers and farm animals (particularly goats) and leave little evidence of their presence apart from the grisly, blood-drained husks of their meals. Their tendency to stay out of sight combined with their naturally nocturnal activity often leads superstitious locals to conclude the worst, imagining that a particularly reckless vampire lives in the area.

A typical chupacabra measures nearly 4 feet from its muzzle to the tip of its spiny tail, and it stands just under 3-1/2 feet tall. With their slight build and lightweight bones, most weigh close to 50 pounds. They mate rarely and only during the hottest months, with the females each producing a single egg that hatches into a tiny, dehydrated creature. The mother usually leaves helpless prey in her cave so the hatchling can immediately feed.

Although chupacabras are typically solitary creatures, they have been known to form small gangs in bountiful areas. Members of these groups work well together, growing bold enough to attack larger animals, small herds, and otherwise more dangerous prey. Stories of chupacabras attacking travelers or laying siege to farmhouses typically stem from the hunting practices of such gangs. Regions where chupacabra activity like this is more common often have complex and colorful myths and tall tales about chupacabra capabilities or motive—and a few of the claims, such as that some chupacabras can fly, are all too true.
