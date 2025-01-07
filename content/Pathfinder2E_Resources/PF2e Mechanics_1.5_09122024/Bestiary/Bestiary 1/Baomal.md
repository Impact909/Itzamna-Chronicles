---
title: "Baomal"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.gWDdujpeU1wHORXj" 
tags:
  - pf2e/creature/type/aberration
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/chaotic
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Baomal"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Baomal"
level: "Creature 20"

alignment: ""
size: "grg"
trait_01: [[aberration]]
trait_02: [[aquatic]]
trait_03: [[chaotic]]
modifier: 34
perception:
  - name: "Perception"
    desc: "+34; Darkvision, Scent (Imprecise) 80 Feet"
languages: "Aklo"
skills:
  - name: "Skills"
    desc: "Athletics: +41, Stealth: +31, Survival: +37"
abilityMods: [10, 2, 8, -3, 6, 1]
speed: 50 feet,  swim 80 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 48
armorclass:
  - name: AC
    desc: "48 all-around vision; __Fort__ +36, __Ref__ +30, __Will__ +34"
hp: 315
health:
  - name: ""
  - name: HP
    desc: "315; __Resistances__ physical 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Double Opportunity"
    desc: "  A baomal gains an extra reaction each round that it can use only to make an Attack of Opportunity. It must use a different head for each one it attempts, and it can't make more than one Attack of Opportunity for the same triggering action."

  - name: "Psychic Static Aura"
    desc: " (aura,mental,occult) 120 feet. All creatures, except aberrations, that begin their turn in the area take 5d6 mental damage."

  - name: "Two Heads"
    desc: "  Any ability that would sever a baomal's head (such as a critical hit with a _[[Equipment/Vorpal|Vorpal]]_ weapon) severs one head at random. Losing one head doesn't kill a baomal, but it does prevent the baomal from making Strikes with the lost head and from using Double Opportunity or Two-Headed Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (reach 20 feet)\n__Damage__  4d12 + 18 piercing plus improved-grab"

  - name: "**Ranged** `pf2:1` Tsunami Jet"
    desc: "+38 (brutal, range 500 feet)\n__Damage__  4d10 + 18 bludgeoning plus push"

  - name: "Breath of the Sea"
    desc: "`pf2:1` (attack) A baomal can inhale tremendous amounts of water, drawing everything in the sea nearby closer. All creatures and objects in the water within 60 feet of the baomal (including ships) are pulled toward it. Creatures must succeed at a DC 42 Athletics check check or be pulled up to 20 feet toward the baomal (40 feet on a critical failure). For ships, use the captain's Sailing Lore in place of Athletics. Unattended objects are automatically pulled."

  - name: "Shell Rake"
    desc: "`pf2:1` (move) The baomal Swims or Strides alongside a creature or the hull of a vessel, dealing damage with the strong spikes on its shell. Each creature or ship the baomal is adjacent to at any point during its movement takes 6d6+10 slashing and piercing damage (DC 42 Reflex check save). Against vessels, Shell Rake ignores the first 5 Hardness and creates an explosion of splinters that deals 3d6+5 damage to every creature within 10 feet of the deck's edge (DC 42 Reflex check save)."

  - name: "Two-Headed Strike"
    desc: "`pf2:2`  The baomal makes a Strike with each set of jaws, each against a different creature. These Strikes count as one attack for the baomal's multiple attack penalty, and the penalty doesn't increase until after both attacks."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Push|Push 40 feet]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Push in its damage entry\n* * *\n\n**Effect** The monster attempts to [[Actions/Shove|Shove]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty. If Push lists a distance, change the distance the creature is pushed on a success to that distance."
 
```

```encounter-table
name: Baomal
creatures:
  - 1: Baomal
```



Few sea monsters are as dreaded and feared as the two-headed baomal. These massive predatory beasts typically dwell in the deepest waters and compete with krakens and other monsters for food. They feed on whales and other large sea creatures, sometimes following them to the water's surface. Near the surface, baomals that encounter ships quickly learn that they contain a variety of tasty morsels. The creatures use their devastating spikes to rip open the ships' hulls, then leisurely feed on the helpless sailors.
