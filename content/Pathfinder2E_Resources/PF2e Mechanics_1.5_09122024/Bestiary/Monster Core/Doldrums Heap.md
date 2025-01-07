---
title: "Doldrums Heap"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.awQzQaOUPA2biEbP" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Doldrums Heap"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Doldrums Heap"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[amphibious]]
trait_02: [[plant]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Wavesense (Precise) 120 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +21, Stealth: +18"
abilityMods: [6, 4, 5, -4, 2, 0]
speed: 20 feet,  climb 20 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +21, __Ref__ +18, __Will__ +15"
hp: 300
health:
  - name: ""
  - name: HP
    desc: "300; __Immunities__  critical hits,  precision,  unconscious; __Weaknesses__ slashing 10; __Resistances__ cold 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Wavesense|Wavesense (Precise) 120 feet]]"
    desc: "  This sense allows a monster to feel vibrations caused by movement through a liquid. It's an imprecise sense with a limited range (listed in the ability). Wavesense functions only if monster and the subject are in the same body of liquid, and only if the subject is moving through the liquid."

abilities_mid:
  - name: ""
  - name: "Mirage Spores"
    desc: " (aura,incapacitation,mental) 300 feet.\n\nThe sargassum heap constantly produces a field of hallucinogenic spores that causes those affected to see the monster as whatever they desire most. Each creature within the emanation must succeed a DC 27 Will check save or become [[Conditions/Fascinated|Fascinated]] with the sargassum heap and compelled to move toward it on the creature's turn. Creatures fascinated this way are also [[Conditions/Off-Guard|Off-Guard]]. If the sargassum heap attacks, the fascinated condition ends only for the creature that is attacked. On a successful save, a creature is temporarily immune to mirage spores for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendrils"
    desc: "+21 (reach 15 feet)\n__Damage__  2d12 + 10 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d12+10 bludgeoning, DC 28 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Draw In"
    desc: "`pf2:2`  The doldrums heap attempts to [[Actions/Reposition|Reposition]] up to three creatures it has [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]. These attempts neither apply nor count toward the heap's multiple attack penalty.\n\nIt can move them into its own space, dealing 1d12+10 bludgeoning damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Doldrums Heap
creatures:
  - 1: Doldrums Heap
```



Though most sargassum heaps divide once they grow too large, occasionally a heap will continue to grow indefinitely. These "doldrum heaps" can tangle and immobilize ships, tearing them apart or feasting on the hapless passengers.

* * *

A sargassum heap is a mass of semi-intelligent seaweed that floats through the ocean, luring in its victims with hallucinogenic spores. Those affected by the spores are drawn towards the heap, envisioning their heart's desire. This might be a lost loved one, a child in need of help, an enchanting mermaid, the promise of dry land, and so on. Once their prey is close enough, the sargassum heap lashes out with its seaweed tendrils and crushes it to death.
