---
title: Mask of Aroden's Guises
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #152: Legacy of the Lost God
aliases: "Actor.ZP13NYv5u1KYjQjJ" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #152: Legacy of the Lost God"
name: "Mask of Aroden's Guises"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 20
sourcebook: "_Pathfinder #152: Legacy of the Lost God_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +20, __Ref__ +16, "
hp: 48
health:
  - name: ""
  - name: "HP"
    desc: "48; __Hardness__ 18; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 20" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "Ten masks adorn twelve stone statues."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 29 Religion check (expert) or DC 29 Occultism check or DC 31 Thievery check (expert) to dismiss the magic on a single statue. Replacing the two missing masks (a mask made of or incorporating coins on the merchant statue and a mask made of any valuable fabric on the tailor statue) and succeeding at a DC 27 Religion check check disarms the trap."
attacks:
  - name: ""

  - name: "Unmasked Statues"
    desc: "`pf2:r` (occult) **Trigger** A creature removes the mask from a statue\n* * *\n\n**Effect** The trap casts [[Spells/Phantasmal Killer|Phantasmal Killer]] (DC 27) against the creature, creating an image of the statue lunging forth. The trap then rolls initiative."

  - name: "Routine"
    desc: "(3 actions) An unmasked statue casts [[Spells/Phantasmal Killer|Phantasmal Killer]] (DC 27 Will check and DC 27 Fortitude check) against a target in the room for each of the trap's actions, creating an image of the statue lunging forth. It doesn't affect the same creature more than once; if there are fewer targets than it has actions, the trap doesn't use its remaining actions. Unmasking an additional statue increases the hazard's actions by 1, and replacing a mask reduces its actions by 1."
  - name: "Reset"
    desc: "The trap deactivates and resets 1 minute after it has no target creatures"
```

```encounter-table
name: Mask of Aroden's Guises
creatures:
  - 1: Mask of Aroden's Guises
```

