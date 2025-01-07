---
title: "Astradaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.JDdAyl9fLdsXFdtA" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/16
  - remaster
statblock: inline
name: "Astradaemon"
level: 16
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Astradaemon"
level: "Creature 16"

alignment: ""
size: "Large"
trait_01: [[daemon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 28
perception:
  - name: "Perception"
    desc: "+28; Darkvision, Lifesense 30 Feet, Truesight"
languages: "Common, Daemonic; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +28, Athletics: +32, Intimidation: +33, Religion: +26, Stealth: +28, Survival: +26"
abilityMods: [8, 6, 7, 2, 4, 7]
speed: 60 feet,  fly 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 39
armorclass:
  - name: AC
    desc: "39; __Fort__ +27, __Ref__ +30, __Will__ +26; +1 status to all saves vs. magic"
hp: 240
health:
  - name: ""
  - name: HP
    desc: "240; __Immunities__  death effects,  void; __Weaknesses__ holy 15"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Lifesense|Lifesense 30 feet]]"
    desc: "  Lifesense allows a monster to sense the vital essence of living and undead creatures within the listed range. The sense can distinguish between the vitality energy animating living creatures and the void energy animating undead creatures, much as sight distinguishes colors."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Bent Light"
    desc: " (divine,illusion,visual) An astradaemon appears shifted from their true position, though still in the same space. Creatures targeting the astradaemon must succeed at a DC 11 Flat check to do so, as if the astradaemon were [[Conditions/Hidden|Hidden]], even though the astradaemon remains observed.\n\nAbilities that apply to the flat check against hidden creatures also apply against bent light."

  - name: "Soul Siphon"
    desc: " (aura,divine,force) 30 feet.\n\nAn astradaemon draws power from the souls of the recently slain. If a Small or larger living creature dies within their aura, the astradaemon gains 5 temporary Hit Points and a +1 status bonus to attack and damage rolls for 1 round, unless the creature was slain by an astradaemon's Devour Soul ability.\n\nIncorporeal undead and living spirits that are traveling outside a body take 1d8 spirit damage each round within the daemon's aura as the astradaemon pulls in fragments of their soul.\n\n[[Bestiary Effects/Effect_ Soul Siphon|Effect: Soul Siphon]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+32 (magical, reach 10 feet, unholy)\n__Damage__  3d6 + 8 piercing plus essence-drain,grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+32 (agile, magical, reach 10 feet, unholy)\n__Damage__  2d6 + 8 slashing plus essence-drain"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+32 (magical, reach 15 feet, unholy)\n__Damage__  3d10 + 8 bludgeoning plus essence-drain"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +29; __8th __  _[[Spells/Execute|Execute]]_, _[[Spells/Pinpoint|Pinpoint]]_; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport (x2)]]_; __5th __  _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|Truesight]]_"

  - name: "Devour Soul"
    desc: "`pf2:1` (divine,incapacitation) **Requirements** The astradaemon hasn't used an action with the attack trait yet this turn\n* * *\n\n**Effect** The astradaemon draws out and consumes the soul of a living creature they have [[Conditions/Grabbed|Grabbed]].\n\nThe creature must succeed at a DC 35 Fortitude check save or instantly die. If it dies, the astradaemon gains 10 temporary Hit Points and a +2 status bonus to attack and damage rolls for 1 minute, or for 1 day if the victim was 15th level or higher.\n\nA victim slain in this way can be returned to life normally. A creature that survives is temporarily immune for 1 minute.\n\n[[Bestiary Effects/Effect_ Devour Soul|Effect: Devour Soul]]\n\n[[Bestiary Effects/Effect_ Devour Soul (Victim Level 15 or Higher)|Effect: Devour Soul (Victim Level 15 or Higher)]]"

  - name: "Essence Drain"
    desc: " (divine,void) When an astradaemon hits with their claw, jaws, or tail, they drain the target's spiritual and vital essences.\n\nThe target takes 2d10 void damage and the astradaemon regains an equal number of Hit Points. The target must succeed at a DC 37 Fortitude check save or become [[Conditions/Doomed|Doomed 1]] and [[Conditions/Drained|Drained 1]]. If the target was already drained or doomed, it instead increases both conditions' value by 1, to a maximum of 4."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Astradaemon
creatures:
  - 1: Astradaemon
```



These unnerving daemons represent death by direct assault against a soul or life-force. Rarely seen in the mortal Universe, astradaemons spend most of their time hunting the pathways between the living world and the afterlife. There, they capture migrating souls, snatching them from their rightful rewards or punishments and dragging them to Abaddon as tribute to their undying masters. These horrifying predators of the dead can also be found stalking the banks of the River of Souls in the Astral Plane, where they constantly hunt for new victims.

* * *

Denizens of the bleak and terrible plane of Abaddon, daemons are shaped by and devoted to the destruction of life in all its forms. They seek the death of every mortal being by the most painful and horrible means possible, in service to the Apocalypse Riders. Each kind of daemon represents a different way to die, and their powers are nearly always aimed at spreading that particular form of death. Through the use of these powers, they seek to drag all existence down into a pit of hopelessness and despair, and to commit all souls to oblivion.

While mortals who summon daemons usually seek to use the creatures' destructive and corrupting powers for their own ends, daemons always look for ways to spread fear, doubt, and despair wherever they go. Often, daemons disguise their plots as the workings of other fiends, knowing that such confusion compounds mortals' fear and keeps those mortals from bringing the most effective weapons. As a result, learned mortals sometimes refer to daemons as "riders" after their leaders or "soul mongers" after their largest industry.

While many fiends seek to tempt mortals into lives of nihilistic evil to increase their own numbers and power on their native planes, daemons are further driven by a supernatural hunger for mortal souls and use a variety of methods—not least of which is the cacodaemons' soul gems—to entrap them. On Abaddon and in other forbidding places across the multiverse, souls are simultaneously a delicacy, a trade good, and a source of magical power, and the daemons are among the greatest gluttons, merchants, and abusers of this spiritual "resource."
