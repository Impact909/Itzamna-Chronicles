---
title: Mocking Puppets
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #204: Stage Fright
aliases: "Actor.kQ0SBTyJdPg3E6C8" 
level: 10
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Mocking Puppets"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 32
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +16, __Ref__ +24, __Will__ +22"
hp: 70
health:
  - name: ""
  - name: "HP"
    desc: "70; __Hardness__ 17; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 10"
perception:
  - name: ""
  - name: "Stealth DC 32" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The puppets and marionettes in this room suddenly turn to face intruders and come to clattering, unsettling life as the echoing sound of mocking laughter fills the air."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 32 Performance check (master) to distract and entertain the haunted puppets and make them forget their anguish and despair, or DC 35 Religion check (expert) to exorcise the haunt; four successes are required to disable it"
attacks:
  - name: ""

  - name: "Jeering Laughter"
    desc: "`pf2:r` (emotion, mental) **Trigger** A living creature spends more than a minute in this room, or one of the geists in this room uses Terrifying Laugh\n* * *\n\n**Effect** The puppets clatter to life, and the haunt fills the room with derisive laughter. All living creatures in the room must attempt a DC 29 Will check save or become [[Conditions/Slowed|Slowed 1]] for 1 round by the overwhelming self-doubt the laughter instills. The mocking puppets roll initiative."
  - name: "Melee"
    desc: "Makeshift Weapon +24 (versatile b, versatile p) no multiple attack penalty"

  - name: "Puppet Attack"
    desc: "`pf2:0` **Trigger** A living creature ends their turn while in area **C2**\n* * *\n\n**Effect** The haunt makes a makeshift weapon Strike against the triggering creature."

  - name: "Routine"
    desc: "(1 action) The room's puppets and marionettes clatter to life and begin to swarm about the room, throwing rubble at living intruders, stabbing them in the ankles with sharp bits of broken metal, and slashing at them with lashes from long, thin marionette cords. At the same time, other puppets cackle, mock, and pantomime a chosen foe. The haunt uses its action to target one living creature in area **C2**; that creature must attempt a DC 29 Will check save or become [[Conditions/Slowed|Slowed 1]] for 1 round by the mockery (or [[Conditions/Slowed|Slowed 2]] on a critical failure); this effect has the emotion and mental traits. At the same time, because the puppets constantly swarm about, they can use the Puppet Attack free action (see below) to attack targets during their turns."
  - name: "Reset"
    desc: "The haunt deactivates if no living creatures are in area **C2**, then resets 1 minute later."
```

```encounter-table
name: Mocking Puppets
creatures:
  - 1: Mocking Puppets
```

