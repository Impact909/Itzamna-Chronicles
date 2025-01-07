---
title: "Enormous Dragonfly"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mHlJVHWdwYMFno6e" 
tags:
  - pf2e/creature/type/animal
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Enormous Dragonfly"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Enormous Dragonfly"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[animal]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Wavesense (Imprecise) 30 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +19, Stealth: +19"
abilityMods: [6, 4, 2, -5, 3, 0]
speed: 20 feet,  fly 60 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +21, __Will__ +14"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Imprecise) 30 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Mandibles"
    desc: "+20 ()\n__Damage__  2d12 + 9 piercing plus grab"

  - name: "Clutch"
    desc: "`pf2:1`  **Requirements** The enormous dragonfly has a Large or smaller creature [[Conditions/Grabbed|Grabbed]] in its mandibles\n\n**Effect** The dragonfly tries to transfer the grabbed creature to be clutched by its legs. The enormous dragonfly attempts an Athletics check check against the creature's Reflex DC. On a success, it transfers the creature (which remains grabbed) to its legs, freeing its mandibles to attack. The dragonfly can have only one creature clutched at a time."

  - name: "Snatch"
    desc: "  The enormous dragonfly can [[Actions/Fly|Fly]] at half Speed while it has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by Clutch, carrying that creature along with it."

  - name: "Swoop"
    desc: "`pf2:2`  The dragonfly Flies up to its Speed and makes one mandible Strike at any point during that movement."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Enormous Dragonfly
creatures:
  - 1: Enormous Dragonfly
```


Variant giant dragonfly

These buzzing insects are the size of a small horse. They are ambush predators known to hunt beasts and humanoids alike, capable of using impressive aerial acrobatics to swoop down from above and snatch away their prey.
