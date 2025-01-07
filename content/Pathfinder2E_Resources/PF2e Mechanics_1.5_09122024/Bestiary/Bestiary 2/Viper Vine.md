---
title: "Viper Vine"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.W6zhiGCjQhDJEJNd" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Viper Vine"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Viper Vine"
level: "Creature 13"

alignment: ""
size: "Large"
trait_01: [[plant]]
modifier: 22
perception:
  - name: "Perception"
    desc: "+22; Low-Light Vision, Tremorsense (Imprecise) 60 Feet"
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +27, Stealth: +24"
abilityMods: [8, 5, 7, -4, 5, -3]
speed: 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 33
armorclass:
  - name: AC
    desc: "33; __Fort__ +26, __Ref__ +24, __Will__ +22"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Resistances__ poison 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 60 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

abilities_mid:
  - name: ""
  - name: "Cold Vulnerability"
    desc: " (cold) When exposed to a cold effect, the viper vine is overwhelmed by lethargy, becoming [[Conditions/Slowed|Slowed 1]] for 1d4 rounds."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+27 (reach 10 feet)\n__Damage__  3d6 + 11 piercing 3d6 poison"

  - name: "**Melee** `pf2:1` Vine"
    desc: "+27 (agile, reach 15 feet)\n__Damage__  3d10 + 11 bludgeoning plus grab"

  - name: "Captivating Pollen"
    desc: "`pf2:1` (incapacitation,mental,poison) The viper vine releases a 60-foot emanation of invisible pollen that stays in the air for 5 rounds unless dispersed by a moderate or stronger wind. Each creature that enters or starts its turn in the area must attempt a DC 33 Will check save or be captivated.\n\nThe viper vine can't use Captivating Pollen for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected and is temporarily immune to Captivating Pollen for 24 hours.\n\n**Success** The creature is [[Conditions/Sickened|Sickened 1]].\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]], and it must spend each of its actions to move closer to the viper vine as expediently as possible while avoiding obvious dangers. If a captivated creature is adjacent to the viper vine, it stays still and doesn't act. It ceases to be fascinated if it's no longer in the pollen aura at the end of its turn.\n\n**Critical Failure** As failure, plus the creature is [[Conditions/Stupefied|Stupefied 2]] for 24 hours."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  3d8+8 bludgeoning damage, DC 33 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Viper Vine
creatures:
  - 1: Viper Vine
```



A voracious, flesh-eating carnivore, the viper vine has a single enormous blossom arising from a thick, leafy tangle of snake-like vines. When the plant senses the approach of suitable prey through its sensitive, shallowly buried root system, it rises up like an agitated snake and unfurls its brightly colored bloom, an act that releases a cloud of mind-numbing pollen. Persistent stories claim the viper vine can lure prey into its clutches by swaying with a hypnotic motion, but this effect is in fact created by this invisible, odorless pollen cloud.

Since a viper vine gains nourishment by consuming creatures rather than through ingesting moisture and soil, it has developed rudimentary locomotion and can drag itself along the ground with its tentacle-like roots. It even has a form of rudimentary sentience, allowing it to not only discern differences in prey and make limited tactical decisions, but also to avoid creatures that are particularly large or dangerous-looking.

The area around viper vine hunting grounds is often strewn with the partially devoured remains of victims. It's not unusual to find the rotting corpses of wild animals, ill-fated adventurers, and even giants in the plant's immediate vicinity, along with a scattering of incidental treasure left behind on the corpses. A viper vine rarely returns to the carcass of a creature it killed earlier, preferring to hunt fresh meat.
