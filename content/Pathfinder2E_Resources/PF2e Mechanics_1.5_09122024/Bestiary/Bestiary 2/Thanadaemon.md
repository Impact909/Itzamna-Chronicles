---
title: "Thanadaemon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.a3WeFckfbaynzmz7" 
tags:
  - pf2e/creature/type/daemon
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Thanadaemon"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Thanadaemon"
level: "Creature 13"

alignment: ""
size: "Medium"
trait_01: [[daemon]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Darkvision, Truesight"
languages: "Common, Daemonic; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Arcana: +22, Deception: +26, Intimidation: +26, Religion: +22, Styx Lore: +24"
abilityMods: [6, 6, 4, 3, 5, 7]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +21, __Ref__ +23, __Will__ +26; +1 status to all saves vs. magic"
hp: 270
health:
  - name: ""
  - name: HP
    desc: "270; __Immunities__  death effects; __Weaknesses__ holy 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bo Staff|+1 Striking Bo Staff]], 2x Soul Gem"
  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Terrifying Gaze"
    desc: " (aura,divine,emotion,fear,mental,visual) 30 feet. When a creature ends its turn in the aura, it must attempt a DC 30 Will check save. If the creature fails, it becomes [[Conditions/Frightened|Frightened 2]]. The creature is then temporarily immune to terrifying gaze (but not Focus Gaze) for 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bo Staff"
    desc: "+28 (magical, parry, reach 10 feet, trip, unholy)\n__Damage__  3d8 + 14 bludgeoning plus draining-strike 1d6 void plus draining-strike 1d6 spirit plus draining-strike"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+27 (agile, finesse, magical, unholy)\n__Damage__  3d6 + 14 slashing plus draining-strike 1d6 spirit plus draining-strike"

  - name: "Divine Innate Spells"
    desc: "DC 34, attack +24; __7th __ (2 slots) _[[Spells/Execute|Finger of Death]]_, _[[Spells/Interplanar Teleport|Plane Shift (At Will; Self Plus Skiff and Passengers Only; Astral, Ethereal, and Evil Planes Only)]]_, _[[Spells/Teleport|Teleport]]_; __6th __ (3 slots) _[[Spells/Slow|Slow]]_, _[[Spells/Vampiric Exsanguination|Vampiric Exsanguination (x2)]]_; __5th __ (1 slots) _[[Spells/Translocate|Dimension Door]]_; __4th __ (1 slots) _[[Spells/Translocate|Dimension Door (At Will)]]_; __1st __ (1 slots) _[[Spells/Detect Alignment|Detect Alignment (Good Only) (At Will)]]_\n__Constant__  __(7th)__ _[[Spells/Air Walk|Air Walk]]_, _[[Spells/Truesight|True Seeing]]_"

  - name: "Rituals"
    desc: "_Create Undead_"

  - name: "Draining Strike"
    desc: " (divine) When a thanadaemon damages a living creature with a melee Strike, the creature must succeed at a DC 33 Fortitude check save or become [[Conditions/Drained|Drained 1]]. Further damage dealt by the thanadaemon increases the drained condition value by 1 on a failed save, to a maximum of [[Conditions/Drained|Drained 4]]."

  - name: "Focus Gaze"
    desc: "`pf2:1` (concentrate,divine,fear,visual) The thanadaemon glares at a single creature they can see within 30 feet. If the target wasn't already [[Conditions/Frightened|Frightened]], they must immediately attempt a DC 33 Will check save against the thanadaemon's terrifying gaze. If the target was already frightened, they must attempt a DC 33 Will check save or become [[Conditions/Fleeing|Fleeing]] for 1d4 rounds; this second effect has the incapacitation trait. After attempting its save, the creature is temporarily immune to this ability until the start of the thanadaemon's next turn."

  - name: "Soul Crush"
    desc: "`pf2:2` (manipulate) **Requirements** The thanadaemon has a soul gem\n* * *\n\n**Effect** The thanadaemon crushes the soul gem in one hand and gains fast healing 15 for 1 minute.\n\n[[Bestiary Effects/Effect_ Soul Crush (Healing)|Effect: Soul Crush (Healing)]]"
 
```

```encounter-table
name: Thanadaemon
creatures:
  - 1: Thanadaemon
```



Also known as the deacons of death, thanadaemons represent death via old age. They are among the most patient daemons, and prefer to bide their time to enact far-reaching, decades-long plans rather than fight (though they are still deadly foes). Like the Horseman of Death, they ply the waters of the River Styx in search of wayward souls. Rarely are thanadaemons seen without a trademark oar (which they wield as a bo staff), a tool they use to navigate the river's muck-ridden channels and turbulent rapids.

* * *

Daemons form from the most despicable souls and personify forms of death.
