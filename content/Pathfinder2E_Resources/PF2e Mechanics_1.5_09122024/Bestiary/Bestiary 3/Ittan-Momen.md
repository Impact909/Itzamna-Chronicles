---
title: "Ittan-Momen"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.MbJ9f8ggShGMicWG" 
tags:
  - pf2e/creature/type/kami
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Ittan-Momen"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Ittan-Momen"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[kami]]
modifier: 7
perception:
  - name: "Perception"
    desc: "+7; Darkvision, Tremorsense (Imprecise) 30 Feet"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +8, Deception: +6, Stealth: +8"
abilityMods: [2, 4, 2, 0, 1, 0]
speed:  fly 30 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +8, __Ref__ +10, __Will__ +5"
hp: 20
health:
  - name: ""
  - name: HP
    desc: "20; __Immunities__  bleed,  death effects,  disease,  doomed,  drained,  fatigued,  healing,  paralyzed,  poison,  unconscious; __Weaknesses__ slashing 5; __Resistances__ bludgeoning 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 30 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "Mundane Appearance"
    desc: "  When not moving, such as during the day, the ittan-momen is nearly indistinguishable from normal cloth. They have an automatic result of 26 on Deception checks and DCs to pass as normal cloth."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Body"
    desc: "+10 (finesse)\n__Damage__  1d8 + 2 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8 bludgeoning, DC 18 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 18 Reflex check, 1d8+2 bludgeoning damage, Escape DC 18, Rupture 5\n\nThe ittan-momen can Engulf only one creature. They can Engulf a creature of a larger size so long as the creature's head can feasibly be covered by the ittan-momen's body.\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Ittan-Momen
creatures:
  - 1: Ittan-Momen
```



Born from large pieces of cloth, ittan-momen flutter in the air, catching the last rays of the setting sun. Ittan-momen can awaken from any sufficiently large cloth, and many beautiful but cruelly-treated tapestries have lured unsuspecting victims to an untimely end.

* * *

Tsukumogami are intelligent, mobile objects formed from the union between a 100-year-old object and a kami. Tsukumogami range from harmless to malicious, each individual personality a result of how the object was treated before its awakening. Well-cared-for objects tend to birth helpful, friendly tsukumogami, while mistreated or abandoned objects twist into malevolent and violent beings. Most tsukumogami are, by nature, mischievous, and oftentimes want nothing more than to occupy the attention of living creatures.

Tsukumogami can commonly be found in areas with a strong cultural belief in the value of caring for objects, which helps items survive long enough to become tsukumogami. Towns and villages with large tsukumogami populations are referred to as "sleepless towns" due to the nightly tsukumogami celebrations, which can become so raucous that they prevent the living residents from sleeping peacefully.
