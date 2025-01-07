---
title: "Sargassum Heap"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Djl1lZDfP1pvg1In" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Sargassum Heap"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Sargassum Heap"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[plant]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Wavesense (Precise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +17, Stealth: +14"
abilityMods: [5, 4, 5, -4, 2, 0]
speed: 10 feet,  climb 10 feet,  swim 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__ +17, __Ref__ +14, __Will__ +10"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Immunities__  critical hits,  precision,  unconscious; __Weaknesses__ slashing 5; __Resistances__ cold 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Precise) 60 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
  - name: "Mirage Spores"
    desc: " (aura,incapacitation,mental) 120 feet.\n\nThe sargassum heap constantly produces a field of hallucinogenic spores that causes those affected to see the monster as whatever they desire most. Each creature within the emanation must succeed a DC 22 Will check save or become [[Conditions/Fascinated|Fascinated]] with the sargassum heap and compelled to move toward it on the creature's turn. Creatures fascinated this way are also [[Conditions/Off-Guard|Off-Guard]]. If the sargassum heap attacks, the fascinated condition ends only for the creature that is attacked. On a successful save, a creature is temporarily immune to mirage spores for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+17 (reach 10 feet)\n__Damage__  2d8 + 8 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d8+3 bludgeoning, DC 23 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Sargassum Heap
creatures:
  - 1: Sargassum Heap
```



A sargassum heap is a mass of semi-intelligent seaweed that floats through the ocean, luring in its victims with hallucinogenic spores. Those affected by the spores are drawn towards the heap, envisioning their heart's desire. This might be a lost loved one, a child in need of help, an enchanting mermaid, the promise of dry land, and so on. Once their prey is close enough, the sargassum heap lashes out with its seaweed tendrils and crushes it to death.
