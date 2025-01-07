---
title: "Grappling Spirit"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.89wwOpRrf3n6Dvwe" 
tags:
  - pf2e/creature/type/incorporeal
  - pf2e/creature/type/lawful
  - pf2e/creature/type/spirit
  - pf2e/creature/type/undead
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Grappling Spirit"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Book of the Dead"
name: "Grappling Spirit"
level: "Creature 9"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[incorporeal]]
trait_02: [[lawful]]
trait_03: [[spirit]]
trait_04: [[undead]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: "Common"
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +21, Diplomacy: +18, Intimidation: +20, Performance: +20, Gladiatorial Lore: +15"
abilityMods: [-5, 6, 4, 0, 2, 5]
speed:  fly 60 feet
sourcebook: "_Pathfinder Book of the Dead_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +19, __Will__ +15"
hp: 125
health:
  - name: ""
  - name: HP
    desc: "125, void healing; __Immunities__  death effects,  disease,  paralyzed,  poison,  precision,  sleep; __Resistances__ all damage 10 (except force, ghost touch, or vitality; double resistance vs. non-magical)"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Void Healing|Void Healing]]"
    desc: "  A creature with void healing draws health from void energy rather than vitality energy. It is damaged by vitality damage and is not healed by vitality healing effects. It does not take void damage, and it is healed by void effects that heal undead."

  - name: "Warrior's Mask"
    desc: "  A grappling spirit wears a mask that allows them to abandon their original form and become a warrior focused solely on combat. This mask is quasi-corporeal, allowing it to be manipulated by both corporeal and incorporeal creatures. A creature who has the grappling spirit [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] can remove the mask as an Interact action by succeeding at an DC 29 Athletics check check against the grappling spirit's Fortitude DC. Removing a grappling spirit's mask causes the spirit to fly into a frenzy. The grappling spirit becomes [[Conditions/Quickened|Quickened]] and can use their extra action to Fly, [[Actions/Grapple|Grapple]], or Strike. They also gain a +4 status bonus to damage rolls, and they take a -4 status penalty to AC and Reflex saving throws. If the mask is put back on, the grappling spirit ends their frenzy."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Ghostly Hand"
    desc: "+21 (agile, finesse, magical, nonlethal)\n__Damage__  2d10 + 12 void plus improved-grab"

  - name: "Ghostly Grasp"
    desc: "  A grappling spirit can [[Actions/Grapple|Grapple]] corporeal creatures despite being incorporeal. The grappling spirit uses their Athletics check to Grapple as normal but can't use Athletics for other actions that require corporeal contact, like [[Actions/Force Open|Force Open]] or [[Actions/Trip|Trip]]."

  - name: "Submission Lock"
    desc: "`pf2:2` (nonlethal) **Requirements** The grappling spirit has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The spirit saps their opponent's strength with a supernatural grip. The grappling spirit attempts an Athletics check to [[Actions/Grapple|Grapple]] a creature they have grabbed or restrained, also adding 4d10+12 void damage, depending on the result.\n* * *\n\n**Critical Success** The creature takes double damage. If it's already enfeebled, it falls [[Conditions/Unconscious|Unconscious]]. If not, it is [[Conditions/Enfeebled|Enfeebled 2]] until the end of its next turn and [[Conditions/Enfeebled|Enfeebled 1]] for 1 minute.\n\n**Success** The creature takes full damage and is enfeebled 1 until the end of its next turn."

  - name: "Teleporting Clothesline"
    desc: "`pf2:2` (occult,teleportation) **Requirements** The grappling spirit has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** The grappling spirit pushes the creature 15 feet in a straight line. The spirit immediately teleports 20 feet to intercept. They make a ghostly hand Strike against the creature. On a hit, the creature is knocked [[Conditions/Prone|Prone]], and on a critical hit, it also takes an additional 2d6 bludgeoning damage as it's driven to the ground."

  - name: "Victory Celebration"
    desc: "  If a spirit knocks a creature [[Conditions/Unconscious|Unconscious]], each creature within 60 feet that witnesses the victory is targeted with a DC 26 Will check [[Spells/Roaring Applause|Roaring Applause]] spell. The spirit must spend all their actions until the end of the turn celebrating, and a new medal or belt appears on the spirit."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Grappling Spirit
creatures:
  - 1: Grappling Spirit
```



When a great gladiator or wrestler meets their demise, their soul can sometimes linger out of a love for combat and sport. Every grappling spirit manifests a mask that represents the legacy of the warrior they were during their life.
