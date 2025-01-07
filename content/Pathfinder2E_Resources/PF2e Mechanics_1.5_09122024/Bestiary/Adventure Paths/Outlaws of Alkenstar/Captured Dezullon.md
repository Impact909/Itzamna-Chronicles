---
title: "Captured Dezullon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.WZnWra7eRud9cTER" 
tags:
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Captured Dezullon"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #180: The Smoking Gun"
name: "Captured Dezullon"
level: "Creature 9"

alignment: ""
size: "Medium"
trait_01: [[plant]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Low-Light Vision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +19, Athletics: +17, Stealth: +19"
abilityMods: [5, 7, 3, -4, 2, -1]
speed: 25 feet,  climb 30 feet
sourcebook: "_Pathfinder #180: The Smoking Gun_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +15, __Ref__ +19, __Will__ +14"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110, regeneration 15 (deactivated by fire); __Resistances__ acid 20"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Regeneration|Regeneration 15 (Deactivated by Fire)]]"
    desc: "  This monster regains the listed number of Hit Points each round at the beginning of its turn. Its [[Conditions/Dying|Dying]] condition never increases beyond Dying 3 as long as its regeneration is active. However, if it takes damage of a type listed in the regeneration entry, its regeneration deactivates until the end of its next turn. Deactivate the regeneration before applying any damage of a listed type, since that damage might kill the monster by bringing it to Dying 4."

  - name: "Stench"
    desc: " (aura,olfactory) 30 feet. A creature entering the emanation must attempt a DC 27 Fortitude check save. On a failure, the creature is [[Conditions/Sickened|Sickened 1]], and on a critical failure is also [[Conditions/Slowed|Slowed 1]]. While within the aura, the creature takes a -2 circumstance penalty to saves to recover from the sickened condition. A creature that succeeds at the save is temporarily immune to this effect for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Vine"
    desc: "+21 (acid, agile)\n__Damage__  3d6 + 6 bludgeoning plus grab 3d6 acid plus grab"

  - name: "**Ranged** `pf2:1` Acid Glob"
    desc: "+23 (acid, range 30 feet)\n__Damage__  4d8 - 2 acid plus amnesia-venom"

  - name: "Amnesia Venom"
    desc: " (mental,poison) **Saving Throw** DC 29 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Off-Guard|Off-Guard]] (1 round)\n\n**Stage 2** off-guard and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 3** [[Conditions/Confused|Confused]], off-guard, and [[Conditions/Clumsy|Clumsy 2]] (1 round)"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  2d6+2 bludgeoning damage, DC 27 Fortitude check\n* * *\n\n_Note: A DC was not provided for this ability by Paizo. The DC present here is a moderate DC for the creature level according to the Gamemastery Guide creature building Tables._\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Root"
    desc: "`pf2:1` (concentrate) Until the next time it acts, the dezullon appears to be a normal pitcher plant. It has an automatic result of 41 (44 in forests or swamps) on Deception checks and DCs to pass as a non-creature plant."

  - name: "Vomit"
    desc: "`pf2:r`  **Trigger** The dezullon is damaged by an attack\n* * *\n\n**Effect** The dezullon vomits the contents of its stomach into an adjacent unoccupied space, filling the space with either a dead body or still-moving zombie (a body is in one of the dezullons, a zombie is in the other). Creatures adjacent to the dezullon must succeed at a DC 28 Reflex check save or be splashed with a dose of the dezullon's amnesia venom."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Captured Dezullon
creatures:
  - 1: Captured Dezullon
```


Weak dezullon

Dezullons are dangerous carnivorous pitcher plants that dwell in forested regions with thick canopies. They hunt for meat along the forest's understory when not sunning themselves in the boughs above. Dezullons are smart enough to notice that some creatures are attracted by shiny things, and sometimes use such objects to set up ambushes. To assume that the dezullon's ambulations are slow simply because the creature has a root structure is a foolish mistake; many an adventurer has been crushed to death by this surprisingly agile plant. In addition, these dangerous plants are expert climbers, making their pursuit even more difficult to escape from.

A hungry dezullon keeps prey off-balance by spilling its putrid, psychoactive digestive juices from its central pitcher. In addition to being highly acidic, the enzymes in a dezullon's digestive tract, once expelled, inflict a victim with powerful hallucinations and amnesia. This secondary effect makes dezullons highly sought after in some circles, including avid drug users, experimental doctors, and criminals who deal in poisons.

Many varieties of dezullon exist, including lumbering giants of incredible size, those that have tiny, cup-shaped pitchers that proliferate along lengths of creeping ivy like suckers on a squid's tentacles, and others with hundreds of blood-red, razor-sharp leaves that protrude from the inside of their pitchers like a leech's teeth. This latter variety is especially dangerous, since the leaves can all but eviscerate creatures that become ensconced inside their pitchers.
