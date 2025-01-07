---
title: "Wemmuth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.2BF6COyjRv3YiMzB" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/15
statblock: inline
name: "Wemmuth"
level: 15
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Wemmuth"
level: "Creature 15"

alignment: ""
size: "huge"
trait_01: [[evil]]
trait_02: [[plant]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision, Tremorsense (Imprecise) 60 Feet"
languages: "Aklo, Fey; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Athletics: +30, Deception: +28, Stealth: +30, Survival: +27"
abilityMods: [8, 6, 6, -2, 4, 2]
speed: 25 feet,  burrow 25 feet,  climb 25 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 37
armorclass:
  - name: AC
    desc: "37; __Fort__ +27, __Ref__ +27, __Will__ +24"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335, blood leech; __Weaknesses__ cold 20, slashing 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense (Imprecise) 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Pummel"
    desc: "+29 (fatal d12, reach 15 feet, sweep)\n__Damage__  4d12 + 10 bludgeoning plus improved-grab"

  - name: "**Ranged** `pf2:1` Boulder"
    desc: "+27 (fatal d12, range increment 60 feet)\n__Damage__  4d10 + 10 bludgeoning"

  - name: "Blood Leech"
    desc: "`pf2:r`  **Trigger** The wemmuth deals damage to a creature with Constrict.\n* * *\n\n**Effect** The wemmuth heals a number of Hit Points equal to half the total damage dealt by Constrict."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d12+10 bludgeoning damage, DC 37 Fortitude check save\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Engulf|Engulf]]"
    desc: "`pf2:2`  DC 37 Reflex check, 4d8 bludgeoning damage, Escape DC 35, Rupture 36\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of any creatures in its path. Any creature of the monster's size or smaller whose space the monster moves through can attempt a Reflex save with the listed DC to avoid being engulfed. A creature unable to act automatically critically fails this save. If a creature succeeds at its save, it can choose to be either pushed aside (out of the monster's path) or pushed in front of the monster to the end of the monster's movement. The monster can attempt to Engulf the same creature only once in a single use of Engulf. The monster can contain as many creatures as can fit in its space.\n\nA creature that fails its save is pulled into the monster's body. It is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The creature takes the listed amount of damage when first engulfed and at the end of each of its turns while it's engulfed. An engulfed creature can get free by [[Actions/Escape|Escaping]] against the listed escape DC. An engulfed creature can attack the monster engulfing it, but only with unarmed attacks or with weapons of light Bulk or less. The engulfing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the engulfed creature cuts itself free. A creature that gets free by either method can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, all creatures it has engulfed are automatically released as the monster's form loses cohesion."

  - name: "Thorny Mass"
    desc: "  Whenever a creature within 10 feet attempts a melee attack against a wemmuth or uses Acrobatics to [[Actions/Tumble Through|Tumble Through]] its space, that creature takes 1d12+10 piercing damage."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Wemmuth
creatures:
  - 1: Wemmuth
```



Fertilized by large quantities of spilled blood, such as that found on bloodstained battlefields or in the war-torn regions surrounding besieged cities, wemmuths are vile swaths of vines that draw sustenance from mortal suffering, lapping up blood like water. Possessing a rudimentary intelligence and an unquenchable thirst for blood, wemmuths lie in wait for most of their lives, growing to incredible size in the bloody soil of their grisly homes. Though the vines that comprise a wemmuth's body are scarcely thicker than rope, a single adult wemmuth system consists of 6 tons of vines, enough to stretch for 6,000 feet if stretched from end to end in a single straight line. Wemmuths never orient themselves this way, however, instead preferring to wrap themselves into massive mounds approximately 15 feet across and equally thick. Although wemmuths are often spotted lazing about, the scent of blood is enough to whip one into a violent frenzy. The creature condenses its entire mass into a sphere of sharp thorns and lashing vines, resembling a hateful tumbleweed the size of an elephant. Wemmuths commonly dig up massive boulders or entire trees from the ground and incorporate them into their rolling mass, using these objects to bolster their defense against many forms of attack or hurling them at faraway foes with terrifying precision.

Some speculate that wemmuths are a form of diabolical corruption let loose upon Golarion by House Thrune of Cheliax, perhaps as a scorched earth tactic against their rivals. Influential nobles from Nirmathas and Molthune both point fingers at one another for the wemmuth's creation, Nirmathas citing Molthune's close ties to Infernal Cheliax and Molthune blaming the primal magic commonly employed by Nirmathas's many druids and rangers. Several Varisian tales describe creatures closely matching the wemmuth's description attempting to apprehend a famous folk trickster, while crusaders from Mendev adhere to the belief that the wemmuths were a blight unleashed upon Golarion by Deskari, former demon lord of locusts, before his defeat at the hands of mortal heroes.
