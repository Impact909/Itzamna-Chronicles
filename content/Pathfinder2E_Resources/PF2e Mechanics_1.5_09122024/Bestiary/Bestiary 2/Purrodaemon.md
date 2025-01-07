---
title: "Purrodaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.sd1xIczLcXWyjPLn" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Purrodaemon"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Purrodaemon"
level: "Creature 18"

alignment: ""
size: "Large"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Truesight"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +37, Intimidation: +35, Religion: +30, Stealth: +34, Survival: +33, Warfare Lore: +32"
abilityMods: [9, 6, 7, 4, 7, 7]
speed: 25 feet,  fly 50 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +33, __Ref__ +30, __Will__ +29; +1 status to all saves vs. magic"
hp: 335
health:
  - name: ""
  - name: HP
    desc: "335; __Immunities__  bleed,  death effects; __Weaknesses__ holy 15; __Resistances__ piercing 15"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Glaive|+2 Greater Striking Glaive]], 2x Soul Gem, Steeped Weapon (7-10)"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Glaive"
    desc: "+37 (deadly d8, forceful, magical, reach 15 feet, unholy)\n__Damage__  3d8 + 17 slashing 2d6 spirit 4d6 bleed"

  - name: "**Ranged** `pf2:1` Hurled Weapon"
    desc: "+35 (deadly d10, magical, propulsive, range increment 120 feet, unholy)\n__Damage__  2d10 + 12 piercing 1d6 spirit 4d6 bleed"

  - name: "Divine Innate Spells"
    desc: "DC 37, attack +27; __9th __  _[[Spells/Seize Soul|Bind Soul]]_, _[[Spells/Blade Barrier|Blade Barrier]]_, _[[Spells/Chain Lightning|Chain Lightning]]_; __7th __  _[[Spells/Flame Strike|Flame Strike]]_, _[[Spells/Teleport|Teleport]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At will) (Good only)]]_\n__Constant__  __(6th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Hurl Weapon"
    desc: "`pf2:1` (divine) The purrodaemon causes a weapon that has steeped in their flesh (see Steep Weapon) to telekinetically launch from their flesh. The purrodaemon makes a hurled weapon Strike without using their hands."

  - name: "Recall Weapon"
    desc: "`pf2:1`  **Requirements** A steeped weapon that's no longer sheathed in the purrodaemon's body is within 120 feet of the daemon\n* * *\n\n**Effect** The steeped weapon swiftly flies through the air to resheath itself in the purrodaemon's body. If a creature is along this flight path, the purrodaemon can make a hurled weapon Strike against the target; if it hits, the weapon drops to the ground in a square adjacent to the creature."

  - name: "Steep Weapon"
    desc: "`pf2:1` (manipulate) The purrodaemon sheathes a weapon in their own flesh. This deals no damage to the purrodaemon, which can have up to 10 weapons sheathed in their body at a time. A steeped weapon must be one that deals piercing or slashing damage.\n\nIf a purrodaemon [[Actions/Interact|Interacts]] to crush a soul gem, one weapon of their choice sheathed in their flesh becomes enchanted with the daemon's fiendish power and becomes a +2 greater striking weapon that can be used in place of their glaive or hurled at targets (with a +2 item bonus to the hurled weapon's attack modifier and an extra d10 of damage). This magical quality fades 24 hours after it ceases being sheathed in the daemon's living body. A steeped weapon can be [[Actions/Disarm|Disarmed]]."

  - name: "Twist the Blade"
    desc: "`pf2:r`  **Requirements** The purrodaemon has fewer than 10 weapons sheathed in their body\n\n**Trigger** The purrodaemon is hit with a weapon that deals piercing damage\n* * *\n\n**Effect** The purrodaemon seizes the triggering weapon. The weapon's wielder must attempt a DC 40 Reflex check save. On a failure, the weapon is disarmed and falls to an adjacent square. On a critical failure, the weapon is sheathed in the purrodaemon's body as though the daemon had used Steep Weapon."
 
```

```encounter-table
name: Purrodaemon
creatures:
  - 1: Purrodaemon
```



Few creatures embody war's sheer amount of bloodshed and loss of life as deeply as the purrodaemons, deacons of war. These giant humanoid daemons are bedecked in black, unholy armor, with weapons piercing their flesh at every opening. Far from wounds, however, these weapons are the purrodaemon's arsenal. A purrodaemon can, with frightening swiftness and nauseating ease, extract a weapon from its own flesh as though drawing a sword from a sheath, and their blood is so tainted with evil that weapons steeped in it become powerful tools of war.
