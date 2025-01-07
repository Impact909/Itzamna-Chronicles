---
title: "Globster"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.q75uwe1XqLTNBwcl" 
tags:
  - pf2e/creature/type/aquatic
  - pf2e/creature/type/ooze
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Globster"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Globster"
level: "Creature 5"

alignment: ""
size: "Large"
trait_01: [[aquatic]]
trait_02: [[ooze]]
modifier: 9
perception:
  - name: "Perception"
    desc: "+9; "
languages: ""
skills:
  - name: "Skills"
    desc: "Athletics: +15"
abilityMods: [6, -5, 5, -5, 0, -5]
speed: 15 feet,  swim 30 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 12
armorclass:
  - name: AC
    desc: "12; __Fort__ +16, __Ref__ +6, __Will__ +9"
hp: 170
health:
  - name: ""
  - name: HP
    desc: "170; __Immunities__  critical hits,  mental,  unconscious; __Weaknesses__ electricity 10"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Stench|Stench]]"
    desc: " (aura,olfactory) 30 feet, DC 19 Fortitude check\n* * *\n\nA creature entering the aura or starting its turn in the area must succeed at a Fortitude save or become [[Conditions/Sickened|Sickened 1]] (plus [[Conditions/Slowed|Slowed 1]] as long as it's sickened on a critical failure). A creature that succeeds at its save or recovers from being sickened is temporarily immune to all stench auras for 1 minute."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Tendril"
    desc: "+15 ()\n__Damage__  2d8 + 6 bludgeoning plus grab,nauseating-slap"

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+6 bludgeoning, DC 22 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Nauseating Slap"
    desc: " (poison) A living creature struck by a globster's tendril must attempt a DC 19 Fortitude check save. On a failure, the creature becomes [[Conditions/Sickened|Sickened 1]]. If the creature is already sickened, the condition value increases by 1, to a maximum of sickened 4.\n\nOnce a creature succeeds at its saving throw, it is temporarily immune for 24 hours."

  - name: "Saturated"
    desc: "  A globster can survive for 1 hour out of the water, after which it risks drowning and suffocation."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Globster
creatures:
  - 1: Globster
```



The tide washes ashore all manner of detritus, from harmless seaweed and shells to the rotting corpses of massive aquatic creatures. The globster is often mistaken for such, and this assumption isn't entirely incorrect—these mindless, oozing masses are composed of decaying sea creatures, half-digested and merged into a revolting, reeking heap of blubbery sludge.

Though mindless, globsters are predators that seek out living quarry. They often huddle on the seafloor, where their own fetid mass attracts scavengers who swiftly become the ooze's next meal. When the tides wash these monsters ashore, they simply shift to hunting land-bound prey. Coastal communities usually notice the smell of a washed-up globster long before they see it. Those sent to investigate often mistake a globster for the carcass of a beached whale before discovering the presumed corpse is very much alive and hungry.

Sages once believed globsters were undead, undulating wads of rotting flesh driven to feed, but though mindless, they are very much alive. They are attracted to waterside refuse dumps and floating garbage scows and are dimly aware enough to congregate where food is plentiful.

Since they consist of so much blubber and oily tissue, globsters can be collected for lamp oil, grease, cooking fat, and more. The goo that remains when they decompose works for this purpose, if one can stand the smell. The firmer fat deteriorates quickly, but many an impromptu goblin beach barbecue has deep-fried slabs of it as a delicacy.

Globsters consume living creatures but digest only a portion of them. The undigested dross accumulates within the globster as it becomes more and more bloated. They carry this fetid mass within their squelching bodies until instinct or injury provokes them to vomit forth a new globster to help devour everything nearby. A globster with enough dross to create a new globster automatically does so as a free action triggered upon taking damage. Treat any encounter with such a globster as though it were against two level 5 creatures, instead of just one. As far as scholars know, this is the only way these creatures can create more of their kind.
