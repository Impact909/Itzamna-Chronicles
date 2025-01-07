---
title: "Alchemist Ivy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZUCxX1I8bxfGew80" 
tags:
  - pf2e/creature/type/alchemical
  - pf2e/creature/type/mindless
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Alchemist Ivy"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #193: Mantle of Gold"
name: "Alchemist Ivy"
level: "Creature 3"
rare_03: [[Uncommon]]
alignment: ""
size: "Large"
trait_01: [[alchemical]]
trait_02: [[mindless]]
trait_03: [[plant]]
modifier: 10
perception:
  - name: "Perception"
    desc: "+10; Tremorsense (Imprecise) 30 Feet, Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +9, Stealth: +9"
abilityMods: [4, 0, 3, -5, 3, 0]
speed: 5 feet
sourcebook: "_Pathfinder #193: Mantle of Gold_"
ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__ +10, __Ref__ +7, __Will__ +8"
hp: 68
health:
  - name: ""
  - name: HP
    desc: "68; __Immunities__  mental; __Weaknesses__ fire 5, slashing 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Camouflage"
    desc: "  The assassin vine can [[Actions/Hide|Hide]] in natural environments even if it doesn't have cover."

abilities_mid:
  - name: ""
  - name: "Alchemical Resistance"
    desc: "  An alchemist ivy takes 5 less damage from attacks with the alchemical trait."

  - name: "Chemical Fertilizer"
    desc: "`pf2:0` (alchemical,healing) **Trigger** A creature within 10 feet of the alchemist ivy Activates or is hit by an item with the alchemical trait\n* * *\n\n**Effect** The alchemist ivy briefly extends tendrils toward the creature and absorbs some of the alchemical residue, regaining 2d8 healing Hit Points and gaining a +15-foot status bonus to its Speed until the end of its next turn.\n\n[[Bestiary Effects/Effect_ Chemical Fertilizer|Effect: Chemical Fertilizer]]"

  - name: "Grasping Foliage"
    desc: "`pf2:r` (primal) **Trigger** The assassin vine detects a creature within 20 feet via [[Bestiary Ability Glossary/Tremorsense|Tremorsense]]\n* * *\n\n**Effect** The assassin vine causes vegetation within a 20-foot emanation to writhe for 1 round, turning this area into difficult terrain. When a creature starts its turn in this area, it must attempt a DC 20 Reflex check save. On a failure, it takes a -10-foot circumstance penalty to its Speeds until it leaves the area, and on a critical failure it is also [[Conditions/Immobilized|Immobilized]] for 1 round. A creature can attempt to [[Actions/Escape|Escape]] to remove these effects.\n\nAssassin vines are immune to Grasping Foliage."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vine"
    desc: "+12 (reach 10 feet)\n__Damage__  1d8 + 6 bludgeoning plus grab"

  - name: "**Ranged** `pf2:1` Sap"
    desc: "+12 (range increment 20 feet)\n__Damage__  2d6 cold"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+4 bludgeoning, DC 20 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Alchemist Ivy
creatures:
  - 1: Alchemist Ivy
```


Variant Assassin Vine

The assassin vine is a carnivorous plant with a voracious appetite. Rather than consuming creatures directly, it creates its own fertilizer by entangling prey and squeezing the life from it. Once the plant has killed a creature, it pulls the carcass over to its roots to feed from the decaying flesh. Although an assassin vine lacks eyes, it can detect and track prey through a combination of using its root systems to detect vibrations through topsoil and its leaves to detect heat changes in the vicinity. Although the assassin vine has no real intelligence, its learned behaviors mimic those of cunning ambush hunters.

As it is slow moving, the assassin vine typically remains rooted in a single area for as long as it has sufficient prey. Though most often found along woodland trails or swamps, these plants can also be encountered in more rural settlements, poorly tended fields, and vineyards. While assassin vines can't be trained in the classical sense, they can be used as defenses, and woodland-dwelling creatures like goblins and fey have been known to cultivate assassin vines as guardians for less-used routes into their lairs. In such cases, the tenders often seek to make the path more obvious than its disuse would otherwise suggest, while simultaneously working to ensure the bones of the vines' victims are removed to keep their presence a secret, resulting in what appears to be an easy approach to the den but is actually an organic ambush.

Mature assassin vines grow to 20 feet long and have smaller vines extending off the main trunk that reach from to 5 to 10 feet in length. The smallest of these vines sprout every 6 inches or so; they tend to grow clusters of full leaves and occasionally bear small berries. A recently fed assassin vine can have bunches of plump, blood-red berries that are juicy and tart but leave a slightly unpleasant iron aftertaste, as if from the faint taste of blood from a bitten lip.
