---
title: "Llorona"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.7TqFBGrYyMGioRYE" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/12
statblock: inline
name: "Llorona"
level: 12
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Llorona"
level: "Creature 12"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[incorporeal]]
trait_03: [[spirit]]
trait_04: [[undead]]
trait_05: [[unholy]]
modifier: 20
perception:
  - name: "Perception"
    desc: "+20; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Athletics: +23, Deception: +25, Intimidation: +23, Stealth: +23"
abilityMods: [-5, 7, 1, 2, 2, 5]
speed:  fly 60 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 32
armorclass:
  - name: AC
    desc: "32; __Fort__ +19, __Ref__ +23, __Will__ +20"
hp: 165
health:
  - name: ""
  - name: HP
    desc: "165, void healing, rejuvenation; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  unconscious; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Rejuvenation"
    desc: " (divine) When a llorona is destroyed, they re-form after 1d6 days at the site of their death. Resolving the injustice that led to a llorona's death puts them to rest permanently. Alternatively, successfully performing a [[Spells/Consecrate|Consecrate]] ritual at the site prevents them from re-forming."

  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+25 (agile, finesse, magical)\n__Damage__  2d6 + 11 void plus funereal-touch,grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+12 void DC 31 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Funereal Touch"
    desc: "  A creature touched by a llorona must attempt a DC 29 Fortitude check save. On a failure, the creature becomes [[Conditions/Drained|Drained 1]] (drained 2 on a critical failure) or increases their drained value by 1 (2 on a critical failure), up to a maximum of drained 4. Every time a creature becomes drained in this way, the llorona gains 10 temporary Hit Points for 1 hour."

  - name: "Ghostly Grasp"
    desc: "  A llorona can [[Actions/Grapple|Grapple]] corporeal creatures despite being incorporeal. The llorona uses their Athletics check to Grapple as normal but can't use Athletics for other actions that require corporeal contact, like Force Open or Trip."

  - name: "Wail"
    desc: "`pf2:2` (auditory,concentrate,incapacitation,mental,occult) The llorona unleashes a somber wail. Each living creature within 120 feet must attempt a DC 31 Will check save. Regardless of its result, the creature is then temporarily immune for 24 hours.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Stunned|Stunned 1]].\n\n**Failure** The creature is [[Conditions/Fascinated|Fascinated]] with the nearest body of water and compelled to move toward the water and drown itself. If there's no nearby body of water, the creature instead remains still. The creature can attempt another DC 31 Will check save at the end of each of its turns. On a success, the creature is no longer fascinated. Once the fascinated condition ends, the creature becomes stunned 1.\n\n**Critical Failure** As failure, except the creature receives another Will save only at the end of a round in which it's submerged in water."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Llorona
creatures:
  - 1: Llorona
```



Vengeful spirits called lloronas arise from people who died overcome with the grief and shame that comes with the tragic drowning of a child. In life, a llorona may have contributed to the child's death or simply lost the child to a horrible accident. In death, a llorona's pain manifests as a malevolent desire to drown others, imparting the same grief that they share with the person's loved ones. To this end, lloronas remain along riversides and other bodies of water in hopes of drawing their next victim and compelling them to drown themselves.

Lloronas look much like they did in life, except they wear elegant funeral attire in undeath. Though stories typically describe lloronas as women, reports from seasoned adventurers include accounts of lloronas appearing as different genders and with a variety of appearances.
