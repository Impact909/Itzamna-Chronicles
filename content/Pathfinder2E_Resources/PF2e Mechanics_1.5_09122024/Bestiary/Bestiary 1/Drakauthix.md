---
title: "Drakauthix"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.1xHM4GNIcFGbZq0M" 
tags:
  - pf2e/creature/type/fungus
  - pf2eMonster
  - pf2e/creature/level/9
statblock: inline
name: "Drakauthix"
level: 9
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Drakauthix"
level: "Creature 9"

alignment: ""
size: "huge"
trait_01: [[fungus]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Darkvision"
languages: ""
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +20, Stealth: +17"
abilityMods: [7, 2, 6, -4, 2, 0]
speed:  fly 20 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +21, __Ref__ +13, __Will__ +15"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Weaknesses__ fire 10, slashing 10"
abilities_top:
  - name: ""

  - name: "Sporesight (Imprecise) 60 feet"
    desc: "  The drakauthix exudes a cloud of spores that it uses to see. This is an imprecise sense that functions only in areas without strong wind currents. Sporesight does not function underwater."

abilities_mid:
  - name: ""
  - name: "Obscuring Spores"
    desc: "  Whenever the drakauthix takes at least 10 slashing damage, it releases a cloud of brown spores that has the effect of [[Spells/Mist|Mist]] for 1 minute, centered around the drakauthix. This cloud of spores does not move with the drakauthix, nor is it displaced by its movement."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tentacle"
    desc: "+20 (reach 30 feet)\n__Damage__  3d8 + 9 piercing plus improved-grab"

  - name: "Reel In"
    desc: "`pf2:1`  The drakauthix pulls all creatures it has [[Conditions/Grabbed|Grabbed]] 15 feet closer to itself."

  - name: "Spore Tendrils"
    desc: "`pf2:1`  The tendrils that cover the drakauthix's body reach out and infest adjacent creatures, dealing 4d6 poison damage and 1d6 persistent poison damage. A creature can attempt a DC 27 Reflex check save to reduce this damage, but one [[Conditions/Grabbed|Grabbed]] by the drakauthix takes a -4 circumstance penalty to this save."

  - name: "Whirlwind of Hooks"
    desc: "`pf2:2`  The drakauthix whirls, whipping creatures around it. The drakauthix makes a tentacle Strike against every creature within its reach."

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Drakauthix
creatures:
  - 1: Drakauthix
```



The drakauthix is a massive fungus that floats through the heights of the largest Darklands caverns, propelled by bladders that spray air and spores. A voracious but slow-moving hunter, the drakauthix prefers to ambush meaty creatures from above, using its hooked appendages to pull its victims upward to feed. The drakauthix's digestive process is entirely external-it clings to victims, and its spore-laden surface slowly feeds on and grows through the flesh before the spore-infested carcass is discarded. As the infested body strikes the ground below, it bursts and releases a cloud of spores, unleashing a host of young called sporelings that immediately scuttle up the cavern walls to cling to its ceiling and grow.

The drakauthix behaves no more intelligently than most predatory animals, and often uses a sort of symbiotic scavenger method to secure prey by capitalizing on the hunting methods of oozes and vermin found in the large cave systems it frequents. When a relatively mindless creature kills a victim, the drakauthix drifts down, hooks the freshly slain carcass with its tendrils, and reels in its meal. The mindless ooze or other creature that just had its food stolen rarely holds a grudge and simply slithers off to find a new quarry, letting the drakauthix digest the corpse in peace. Of course, the drakauthix isn't above feasting on more active prey as well, and might attack an adventurer who neglects to look upward for danger when exploring a network of mysterious caves.

Some Darklands-dwelling creatures, such as duergars, hunt drakauthixes for their flesh, which has a unique flavor with a peppery aftertaste. Subterranean races also make ink from drakauthixes by burning their carcasses, then grinding and pressing the ashes for a long time until a silvery substance congeals.
