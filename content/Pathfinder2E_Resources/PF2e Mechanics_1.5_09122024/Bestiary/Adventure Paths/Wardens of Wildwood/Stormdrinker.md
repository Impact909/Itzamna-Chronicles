---
title: "Stormdrinker"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.zWAz2bgQHaTTTNtg" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Stormdrinker"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #201: Pactbreaker"
name: "Stormdrinker"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[plant]]
modifier: 14
perception:
  - name: "Perception"
    desc: "+14; Darkvision"
languages: "Common, Fey; (Can&#x27;t Speak any Language)"
skills:
  - name: "Skills"
    desc: "Athletics: +17, Stealth: +13"
abilityMods: [6, 1, 5, -2, 3, -1]
speed: 20 feet,  swim 20 feet
sourcebook: "_Pathfinder #201: Pactbreaker_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +18, __Ref__ +12, __Will__ +15"
hp: 145
health:
  - name: ""
  - name: HP
    desc: "145; __Immunities__  electricity; __Resistances__ fire 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Absorb Shock"
    desc: "  Whenever the stormdrinker would take electricity damage or is targeted with an electricity effect, it gains 10 temporary HP, is [[Conditions/Quickened|Quickened]], and increases the reach of its vine Strikes by 5 feet until the end of its next turn. It can use its extra action to Stride, Strike, or Swim.\n\n[[Bestiary Effects/Effect_ Absorb Shock|Effect: Absorb Shock]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vine"
    desc: "+18 (reach 10 feet)\n__Damage__  2d10 + 8 bludgeoning plus grab"

  - name: "Lightning Blast"
    desc: "`pf2:2`  **Requirements** The stormdrinker is [[Conditions/Quickened|Quickened]] due to Absorb Shock\n* * *\n\n**Effect** The stormdrinker dismisses its Absorb Shock benefits to expel lightning in a 60-foot line, dealing 8d6 electricity damage (DC 25 Reflex check save)."

  - name: "Ring Bell"
    desc: "`pf2:1` (auditory) **Requirements** The stormdrinker is carrying a bell\n* * *\n\n**Effect** The stormdrinker rings its bell, signaling Tumbo to bite him once. (Multiple bites don't stack their effects on the stormdrinker.) The stormdrinker can't use this ability when it doesn't have its bell, such as if it is Disarmed."

  - name: "Vine Lash"
    desc: "`pf2:2`  The stormdrinker makes a vine Strike against each creature within reach. Its multiple attack penalty increases only after all the attacks."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Stormdrinker
creatures:
  - 1: Stormdrinker
```




