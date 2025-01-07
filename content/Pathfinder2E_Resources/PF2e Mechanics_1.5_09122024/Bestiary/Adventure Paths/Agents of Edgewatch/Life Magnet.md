---
title: Life Magnet
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #158: Sixty Feet Under
aliases: "Actor.Qp3uoh8lSHDINwfP" 
level: 7
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #158: Sixty Feet Under"
name: "Life Magnet"
level: "Hazard 7"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 17
sourcebook: "_Pathfinder #158: Sixty Feet Under_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +20, __Ref__ +18, "
hp: 50
health:
  - name: ""
  - name: "HP"
    desc: "50, &lt;strong&gt;Bar Hardness&lt;/strong&gt; 15, &lt;strong&gt;Bar HP&lt;/strong&gt; 40 (BT 20); __Hardness__ 14; __Immunities__  object immunities,  precision,  critical hits"
perception:
  - name: ""
  - name: "Stealth DC 17" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A magical magnet hidden behind a panel in the corner of the room pulls not metal but living creatures toward it, heedless of any obstacles in the way."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 29 Thievery check (expert) to deactivate the panel, or [[Spells/Dispel Magic|Dispel Magic]];(4th level; counteract DC 22) to counteract the panel's magic"
attacks:
  - name: ""

  - name: "Magnetize the Living"
    desc: "`pf2:r` **Trigger** A creature touches any of the iron bars in this area or touches a creature already affected by the trap\n* * *\n\n**Effect** The magical panel hidden in the far corner of the chamber (either the western or the eastern corner, depending on which side of the room the creature was closest to when it triggered the trap) \"magnetizes\" the triggering creature and violently pulls it toward the corner, automatically dealing 2d10+10 bludgeoning damage to the creature.\n\nThe trap then rolls initiative if it hasn't already done so."

  - name: "Routine"
    desc: "(1 action) The trap pulls up to four creatures that have already triggered its Magnetize the Living ability toward one of the far corners of the room, possibly pressing them into the iron bars. If all the iron bars between an affected creature and the magnetic panel remain intact, the creature takes 2d10+10 bludgeoning damage with a DC 25 basic Fortitude save and is restrained on a failure (Escape DC 23).\n\nIf an iron bar has been broken, the creature takes 1d10+5 bludgeoning damage instead, and if two consecutive bars have been broken the creature takes no damage (but might still be restrained on a failed save)."
  - name: "Reset"
    desc: "The trap deactivates and resets 1 minute after there are no creatures touching the iron bars."
```

```encounter-table
name: Life Magnet
creatures:
  - 1: Life Magnet
```

