---
title: Tree of Dreadful Dreams
obsidianUIMode: preview
noteType: pf2eHazard
tags:
  - magical
  - trap
  - pf2eHazard
  - complex
source: Pathfinder #147: Tomorrow Must Burn
aliases: "Actor.3YvbpSoZJiMeaYaO" 
level: 10
license: OGL
statblock: inline
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #147: Tomorrow Must Burn"
name: "Tree of Dreadful Dreams"
level: "Hazard 10"

trait_06: "Complex"
trait_01: [[magical]]
trait_02: [[trap]]
modifier: 22
sourcebook: "_Pathfinder #147: Tomorrow Must Burn_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +22, __Ref__ +14, "
hp: 40
health:
  - name: ""
  - name: "HP"
    desc: "40, to break each branch; __Hardness__ 10; __Immunities__  object immunities,  critical hits,  precision"
perception:
  - name: ""
  - name: "Stealth DC 22" 
    desc: "(expert)"
abilities_top:
  - name: ""
  - name: "Description"
    desc: "The statue of the willow tree animates, its branches lashing out to try to grab anyone in area **B2**."
abilities_mid:
  - name: ""
  - name: "Disable"
    desc: "DC 25 Athletics check or DC 25 Thievery check (trained) to force or lever open a single branch, disabling that branch and freeing any creature trapped within. DC 29 Thievery check (expert) to disrupt the tree's magical animation, shut it down, and free all trapped creatures. Placing a _dreamstone_ in the tree's trunk takes 2 Interact actions and causes the trap to shut down, freeing all trapped creatures. Placing the cursed _dreamstone_ from area **B4** in the trunk instead increases the tree's actions per turn to 4 and gives it a +2 item bonus to all saving throws and attack rolls."
attacks:
  - name: ""
  - name: "Melee"
    desc: "Branch +26 (reach 20 feet) "

  - name: "Constrict"
    desc: "action 1d10+12 bludgeoning damage.\n\nDC 27 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Terrifying Visions"
    desc: "passive A creature that begins its turn grabbed by the trap experiences vivid, warped visions of true events and must succeed at a DC 31 Will check save or take 4d8 mental damage. On a critical failure, the creature also becomes [[Conditions/Doomed|Doomed 1]]. A creature that succeeds at its save is temporarily immune for 24 hours."

  - name: "Attack of Opportunity (Special)"
    desc: "`pf2:r` The tree of dreadful dreams can attempt up to six Attacks of Opportunity each round.\n\n**Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Independent Limbs"
    desc: "passive Any creature struck by the tree's Branch strike are [[Conditions/Grabbed|Grabbed]]. Additionally the tree's Branch strikes do not suffer from multiple attack penalties."

  - name: "Routine"
    desc: "(3 actions) The statue uses each action to attempt a branch Strike against a random creature in the room that it hasn't [[Conditions/Grabbed|Grabbed]]. If there are no creatures for it to attack and it has at least one creature grabbed, it instead Constricts. The trap can have up to six creatures grabbed."
  - name: "Reset"
    desc: "The trap deactivates and resets if it has no creatures [[Conditions/Grabbed|Grabbed]] and no creatures in the room to attack. If an uncursed _dreamstone_ is placed in its trunk, the statue doesn't reactivate."
```

```encounter-table
name: Tree of Dreadful Dreams
creatures:
  - 1: Tree of Dreadful Dreams
```

