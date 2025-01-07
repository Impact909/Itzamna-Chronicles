---
title: "Mudwretch"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.l1uRgKGSMy88zUmH" 
tags:
  - pf2e/creature/type/earth
  - pf2e/creature/type/elemental
  - pf2e/creature/type/water
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Mudwretch"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Mudwretch"
level: "Creature 2"

alignment: ""
size: "Medium"
trait_01: [[earth]]
trait_02: [[elemental]]
trait_03: [[water]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; Darkvision"
languages: "Petran"
skills:
  - name: "Skills"
    desc: "Athletics: +8, Stealth: +6"
abilityMods: [4, 0, 3, -2, 3, 0]
speed: 20 feet,  swim 20 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +11, __Ref__ +4, __Will__ +9"
hp: 40
health:
  - name: ""
  - name: HP
    desc: "40; __Immunities__  bleed,  critical hits,  paralyzed,  poison,  sleep; __Weaknesses__ fire 5; __Resistances__ acid 3, physical 3 (except bludgeoning)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "Muddy Field"
    desc: " (aura) 10 feet. The ground in the area is difficult terrain for all non-mudwretch creatures."

  - name: "Susceptible to Desiccation"
    desc: "  If a mudwretch takes any damage from [[Spells/Desiccate|Desiccate]] or a similar effect, takes 10 or more fire damage from a single effect, or spends more than 24 hours outside of a source of sufficient hydration (such as a swamp, river, well, or recent rainfall), it becomes dehydrated.\n\nWhile dehydrated, the mudwretch can't Spew Mud, is [[Conditions/Sickened|Sickened 2]], and is [[Conditions/Slowed|Slowed 1]] until it either fully immerses in water, spends 1 minute in the rain, or rehydrates in another way (such as via Gory Hydration)."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+10 (agile)\n__Damage__  1d8 + 4 bludgeoning plus grab"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+2 bludgeoning damage, DC 18 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Gory Hydration"
    desc: "`pf2:r`  **Requirements** The mudwretch is dehydrated\n\n**Trigger** The mudwretch deals Constrict damage to a living creature that has blood\n* * *\n\n**Effect** The mudwretch squeezes harder, dealing 1d6 bleed to the target. The mudwretch absorbs this blood, removing any penalties it had as a result of being dehydrated."

  - name: "Mud Puddle"
    desc: "`pf2:1` (concentrate) Until it next acts, the mudwretch appears to be an ordinary puddle of mud. It has an automatic result of 20 on Deception checks to pass as a mud puddle and can make a fist Strike against a creature that walks onto the mud puddle as a reaction."

  - name: "Spew Mud"
    desc: "`pf2:2` (primal) The mudwretch spews a 20-foot line of pressurized mud that deals 2d10 bludgeoning damage (DC 18 Reflex check save). On a critical failure, a creature also takes a -10-foot status penalty to its Speeds for 1 round.\n\nThe mudwretch can't Spew Mud again for 1d4 rounds."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Mudwretch
creatures:
  - 1: Mudwretch
```



In its resting form, a mudwretch looks like a large puddle of thick, dark mud, heaped at the center in a slightly drier patch of loam. When a living creature approaches, though, the mudwretch lurches upward, piling its muddy flesh upon itself to form a roughly humanoid shape, often in vague mockery of the approaching creature's general form in cases where the creature is a humanoid itself.

Mudwretches possess a low level of intellect, and while they do not form societies or cultures of their own, they are attracted to ruins or abandoned settlements. They have little need to eat, but without a constant source of moisture, a mudwretch dries out, suffering from low throbbing aches until it can resaturate. Often, blood from living creatures has to do-a dried mudwretch is more dangerous to intruders than one that's comfortably wallowing on a river bank.
