---
title: "Gambulami"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.krOOzggoKG352klW" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/11
statblock: inline
name: "Gambulami"
level: 11
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #172: Secrets of the Temple-City"
name: "Gambulami"
level: "Creature 11"
rare_03: [[Unique]]
alignment: ""
size: "Small"
trait_01: [[evil]]
trait_02: [[fey]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Low-Light Vision, Scent (Imprecise) 30 Feet"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +24, Crafting: +18, Deception: +20, Intimidation: +22, Nature: +21, Stealth: +22, Survival: +21"
abilityMods: [7, 5, 3, 1, 4, 3]
speed: 20 feet
sourcebook: "_Pathfinder #172: Secrets of the Temple-City_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +24, __Ref__ +20, __Will__ +21"
hp: 200
health:
  - name: ""
  - name: HP
    desc: "200"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Deflecting Branch|Deflecting Branch]], 3x [[Equipment/Spear|Spear]], [[Equipment/Leather Armor|Leather Armor]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Deflecting Branch"
    desc: "+24 (forceful, magical, sweep)\n__Damage__  3d10 + 13 bludgeoning"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+22 ()\n__Damage__  2d8 + 13 piercing plus grab"

  - name: "**Ranged** `pf2:1` Spear"
    desc: "+22 (thrown 20 ft.)\n__Damage__  1d6 + 13 piercing"

  - name: "Primal Innate Spells"
    desc: "DC 30, attack +22; __1st __ (1 slots) _[[Spells/Charm|Charm]]_"

  - name: "Inspired Feast"
    desc: " (emotion,mental) If a biloko feasts on a human corpse for 1 minute or more, they gain a +1 status bonus to attack rolls and a +2 status bonus to damage rolls for 1 hour."

  - name: "Size Alteration"
    desc: "`pf2:2` (polymorph,primal) Gambulami is affected by a 4th-rank [[Spells/Enlarge|Enlarge]] spell. This lasts for 1 minute, and Gambulami can Dismiss the Spell."

  - name: "Thrashing Chomp"
    desc: "`pf2:2`  **Requirements** Gambulami is larger than Small in size and has a creature [[Conditions/Grabbed|Grabbed]] with his jaws\n* * *\n\n**Effect** Gambulami whips the creature around, smashing it against other nearby creatures. He makes an Athletics check check against the grabbed creature's Fortitude DC. Regardless of the result, the creature is released from Gambulami's jaws afterward, escaping into the space in which it was grabbed.\n* * *\n\n**Critical Success** Gambulami uses a mighty spin to smash the held creature against every creature within his reach. Every creature, including the grabbed creature, takes 1d10+7 bludgeoning damage.\n\n**Success** As critical success, but creatures take 1d10 bludgeoning damage.\n\n**Failure** The creature breaks free.\n\n**Critical Failure** The creature breaks free and Gambulami's spin causes him to fall [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Gambulami
creatures:
  - 1: Gambulami
```




