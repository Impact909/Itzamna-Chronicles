---
title: "Shredskin"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.ZNhUN6Pf9k8Q68qA" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/undead
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/2
statblock: inline
name: "Shredskin"
level: 2
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Shredskin"
level: "Creature 2"

alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[undead]]
trait_03: [[unholy]]
modifier: 6
perception:
  - name: "Perception"
    desc: "+6; Darkvision"
languages: "Common; (can&#x27;t speak any language)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +10, Athletics: +8, Deception: +8, Stealth: +8"
abilityMods: [2, 4, 0, -1, 0, 2]
speed:  fly 30 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__ +6, __Ref__ +10, __Will__ +8"
hp: 30
health:
  - name: ""
  - name: HP
    desc: "30, void healing; __Immunities__  critical hits (except slashing),  death effects,  disease,  paralyzed,  poison,  precision,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+10 (agile, finesse, reach 0 feet)\n__Damage__  1d6 + 4 slashing plus grab"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+11 (finesse, reach 0 feet)\n__Damage__  1d8 + 4 piercing"

  - name: "Compression"
    desc: "  When a shredskin successfully [[Actions/Squeeze|Squeezes]], it moves through the tight space at full speed. Narrow confines are not difficult terrain for a shredskin."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d6+2 bludgeoning, DC 16 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Control Body"
    desc: "`pf2:1`  **Requirements** The shredskin is in the same space as a Medium or Small humanoid-shaped corpse\n* * *\n\n**Effect** The shredskin wraps itself around the corpse as a new skin and takes control of the host body. While controlling a host, the shredskin uses the host's Speed but its own attacks, and it loses its Grab and Enshroud abilities. Attacks that target the shredskin while it controls a body deal half of the damage to the shredskin and half of the damage to the host body. Attacks that target an area deal damage to both the shredskin and host body normally. The shredskin can release the host body as a free action at the start of its turn. If the host is destroyed, the shredskin automatically releases the body and is [[Conditions/Off-Guard|Off-Guard]] for 1 round. A Medium corpse typically has 15 Hit Points, while a Small corpse typically has 10 Hit Points. Creatures can notice that a corpse is controlled by a shredskin by succeeding at a Perception check against the shredskin's Deception DC (typically 18)."

  - name: "Enshroud"
    desc: "`pf2:1` (attack,incapacitation) **Requirements** The shredskin is restraining a creature\n* * *\n\n**Effect** The shredskin wraps itself around the [[Conditions/Restrained|Restrained]] creature like a shirt, seizing control. The shredskin rolls an Athletics check check against the creature's Fortitude DC. On a success, the creature becomes restrained until it Escapes and the shredskin can control the creature as described in Control Body. At the start of each of its turns, the shredskin can attempt to Constrict the enshrouded creature as a free action. An enshrouded creature can attempt a DC 16 Escape check to break free (DC 18 if the shredskin critically succeeded its Athletics check to Enshroud)."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Shredskin
creatures:
  - 1: Shredskin
```



Shredskins are flying, flapping animate skins who wander the lands lamenting their fate and feeling hollow and adrift, as if they're missing something crucial inside them. They try to enshroud and seize humanoid bodies—either corpses or living creatures, anything to fill that void within themselves. Though many will take any body they can overpower, some know who created them and desire only that body to claim as their own, the truest fulfillment of their accursed nature. Shredskins come from people skinned as inhumane trophies, or who were killed in a gruesome way that left only their skin intact, such as being pulled into a machine and degloved.
