---
title: "Obcisidaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.G1u90QDl0UPE0r9K" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Obcisidaemon"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #192: Worst of All Possible Worlds"
name: "Obcisidaemon"
level: "Creature 19"
rare_03: [[Uncommon]]
alignment: ""
size: "grg"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 35
perception:
  - name: "Perception"
    desc: "+35; Darkvision, Truesight"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Athletics: +39, Deception: +34, Intimidation: +36, Religion: +32, Warfare Lore: +36"
abilityMods: [10, 4, 8, 4, 5, 7]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder #192: Worst of All Possible Worlds_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +35, __Ref__ +29, __Will__ +32; +1 status to all saves vs. magic"
hp: 425
health:
  - name: ""
  - name: HP
    desc: "425; __Immunities__  death effects; __Weaknesses__ holy 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Halberd|+3 Major Striking Halberd]]"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Cloak of Souls"
    desc: "  An obcisidaemon is shrouded at all times in a cloak of captured souls. It can hold a number of souls equal to the daemon's Charisma modifier. Destroying the daemon frees the souls, though this doesn't return the deceased creatures to life. A creature whose soul is trapped within this cloak can't be resurrected except by a 9th-rank [[Spells/Resurrect|Resurrect]] ritual or similarly powerful magic."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Scorched Earth"
    desc: " (aura,divine) 60 feet. Any creature who dies within the aura and isn't drawn into the obcisidaemon's Cloak of Souls via Inherit Soul must attempt a DC 38 Fortitude check save. On a failure, the creature's body (but not its gear) is immediately reduced to a fine smear of ashes."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Halberd"
    desc: "+36 (magical, reach 25 feet, unholy, versatile s)\n__Damage__  1d6 spirit 4d10 + 18 piercing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+36 (magical, reach 15 feet, unholy)\n__Damage__  1d6 spirit plus grab 4d6 + 18 piercing plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 38, attack +30; __10th __  _[[Spells/Massacre|Massacre]]_; __9th __  _[[Spells/Disintegrate|Disintegrate]]_, _[[Spells/Falling Stars|Meteor Swarm]]_; __7th __  _[[Spells/Paralyze|Paralyze]]_, _[[Spells/Spell Turning|Spell Turning]]_; __5th __  _[[Spells/Toxic Cloud|Cloudkill]]_, _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At Will, Good Only)]]_\n__Constant__  __(10th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Consume Soul"
    desc: "`pf2:2` (divine) The obcisidaemon consumes a soul from its cloak to gain one of the following effects. A consumed soul in this way can't be resurrected except by [[Spells/Wish|Wish]] or a similarly powerful effect.\n\n[[Bestiary Effects/Effect_ Consume Soul|Effect: Consume Soul]]\n\n_Empower Spell_ The obcisidaemon gains a +2 status bonus to its spell DCs and spell attack rolls until the end of its next turn.\n\n_Empower Weapon_ The obcisidaemon's weapon gains the effects of a greater flaming, greater frost, greater shock, or wounding rune until the end of its next turn.\n\n_Healing_ The daemon gains the benefit of a two-action, 8th-rank [[Spells/Heal|Heal]] spell (8d8+64)."

  - name: "Inherit Soul"
    desc: "`pf2:r` (divine,incapacitation) **Trigger** The obcisidaemon slays a creature\n* * *\n\n**Effect** The obcisidaemon attempts to draw the creature's soul into its cloak of souls. The triggering creature must attempt a DC 38 Fortitude check save. On a failure, its soul is consumed and added to the cloak of souls. If the obcisidaemon's cloak can't hold any more souls, the daemon can release one of the souls as a free action; otherwise, the soul isn't absorbed."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Obcisidaemon
creatures:
  - 1: Obcisidaemon
```



Obcisidaemons (known to some as obliteration daemons) care only for the brutality and violence that conflict brings.

## Soul Hoarding

Obcisidaemons carry some souls for months or even years at a time, choosing never to consume them, even when doing so might grant an advantage in combat.
