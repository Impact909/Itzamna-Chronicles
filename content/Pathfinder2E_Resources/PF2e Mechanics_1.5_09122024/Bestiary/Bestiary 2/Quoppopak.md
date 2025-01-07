---
title: "Quoppopak"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.mnYVNK07EcyvbO1m" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Quoppopak"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Quoppopak"
level: "Creature 11"

alignment: ""
size: "Large"
trait_01: [[aberration]]
trait_02: [[aquatic]]
trait_03: [[evil]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Low-Light Vision"
languages: "Thalassic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +23, Athletics: +22, Stealth: +23"
abilityMods: [7, 6, 5, -2, 5, 0]
speed: 15 feet,  swim 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +22, __Ref__ +23, __Will__ +18"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity (Tentacle Only)]]"
    desc: "`pf2:r`  Tentacle only\n* * *\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Beak"
    desc: "+24 (reach 10 feet)\n__Damage__  3d8 + 13 piercing"

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+24 (agile, reach 15 feet)\n__Damage__  2d8 + 13 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Ventral Tube"
    desc: "+24 (reach 10 feet)\n__Damage__  2d6 + 13 slashing 1d6 bleed"

  - name: "**Ranged** `pf2:1` Water Jet"
    desc: "+23 (range increment 100 feet, water)\n__Damage__  2d6 + 13 bludgeoning plus push"

  - name: "Flooding Thrust"
    desc: "`pf2:2`  **Requirements** The quoppopak's ventral tube is in water\n* * *\n\n**Effect** The quoppopak uses Tentacle Stab against a creature within reach; if either of these Strikes hits, the creature must attempt a DC 30 Reflex check save. On a failed save, the quoppopak shoots water through its tentacles into the creature, dealing 2d6+5 bludgeoning damage and making the creature [[Conditions/Sickened|Sickened 1]] as its internal organs fill with water (double damage and [[Conditions/Sickened|Sickened 2]] on a critical failure)."

  - name: "Tentacle Stab"
    desc: "`pf2:1`  **Frequency** once per round\n* * *\n\n**Effect** The quoppopak makes two tentacle Strikes against the same creature. These Strikes deal piercing damage instead of bludgeoning, and the quoppopak can't [[Bestiary Ability Glossary/Grab|Grab]] with them. Its multiple attack penalty doesn't increase until after both attacks."

  - name: "Water Glide"
    desc: "  The quoppopak can stand and move on the surface of water or other liquids without falling through. It can go underwater if it wishes, but it must [[Actions/Swim|Swim]] to do so."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Push|Push]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Quoppopak
creatures:
  - 1: Quoppopak
```



Quoppopaks combine the most terrifying aspects of water striders, octopuses, and vampire bats into one evil, water-dwelling monster. Their bodies consist of an oval abdomen, eight hollow tentacles, and a thick, tail-like limb ending in a ventral tube, which resembles a lamprey's mouth and is capable of intaking fluids at an astounding rate. While quoppopaks can clumsily maneuver on land, they prefer to move on water; quoppopaks glide along the surface of lakes or the ocean by thrusting their ventral tubes into the water, cycling liquid up through their bodies, then spraying the water back out in a high-pressure stream through their hollow, spear-like tentacles. Though the ventral tube can't expel fluids, it still poses a substantial threat to other creatures. Quoppopaks have gills, but they are located inside the creatures' abdomens, allowing them to draw their air from the water they siphon through their ventral tubes. Quoppopaks can hold some water in their abdomens for quick forays on land, but this is akin to humans holding their breath to go underwater, and the monsters' water reserves quickly deplete.
