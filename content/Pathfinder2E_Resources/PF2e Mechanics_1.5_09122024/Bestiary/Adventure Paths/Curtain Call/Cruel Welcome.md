---
title: Cruel Welcome
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
  - remaster
source: Pathfinder #204: Stage Fright
aliases: "Actor.Fj52Kll6MTCFgMYw" 
level: 8
license: ORC
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #204: Stage Fright"
name: "Cruel Welcome"
level: "Hazard 8"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 21
sourcebook: "_Pathfinder #204: Stage Fright_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +19, __Ref__ +13, "
hp: 66
health:
  - name: ""
  - name: "HP"
    desc: "66; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 21" 
    desc: "(trained)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A loved one, tied to a post with thick ropes, suddenly lurches to life and begins to shriek in anguish as soon as one of the PCs comes within 20 feet."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 31 Thievery check (expert) to remove the small runes carved on the pole that focus the magic, or DC 28 Occultism check (trained) to recognize the occult illusions woven into the trap and disable the underlying magic"
attacks:
  - name: ""

  - name: "Become Cruel"
    desc: "`pf2:r` (emotion, fear, mental, occult) **Trigger** A PC approaches within 20 feet of the trap\n* * *\n\n**Effect** The rag-wrapped figure cries out in pain. The triggering PC must attempt a DC 26 Will check save or become [[Conditions/Frightened|Frightened 1]] ([[Conditions/Frightened|Frightened 2]] on a critical failure). The trap then rolls initiative."

  - name: "Routine"
    desc: "(1 action; illusion, mental, occult, visual) The cruel welcome's head lifts, and it gazes at the closest PC within 20 feet; if there are no PCs in range, the trap does nothing, its turn ends, and it deactivates until midnight. The target must attempt a DC 26 Will check save.\n* * *\n\n**Critical Success** The PC is unaffected. For the next 24 hours, the PC gains a +4 circumstance bonus to all saving throws against cruel welcome traps.\n\n**Success** The PC recognizes the face of the tormented figure on the pole as that of a loved one, and the anguish of the sight results in 4d10 mental damage. For the next 24 hours, the PC gains a +4 circumstance bonus to all saving throws against cruel welcome traps.\n\n**Failure** As success, but 4d10+22 mental damage.\n\n**Critical Failure** As failure, but 8d10+44 mental damage, and the PC becomes [[Conditions/Stupefied|Stupefied 1]] for 24 hours."
  - name: "Reset"
    desc: "A cruel welcome trap resets at midnight."
```

```encounter-table
name: Cruel Welcome
creatures:
  - 1: Cruel Welcome
```

