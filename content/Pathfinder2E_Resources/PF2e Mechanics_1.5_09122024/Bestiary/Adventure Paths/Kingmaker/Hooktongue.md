---
title: "Hooktongue"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.92Y4DazNP1gBNslV" 
tags:
  - pf2e/creature/type/animal
  - pf2e/creature/type/aquatic
  - pf2eMonster
  - pf2e/creature/level/14
statblock: inline
name: "Hooktongue"
level: 14
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Hooktongue"
level: "Creature 14"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[animal]]
trait_02: [[aquatic]]
modifier: 25
perception:
  - name: "Perception"
    desc: "+25; Darkvision"
languages: "Thalassic; can&#x27;t speak any language"
skills:
  - name: "Skills"
    desc: "Athletics: +28, Stealth: +27"
abilityMods: [8, 5, 5, -3, 5, 0]
speed: 20 feet,  swim 50 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +27, __Ref__ +25, __Will__ +23"
hp: 275
health:
  - name: ""
  - name: HP
    desc: "275; __Resistances__ cold 15, fire 15"
abilities_top:
  - name: ""

  - name: "Slow Metabolism"
    desc: "  Hooktongue can go for 10 years without feeding. After this, its hunger makes it [[Conditions/Slowed|Slowed 1]] but doesn't otherwise impact its lifespan. If Hooktongue is slowed as a result of starvation, it can remove this condition by using Swallow Whole to gulp down a meal."

  - name: "Undetectable"
    desc: " (detection,primal,revelation,scrying) Hooktongue automatically tries to counteract any detection, revelation, or scrying divination attempted against it, using its Stealth modifier for the counteract check."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+30 (reach 15 feet)\n__Damage__  3d12 + 14 piercing plus grab"

  - name: "**Melee** `pf2:1` Tongue"
    desc: "+30 (agile, reach 25 feet)\n__Damage__  3d8 + 14 bludgeoning plus hooktongue-venom"

  - name: "Capsize"
    desc: "`pf2:1` (attack) Hooktongue attempts to capsize an aquatic vessel of its size or smaller that it's adjacent to. It must succeed at an Athletics check with a DC of 35 or the pilot's Sailing Lore DC, whichever is higher."

  - name: "Hooktongue Venom"
    desc: " (poison) **Saving Throw** DC 34 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 3d6 poison damage, clumsy 1, and [[Conditions/Confused|Confused]] (1 round)\n\n**Stage 3** 4d6 poison damage, [[Conditions/Clumsy|Clumsy 2]], and confused (1 round)"

  - name: "Poison Spray"
    desc: "`pf2:2` (poison,primal) Hooktongue sprays poison from its throat in an 80-foot line that deals 15d6 poison damage (DC 34 Reflex check). A creature that fails or critically fails this save is exposed to Hooktongue Venom as well. Hooktongue can't use Poison Spray again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Large, 2d10+10 bludgeoning damage, Rupture 28\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "Water Travel"
    desc: "`pf2:3` (primal,water) Hooktongue dissolves into water, appearing only as a long, serpentine silhouette on the waves. While in this form, Hooktongue's swim Speed increases to 600 feet, it automatically succeeds at Athletics checks to [[Actions/Swim|Swim]], and it gains a +4 circumstance bonus to Stealth checks in water. Hooktongue can remain in this form for 8 hours but can't enter salt water when using this ability. Hooktongue can return to its normal form using a single action, which has the concentrate trait."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Hooktongue
creatures:
  - 1: Hooktongue
```


Variant water orm

Legendary creatures lurking in remote lakes, water orms always find their way into the tavern tales of lakeside communities. To some travelers, every lake of respectable size seems to be surrounded by towns full of fishers claiming to have spotted a water orm. These elusive creatures inhabit lakes mainly in cool and gloomy regions. Some claim that water orms are an offshoot of sea serpents and linnorms, but no credible link between these creatures has been found.

Water orms have many features that sea serpents do not, such as the ability to understand the rudiments of language. Their natural inclination to avoid contact and remain hidden often remains at odds with their equally compelling curiosity about those they might spy upon the shores of their lakes. Water orm sightings usually occur when they can't help but to rise up to the surface to take a peek at someone particularly unusual on the beach or floating on the water's surface.

These creatures are extremely long-lived and can go for decades, or even centuries, with very little to eat. This allows water orms to subsist in lakes without surfacing for many years, even in bodies of fresh water without ample food sources. Water orms might lie in a silty lake bed for years, their elusiveness only contributing to their mythical reputation. When a pet or child goes missing near a lake, rumors might hold that the local water orm is responsible, leading to folk tales that caution residents against venturing out alone near the water.

While most water orms are described as serpentine or long-necked reptiles, others look similar to bizarrely elongated seals or whales, impossibly large sea horses, or long-necked creatures with paddles resembling those of elasmosauruses.
