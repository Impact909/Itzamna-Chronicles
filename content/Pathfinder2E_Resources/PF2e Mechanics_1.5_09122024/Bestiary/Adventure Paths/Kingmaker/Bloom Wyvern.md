---
title: "Bloom Wyvern"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.f4l5V0FTENc4jJT8" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Bloom Wyvern"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Bloom Wyvern"
level: "Creature 8"
rare_03: [[Unique]]
alignment: ""
size: "Large"
trait_01: [[dragon]]
trait_02: [[evil]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +17, Athletics: +18, Stealth: +15"
abilityMods: [6, 3, 4, -2, 4, 0]
speed: 20 feet,  fly 60 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +18, __Ref__ +13, __Will__ +16"
hp: 135
health:
  - name: ""
  - name: HP
    desc: "135; __Immunities__  paralyzed,  unconscious"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Savage"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by the wyvern critically fails a skill check to Escape.\n* * *\n\n**Effect** The wyvern makes a stinger Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+20 (reach 10 feet)\n__Damage__  2d12 + 9 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+20 ()\n__Damage__  2d10 + 9 slashing plus grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+18 (agile, reach 10 feet)\n__Damage__  2d6 + 5 piercing plus wyvern-venom"

  - name: "Powerful Dive"
    desc: "`pf2:2` (move) The wyvern Flies up to its fly Speed and must both move forward at least 20 feet and descend at least 10 feet. If it ends the movement within melee reach of at least one enemy its size or smaller, it can make a claw Strike against that enemy. If the claw hits, as a free action the wyvern can either automatically [[Bestiary Ability Glossary/Grab|Grab]] the target or knock it [[Conditions/Prone|Prone]]."

  - name: "Punishing Momentum"
    desc: "`pf2:1`  **Requirements** The wyvern [[Conditions/Grabbed|Grabbed]] a creature this turn using Powerful Dive.\n* * *\n\n**Effect** The wyvern can Fly at half Speed while holding the creature in its claws, carrying that creature along with it and dropping it at the end of its movement. Alternatively, the wyvern can Strike the creature with its stinger with a +2 circumstance bonus."

  - name: "Wyvern Venom"
    desc: " (poison) **Saving Throw** DC 26 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 5d6 poison damage (1 round)\n\n**Stage 2** 6d6 poison damage (1 round)\n\n**Stage 3** 8d6 poison damage (1 round)"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Bloom Wyvern
creatures:
  - 1: Bloom Wyvern
```


Variant wyvern

A wyvern is a venomous drake with a well-earned reputation for impatience and aggression. As much as 15 feet long and weighing up to 1,000 pounds, a wyvern's resilient body allows it to crash talons-first into large prey without serious risk to itself. A wyvern uses its momentum to stun its target before injecting it with searing venom or carrying it over the side of a nearby cliff. Because a wyvern lacks the strength to haul its prey all the way to its nest intact, it is far more likely to lift and drop its victim over a gully or canyon and let gravity do its work before it descends to pick apart the carcass.

Conversation is of little interest to a wyvern, as the creature typically speaks only to taunt its prey, issue territorial claims, or demand tribute. Even so, many wyverns enjoy grim humor and tales of violent acts, particularly if those acts were committed by the storyteller. A wyvern properly appeased with meat, entertainment, and treasure sometimes agrees to provide assistance ranging from giving directions to serving as a mount for a powerful humanoid. However, these arrangements rarely last more than a few weeks before the wyvern's pride, malice, or insolence inspires it to flee or even betray its allies. Only the truly cruel can cow a wyvern into servitude for an extended period, as most wyverns are so self-interested that they go out of their way to avoid helping others.

* * *

Ravenous, bestial, and driven by instinct-drakes are primitive draconic monsters who bear a fraction of the terrifying might of their larger cousins but little (if any) of the cunning. While they're weaker, slower, and less inclined toward reason than dragons, drakes are nonetheless a menace to creatures and settlements around them. Their propensity for forming raiding parties-small social groups fittingly called "rampages"-makes them all the more dangerous; a single rampage of river drakes can quickly lay waste to a waterside village, and roving rampages of desert drakes are a plague to caravan traders.

Drakes share a number of physical characteristics that unite them as one species despite their wide variety of habitats and abilities. For example, drakes lack forearms, leaving them only their formidable jaws and thick-scaled tails with which to attack if engaged at melee range. Most drakes would rather avoid close combat, however, preferring to use their breath weapons to wreak havoc in wide swaths from comfortable distances while flying overhead. Finally, all drakes have small reservoirs of their ancestral draconic power that they can tap into to perform incredible feats of speed.
