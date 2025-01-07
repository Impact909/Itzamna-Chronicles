---
title: Tylegmut's Last Meal
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #181: Zombie Feast
aliases: "Actor.GHf5GCGRWabFhTMT" 
level: 4
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #181: Zombie Feast"
name: "Tylegmut's Last Meal"
level: "Hazard 4"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 12
sourcebook: "_Pathfinder #181: Zombie Feast_"
ac: 10
armorclass:
  - name: AC
    desc: "10; "
hp: 10
health:
  - name: ""
  - name: "HP"
    desc: "10; __Immunities__  object immunities"
perception:
  - name: ""
  - name: "Stealth DC 12" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The former bank manager's ghostly presence tempts creatures to partake in a dubious meal."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 18 Religion check (trained) to say a prayer to Urgathoa and put the haunt temporarily to rest until it resets, DC 22 Occultism check (trained) to commune with the bank manager's spirit and convince her to permanently pass on, disabling the haunt"
attacks:
  - name: ""

  - name: "Foul Temptation"
    desc: "`pf2:r` (occult) **Trigger** A creature looks over the contents of the desk\n* * *\n\n**Effect** The haunt tempts nearby creatures to eat from the plates and bowls arrayed on the desk by concealing it in an illusion of food the viewer finds delicious. Each creature in area **D5** must attempt a DC 21 Will check save. The haunt then rolls initiative.\n* * *\n\n**Critical Success** The creature sees through the illusion entirely and is temporarily immune to the haunt's routine for 1 minute.\n\n**Success** The creature is not tempted by the food.\n\n**Failure** The creature believes the food is appetizing and becomes driven to consume it. The creature takes 4d4+4 slashing damage as it chews the jagged bones and husks.\n\n**Critical Failure** As failure, but the creature takes double damage and is [[Conditions/Paralyzed|Paralyzed]] for 1 round as the haunt continues to tempt it."

  - name: "Routine"
    desc: "(1 action) The haunt sends a cloud of dust and bone shards hurtling about the room. The dust and bones batter all creatures in the room, dealing 4d6 bludgeoning damage (DC 21 Reflex check). Creatures who fail the save are [[Conditions/Blinded|Blinded]] for 1 round (or 1 minute on a critical failure)."
  - name: "Reset"
    desc: "The haunt re-forms after 1 hour. The haunt becomes disabled and doesn't re-form if a creature eats a full meal at the desk-this can be any food, not just the \"food\" at hand."
```

```encounter-table
name: Tylegmut's Last Meal
creatures:
  - 1: Tylegmut's Last Meal
```

