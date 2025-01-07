---
title: "Wyvern"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.H9Y3VwwQFHgvifZo" 
tags:
  - pf2e/creature/type/dragon
  - pf2eMonster
  - pf2e/creature/level/6
  - remaster
statblock: inline
name: "Wyvern"
level: 6
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Wyvern"
level: "Creature 6"

alignment: ""
size: "Large"
trait_01: [[dragon]]
modifier: 13
perception:
  - name: "Perception"
    desc: "+13; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Athletics: +15, Stealth: +12"
abilityMods: [5, 2, 4, -2, 3, 0]
speed: 20 feet,  fly 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +16, __Ref__ +12, __Will__ +13"
hp: 95
health:
  - name: ""
  - name: HP
    desc: "95; __Immunities__  paralyzed,  sleep"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Savage"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by the wyvern critically fails a skill check to [[Actions/Escape|Escape]]\n* * *\n\n**Effect** The wyvern makes a stinger Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+17 ()\n__Damage__  2d12 + 5 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+17 ()\n__Damage__  2d8 + 5 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+15 (agile, reach 10 feet)\n__Damage__  2d6 + 5 piercing plus wyvern-venom"

  - name: "Powerful Dive"
    desc: "`pf2:2` (move) The wyvern Flies up to their fly Speed and must both move forward at least 20 feet and descend at least 10 feet. If they end the movement within melee reach of at least one enemy their size or smaller, they can make a claw Strike against that enemy. If the claw hits, as a free action, the wyvern can either automatically Grab the target or knock it [[Conditions/Prone|Prone]]."

  - name: "Punishing Momentum"
    desc: "`pf2:1`  **Requirements** The wyvern [[Conditions/Grabbed|Grabbed]] a creature this turn using Powerful Dive\n* * *\n\n**Effect** The wyvern can Fly at half Speed while holding the creature in their claws, carrying that creature along with them and dropping it at the end of their movement. Alternatively, the wyvern can Strike the creature with their stinger with a +2 circumstance bonus."

  - name: "Wyvern Venom"
    desc: " (poison) **Saving Throw** DC 22 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 2d6 poison damage (1 round)\n\n**Stage 2** 3d6 poison damage (1 round)\n\n**Stage 3** 4d6 poison damage (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Wyvern
creatures:
  - 1: Wyvern
```



A wyvern is a venomous drake with a well-earned reputation for impatience and aggression. As much as 15 feet long and weighing up to 1,000 pounds, a wyvern's resilient body allows them to crash talons-first into large prey without serious risk to themself. A wyvern uses their momentum to stun their target before injecting it with searing venom or carrying it over the side of a nearby cliff. Because a wyvern lacks the strength to haul their prey all the way to their nest intact, they're far more likely to lift and drop their victim over a gully or canyon and let gravity do its work before they descend to pick apart the carcass.

Conversation is of little interest to a wyvern, as the creature typically speaks only to taunt their prey, issue territorial claims, or demand tribute. Even so, many wyverns enjoy grim humor and tales of violent acts, particularly if those acts were committed by the storyteller. A wyvern properly appeased with meat, entertainment, and treasure sometimes agrees to provide assistance ranging from giving directions to serving as a mount for a powerful humanoid. However, these arrangements rarely last more than a few weeks before the wyvern's pride, malice, or insolence inspires them to flee or even betray their allies. Only the truly cruel can cow a wyvern into servitude for an extended period, as most wyverns are so self-interested that they go out of their way to avoid helping others.

* * *

Ravenous, bestial, and driven by instinct, drakes are draconic monsters who bear a fraction of the terrifying might of the primal dragons they share evolutionary roots with. While they're weaker, slower, and less inclined toward reason than dragons, drakes are nonetheless a menace to creatures and settlements around them. Their propensity for forming raiding parties—small social groups fittingly called "rampages"—makes them all the more dangerous; a single rampage of river drakes can quickly lay waste to a waterside village, and roving rampages of desert drakes are a plague to caravan traders.

Drakes share a number of physical characteristics that unite them as one species despite their wide variety of habitats and abilities. For example, drakes lack forearms, leaving them with their formidable jaws and thickscaled tails to use in close combat. Most drakes would rather avoid this, however, preferring to use their magical breath to wreak havoc in wide swaths from comfortable distances while flying overhead. Finally, all drakes have small reservoirs of their ancestral draconic power that they can tap into to perform incredible feats of speed.

Different species of drakes rarely come into conflict. Part of this is their distinct habitats, but drakes are open to negotiating simple agreements between rampages. This courtesy does not extend to dragonets, which drakes happily take as prey. Solitary tamed drakes are also excluded from such agreements and considered free game if their tamer isn't strong enough to protect them.

### Drake Eggs

While drake hides aren't any more valuable than those of similarly sized creatures, drake eggs are prized commodities. They are used as components in powerful spells as well as eaten by various cultures, but the most common use for drake eggs is hatching and rearing drakes to serve as mounts and guardians.

A typical drake lays a clutch of 2d4 eggs every 5 years. Eggs hatch within 3 to 6 weeks, during which time they must be kept in conditions appropriate to their natural environment, perhaps the most difficult aspect of drake husbandry. While it is generally easy for breeders to incubate the eggs of desert or jungle drakes (which require mildly warm temperatures to hatch) or river drakes (which must be submerged in running water), the eggs of flame and frost drakes require extreme temperatures in order to hatch, which can be difficult to replicate safely.

A drake egg is an object with Hardness 3, 5 HP, and no Broken Threshold. The coloration of drake eggs varies only slightly from one species to the next. A creature must succeed at a DC 20 Nature check check, or a relevant DC 20 Lore check, to identify the drake species of a specific egg.

Once a drake hatches, they imprint on the first creature that they see. A creature imprinted on in this way can use Nature to Train and Command that drake. The market price of a drake egg varies depending on the type of drake and the exact legal situation. Because drakes are dangerous and intelligent creatures, many societies do not condone the trade of drake eggs and criminalize those who engage in it.

It takes 2 years for a drake hatchling to grow to full size. A well-trained drake can make a fearsome mount or guardian, but many careless would-be drake trainers are devoured by their charges.
