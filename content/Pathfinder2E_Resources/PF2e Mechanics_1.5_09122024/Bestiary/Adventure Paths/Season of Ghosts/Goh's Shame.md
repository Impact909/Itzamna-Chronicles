---
title: Goh's Shame
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - haunt
  - pf2eHazard
  - complex
source: Pathfinder #197: Let the Leaves Fall
aliases: "Actor.3fCK1SKnVzzC3PX2" 
level: 5
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #197: Let the Leaves Fall"
name: "Goh's Shame"
level: "Hazard 5"

trait_06: "Complex"
trait_01: [[haunt]]
modifier: 13
sourcebook: "_Pathfinder #197: Let the Leaves Fall_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +9, __Ref__ +15, "
hp: 54
health:
  - name: ""
  - name: "HP"
    desc: "54; __Immunities__  object immunities,  critical hits,  precision; __Weaknesses__ vitality 5; __Resistances__ fire 5"
perception:
  - name: ""
  - name: "Stealth DC 13" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "A strange shadowy figure churns in the waters at Goh's feet."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 21 Diplomacy check to calm Goh enough that the haunt dissipates, DC 23 Religion check to exorcise the haunt, or DC 25 Intimidation check to \"scare the shame\" out of Goh"
attacks:
  - name: ""

  - name: "Grasping Hands"
    desc: "`pf2:r` **Trigger** Goh steps into the Ceiba River\n* * *\n\n**Effect** A shadowy figure that looks like a swimming child appears to grab ahold of Goh's ankles and begins to pull him deeper into the water; Goh becomes [[Conditions/Grabbed|Grabbed]]. The haunt then rolls initiative."
  - name: "Melee"
    desc: "Grapple +15 () "

  - name: "Routine"
    desc: "(2 actions; emotion, enchantment, fear incapacitation, mental, occult) The haunt uses its first action to grapple with Goh and attempts to pull him underwater. Goh has a Fortitude DC of 19. In order to pull Goh underwater, the haunt must critically succeed at its grapple check against him with a result of 29 or higher to successfully restrain Goh. Goh is overwhelmed by terror and makes no attempt to escape, so it falls to the PCs to get him free from the haunt. If Goh is [[Conditions/Restrained|Restrained]] and pulled underwater, the haunt must continue to grapple him in following rounds. If the haunt manages to critically succeed at grappling Goh while he's restrained, the man dies from a combination of fright and drowning, at which point the haunt immediately ends.\n\nIf Goh is pulled free and taken out of the water, the haunt loses one action and no longer attempts to grapple him. The haunt uses its second action to manifest the image of a frightening watery drowned ghost, causing one creature it targets within 30 feet to attempt a DC 22 Will check save (the haunt always targets a creature who attempted to free Goh from its grip if possible).\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]] and [[Conditions/Fleeing|Fleeing]] for as long as it remains frightened.\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 3]] and fleeing as long as it remains frightened, or for 1 minute, whichever comes second."
  - name: "Reset"
    desc: "The haunt ends if Goh dies and doesn't reset. If Goh is dragged out of the water, the haunt ends at the end of its next turn but resets immediately the next time Goh enters the river."
```

```encounter-table
name: Goh's Shame
creatures:
  - 1: Goh's Shame
```

