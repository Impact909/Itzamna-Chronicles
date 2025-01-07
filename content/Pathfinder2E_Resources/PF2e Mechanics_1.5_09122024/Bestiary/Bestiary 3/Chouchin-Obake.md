---
title: "Chouchin-Obake"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.kiObUUHsJarW5lSO" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/kami
  - pf2eMonster
  - pf2e/creature/level/6
statblock: inline
name: "Chouchin-Obake"
level: 6
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Chouchin-Obake"
level: "Creature 6"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[kami]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; "
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +12, Deception: +10, Stealth: +16"
abilityMods: [2, 4, 4, 3, 5, 0]
speed:  fly 20 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +12, __Ref__ +16, __Will__ +15"
hp: 75
health:
  - name: ""
  - name: HP
    desc: "75; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  paralyzed,  poison,  unconscious; __Resistances__ physical 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Lifewick Candle"
    desc: " (aura,divine,void) 15 feet. A ghostly blue flame within the chouchin-obake draws upon the life-force of the living to sustain themself.\n\nAt the start of the chouchin-obake's turn, each creature in the aura takes 2d6 void damage (DC 26 Fortitude check save). The chouchin-obake regains an amount of Hit Points equal to the amount of damage taken by the single creature that took the most damage."

  - name: "Shadowbind"
    desc: "`pf2:r`  **Trigger** A creature attempts to leave the chouchin-obake's Lifewick Candle aura during a move action\n* * *\n\n**Effect** The chouchin-obake attempts to bind the creature using their own shadow. The triggering creature must succeed at a DC 26 Reflex check save or become [[Conditions/Immobilized|Immobilized]] until its next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+16 (finesse, reach 15 feet)\n__Damage__  2d8 void plus grab 2d6 fire plus grab"

  - name: "**Ranged** `pf2:1` Flame"
    desc: "+16 (range increment 30 feet)\n__Damage__  2d4 void 2d6 fire"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8 void plus 1d6 fire, DC 26 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Chouchin-Obake
creatures:
  - 1: Chouchin-Obake
```



A chouchin-obake takes the shape of a paper lantern with a horizontal split near the bottom from which a long tongue protrudes. Upon closer inspection, two eyes appear above the split mouth. Chouchin-obake are anomalous in that they don't awaken in the same way other tsukumogami do. Paper lanterns are nearly impossible to maintain for long enough to spawn tsukumogami. Instead, a chouchin-obake is a kind of fire kami that takes the form of a lantern's flame and inhabits a paper lantern when they manifest.

* * *

Tsukumogami are intelligent, mobile objects formed from the union between a 100-year-old object and a kami. Tsukumogami range from harmless to malicious, each individual personality a result of how the object was treated before its awakening. Well-cared-for objects tend to birth helpful, friendly tsukumogami, while mistreated or abandoned objects twist into malevolent and violent beings.Most tsukumogami are, by nature, mischievous, and oftentimes want nothing more than to occupy the attention of living creatures.

Tsukumogami can commonly be found in areas with a strong cultural belief iin the value of caring for objects, which helps items survive long enough to become tsukumogami. Towns and villages with large tsukumogami populations are referred to as "sleepless towns" due to the nightly tsukumogami celebrations, which can become so raucous that they prevent the living residents from sleeping peacefully.
