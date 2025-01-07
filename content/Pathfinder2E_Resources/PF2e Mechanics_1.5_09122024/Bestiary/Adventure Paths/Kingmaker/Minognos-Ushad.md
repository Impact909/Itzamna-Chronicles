---
title: "Minognos-Ushad"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.LtebWDuDPlSddOS2" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/19
statblock: inline
name: "Minognos-Ushad"
level: 19
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Minognos-Ushad"
level: "Creature 19"
rare_03: [[Unique]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[evil]]
modifier: 30
perception:
  - name: "Perception"
    desc: "+30; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +33, Athletics: +37, Intimidation: +31, Stealth: +33"
abilityMods: [10, 6, 6, 0, 6, 4]
speed: 30 feet,  fly 100 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 43
armorclass:
  - name: AC
    desc: "43; __Fort__ +33, __Ref__ +35, __Will__ +31"
hp: 295
health:
  - name: ""
  - name: HP
    desc: "295; __Immunities__  paralyzed,  unconscious; __Resistances__ poison 20"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Savage"
    desc: "`pf2:r`  **Trigger** A creature [[Conditions/Grabbed|Grabbed]] by Minognos-Ushad critically fails a skill check to Escape.\n* * *\n\n**Effect** Minognos-Ushad makes a stinger Strike against the triggering creature."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+37 (reach 10 feet)\n__Damage__  4d10 + 18 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+37 (reach 10 feet)\n__Damage__  4d8 + 18 slashing plus improved-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+37 (agile, reach 20 feet)\n__Damage__  4d6 + 18 piercing plus wyvern-venom"

  - name: "Breath Weapon"
    desc: "`pf2:2` (poison,primal) Minognos-Ushad breathes a 60-foot cone of poison. Creatures in the cone take 20d6 poison damage (DC 41 Reflex check). Minognos-Ushad can't use Breath Weapon again for 1d4 rounds."

  - name: "Powerful Dive"
    desc: "`pf2:2` (move) Minognos-Ushad Flies up to her fly Speed and must both move forward at least 20 feet and descend at least 10 feet. If she ends her movement within melee reach of at least one enemy her size or smaller, she can make a claw Strike against that enemy. If the claw hits, as a free action she can either automatically [[Bestiary Ability Glossary/Grab|Grab]] the target or knock it [[Conditions/Prone|Prone]]."

  - name: "Punishing Momentum"
    desc: "`pf2:1`  **Requirements** Minognos-Ushad [[Conditions/Grabbed|Grabbed]] a creature this turn using Powerful Dive\n\n**Effect** Minognos-Ushad can Fly at half Speed while holding the creature in her claws, carrying that creature along with her and dropping it at the end of her movement. Alternatively, she can Strike the creature with her stinger with a +2 circumstance bonus."

  - name: "Wyvern Venom"
    desc: " (poison) **Saving Throw** DC 22 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 5d6 poison damage (1 round)\n\n**Stage 2** 6d6 poison damage (1 round)\n\n**Stage 3** 8d6 poison damage (1 round)"

  - name: "[[Bestiary Ability Glossary/Improved Grab|Improved Grab]]"
    desc: "  **Requirements** The monster's last action was a successful Strike that lists Improved Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with as a free action. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead spend an action to use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Minognos-Ushad
creatures:
  - 1: Minognos-Ushad
```


Variant wyvern

A wyvern is a venomous drake with a well-earned reputation for impatience and aggression. As much as 15 feet long and weighing up to 1,000 pounds, a wyvern's resilient body allows it to crash talons-first into large prey without serious risk to itself. A wyvern uses its momentum to stun its target before injecting it with searing venom or carrying it over the side of a nearby cliff. Because a wyvern lacks the strength to haul its prey all the way to its nest intact, it is far more likely to lift and drop its victim over a gully or canyon and let gravity do its work before it descends to pick apart the carcass.

Conversation is of little interest to a wyvern, as the creature typically speaks only to taunt its prey, issue territorial claims, or demand tribute. Even so, many wyverns enjoy grim humor and tales of violent acts, particularly if those acts were committed by the storyteller. A wyvern properly appeased with meat, entertainment, and treasure sometimes agrees to provide assistance ranging from giving directions to serving as a mount for a powerful humanoid. However, these arrangements rarely last more than a few weeks before the wyvern's pride, malice, or insolence inspires it to flee or even betray its allies. Only the truly cruel can cow a wyvern into servitude for an extended period, as most wyverns are so self-interested that they go out of their way to avoid helping others.

* * *

Ravenous, bestial, and driven by instinct-drakes are primitive draconic monsters who bear a fraction of the terrifying might of their larger cousins but little (if any) of the cunning. While they're weaker, slower, and less inclined toward reason than dragons, drakes are nonetheless a menace to creatures and settlements around them. Their propensity for forming raiding parties-small social groups fittingly called "rampages"-makes them all the more dangerous; a single rampage of river drakes can quickly lay waste to a waterside village, and roving rampages of desert drakes are a plague to caravan traders.

Drakes share a number of physical characteristics that unite them as one species despite their wide variety of habitats and abilities. For example, drakes lack forearms, leaving them only their formidable jaws and thick-scaled tails with which to attack if engaged at melee range. Most drakes would rather avoid close combat, however, preferring to use their breath weapons to wreak havoc in wide swaths from comfortable distances while flying overhead. Finally, all drakes have small reservoirs of their ancestral draconic power that they can tap into to perform incredible feats of speed.
