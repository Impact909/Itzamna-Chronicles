---
title: "Gosreg"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Uhs2ZX3c0VYsBDnu" 
tags:
  - pf2e/creature/type/aberration
  - pf2eMonster
  - pf2e/creature/level/11
  - remaster
statblock: inline
name: "Gosreg"
level: 11
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Gosreg"
level: "Creature 11"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[aberration]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Darkvision, Thoughtsense (Precise) 60 Feet"
languages: "Aklo, Sakvroth; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Deception: +24, Diplomacy: +22, Occultism: +23, Society: +19, Stealth: +23"
abilityMods: [3, 6, 3, 6, 5, 7]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__ +18, __Ref__ +23, __Will__ +22; +1 status to all saves vs. magic"
hp: 195
health:
  - name: ""
  - name: HP
    desc: "195; __Immunities__  confused; __Resistances__ mental 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Borrow Languages"
    desc: "  The gosreg can read and speak all languages known by creatures within range of its telepathy."

  - name: "Thoughtsense 60 feet"
    desc: " (mental,occult) The gosreg senses a creature's mental essence as a precise sense with the listed range; it cannot sense mindless creatures with thoughtsense."

abilities_mid:
  - name: ""
  - name: "Unsettled Aura"
    desc: " (aura,mental,occult) 30 feet.\n\nGosregs project a field of discordant energy that unsettles the minds of thinking creatures. Any non-mindless creature within 30 feet of a gosreg takes a –1 status penalty to Will saves.\n\n[[Bestiary Effects/Effect_ Unsettled Aura|Effect: Unsettled Aura]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+21 (finesse)\n__Damage__  2d10 + 7 piercing 1d10 mental"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+21 (agile, finesse)\n__Damage__  2d8 + 7 slashing"

  - name: "Occult Innate Spells"
    desc: "DC 30, attack +22; __6th __  _[[Spells/Phantasmal Calamity|Phantasmal Calamity]]_, _[[Spells/Phantom Pain|Phantom Pain]]_; __5th __  _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Sending|Sending]]_, _[[Spells/Subconscious Suggestion|Subconscious Suggestion]]_, _[[Spells/Synaptic Pulse|Synaptic Pulse]]_; __4th __  _[[Spells/Nightmare|Nightmare]]_, _[[Spells/Suggestion|Suggestion (x3)]]_\n__Cantrips__  __(6th)__ _[[Spells/Telekinetic Hand|Telekinetic Hand]]_, _[[Spells/Telekinetic Projectile|Telekinetic Projectile]]_"

  - name: "Broadcast Stance"
    desc: "`pf2:1` (mental,occult,stance) **Requirements** the gosreg is in its natural form\n* * *\n\n**Effect** The gosreg secures its limbs into the ground as its brain-like head crackles with psychic energy. The gosreg's unsettled aura extends to 60 feet, and it blocks all other creatures' telepathy in the aura. Its Mind Bolt can also affect any number of targets in 60 feet. These effects end when the gosreg uses its claw Strike, leaves its space, or is knocked [[Conditions/Prone|Prone]]."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The gosreg takes on the appearance of any Small or Medium humanoid. This doesn't change its Speed or attack and damage modifiers with its claw, but it might change the damage type it deals (typically to bludgeoning). It cannot use its jaws Strike while in humanoid form.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Mind Bolt"
    desc: "`pf2:2` (mental,occult) A gosreg concentrates its field of discordant mental energy and projects it into the mind of one creature within 60 feet. The target takes 6d6 mental damage (DC 30 Will check save). On a critical failure, the creature is also [[Conditions/Confused|Confused]] for 1 minute or until it takes damage."
 
```

```encounter-table
name: Gosreg
creatures:
  - 1: Gosreg
```



Gosregs are agents of the Dominion of the Black who insinuate themselves into humanoid societies to implement the goals of their sinister masters. They're generally tasked with observing and waiting, hiding in disguised forms until their location is ripe for harvest. When this occurs, they reveal themselves as living psychic beacons, signaling their distant masters and guiding invasion forces. Over the years of an infiltration, a gosreg will assume dozens of roles, relishing any intense emotions it can inspire while laying the groundwork for future identities.

In their natural form, gosregs dart about in a jerky gallop due to stumpy legs, gangly arms, and oversized heads. They take on the appearances of humanoids to infiltrate societies, and they drop these disguises only when they're compromised and must resort to physical violence to continue their mission.

* * *

The Dominion of the Black is a conglomeration of deep-space conquerors with a strong presence on Aucturn, the most remote planet in Golarion's solar system. The Dominion has secret outposts all over Golarion; most of its members on the planet are scouts, using their skills to steal brains and identities, gathering information without any consideration for the inhabitants of the worlds they infiltrate.
