---
title: "Olethrodaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.odFH1wbFoUDixQ55" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
statblock: inline
name: "Olethrodaemon"
level: 20
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Olethrodaemon"
level: "Creature 20"

alignment: ""
size: "grg"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 33
perception:
  - name: "Perception"
    desc: "+33; Darkvision, Tremorsense (Imprecise) 120 Feet, Truesight"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Athletics: +40, Intimidation: +38, Religion: +34"
abilityMods: [10, 6, 7, 2, 6, 8]
speed: 35 feet,  burrow 35 feet,  fly 40 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 44
armorclass:
  - name: AC
    desc: "44; __Fort__ +35, __Ref__ +32, __Will__ +34; +1 status to all saves vs. magic"
hp: 450
health:
  - name: ""
  - name: HP
    desc: "450; __Immunities__  death effects; __Weaknesses__ holy 20"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "4x Soul Gem"
  - name: "[[Bestiary Ability Glossary/Tremorsense|Tremorsense 120 feet]]"
    desc: "  Tremorsense allows a monster to feel the vibrations through a solid surface caused by movement. It is an imprecise sense with a limited range (listed in the ability). Tremorsense functions only if the monster is on the same surface as the subject, and only if the subject is moving along (or burrowing through) the surface."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Aura of Doom"
    desc: " (aura,death,divine) 60 feet. Any creature that begins its turn in the aura is [[Conditions/Doomed|Doomed 1]] for as long as it remains in the aura and for 1 hour thereafter."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+38 (magical, reach 10 feet, unholy)\n__Damage__  4d12 + 17 piercing plus grab 1d6 spirit plus grab"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+38 (agile, magical, reach 15 feet, unholy)\n__Damage__  4d8 + 17 slashing plus grab 1d6 spirit plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 42, attack +34; __10th __  _[[Spells/Cataclysm|Cataclysm]]_, _[[Spells/Massacre|Massacre]]_; __9th __  _[[Spells/Disintegrate|Disintegrate (x3)]]_, _[[Spells/Disjunction|Disjunction]]_, _[[Spells/Wails of the Damned|Wail of the Banshee]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_; __4th __  _[[Spells/Translocate|Dimension Door (At will)]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At will) (Good only)]]_\n__Constant__  __(10th)__ _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Control Weather_"

  - name: "Apocalypse Breath"
    desc: "`pf2:2` (divine,void) The daemon expels a shrieking black cloud of smoke from its mouth in a 120-foot line or a 60-foot cone (or both a line and a cone in the same direction if it spends 3 actions). Living creatures in the area take 24d6 void damage (DC 45 Reflex check save).\n\nThe olethrodaemon can't use Apocalypse Breath again for 1d4 rounds."

  - name: "Soul Crush"
    desc: "`pf2:2` (manipulate) **Requirements** The olethrodaemon has a soul gem\n* * *\n\n**Effect** The olethrodaemon crushes the soul gem in one hand and regains the use of Apocalypse Breath or any one of its innate spells."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Huge, 4d10 bludgeoning damage and [[Conditions/Drained|Drained 2]], Rupture 43\n\nAn olethrodaemon has numerous stomachs connected by labyrinthine digestive organs. Swallowed creatures cannot Escape, but can attempt to cut their way out with a 1d6 roll. On a roll of 1-3, the creature cuts into yet another stomach. On a roll of 4-6, the creature manages to cut its way out of the olethrodaemon.\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Olethrodaemon
creatures:
  - 1: Olethrodaemon
```



Even daemons fear the most massive and terrifying of their kind, olethrodaemons. No single entity could embody the level of evil necessary to manifest one; instead, these living war machines are made from the souls of many-or so the story goes. Other theories suggest that the four Horsemen of the Apocalypse are responsible for creating the olethrodaemons, or that olethrodaemons are merely the seeping run-off of an even greater being: a mysterious fifth Horseman.

Whatever the truth, olethrodaemons are real, and their existence is terrifying enough to instill paralyzing existential dread. With dozens of unblinking glowing eyes above a drooling maw, two sets of four muscled limbs, and countless horns, olethrodaemons resemble no other creature known to mortalkind.
