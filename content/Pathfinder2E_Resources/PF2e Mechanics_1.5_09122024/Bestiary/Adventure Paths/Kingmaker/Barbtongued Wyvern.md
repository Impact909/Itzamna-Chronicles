---
title: "Barbtongued Wyvern"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.37o6dMrYqWKh0SR3" 
tags:
  - pf2e/creature/type/dragon
  - pf2e/creature/type/evil
  - pf2eMonster
  - pf2e/creature/level/18
statblock: inline
name: "Barbtongued Wyvern"
level: 18
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Kingmaker"
name: "Barbtongued Wyvern"
level: "Creature 18"
rare_03: [[Rare]]
alignment: ""
size: "huge"
trait_01: [[dragon]]
trait_02: [[evil]]
modifier: 29
perception:
  - name: "Perception"
    desc: "+29; Darkvision, Scent (Imprecise) 30 Feet"
languages: "Draconic"
skills:
  - name: "Skills"
    desc: "Acrobatics: +34, Athletics: +35, Stealth: +30"
abilityMods: [9, 6, 8, 0, 3, 4]
speed: 30 feet,  fly 100 feet
sourcebook: "_Pathfinder Kingmaker_"
ac: 42
armorclass:
  - name: AC
    desc: "42; __Fort__ +34, __Ref__ +30, __Will__ +27"
hp: 330
health:
  - name: ""
  - name: HP
    desc: "330; __Immunities__  paralyzed,  unconscious"
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
    desc: "+35 (reach 10 feet)\n__Damage__  3d12 + 17 piercing 1d6 bleed"

  - name: "**Melee** `pf2:1` Barbed Tongue"
    desc: "+35 (reach 30 feet)\n__Damage__  3d6 + 17 slashing plus ripping-grab"

  - name: "**Melee** `pf2:1` Stinger"
    desc: "+35 (agile, reach 20 feet)\n__Damage__  3d10 + 17 piercing plus barbtongued-wyvern-venom"

  - name: "Barbtongued Wyvern Venom"
    desc: " (poison) **Saving Throw** DC 40 Fortitude check\n* * *\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** 5d12 poison damage and [[Conditions/Clumsy|Clumsy 1]] (1 round)\n\n**Stage 2** 6d12 poison damage and [[Conditions/Clumsy|Clumsy 2]] (1 round)\n\n**Stage 3** 7d12 poison damage and [[Conditions/Clumsy|Clumsy 3]] (1 round)"

  - name: "Pin to the Sky"
    desc: "`pf2:1`  With incredible force, the barbtongued wyvern whips its tongue and flings barbs from its length. Up to two creatures within 200 feet of the wyvern can be targeted; each creature must attempt a DC 40 Reflex check save. The barbtongued wyvern can't use Pin to the Sky again until its next turn.\n* * *\n\n**Critical Success** The target is unaffected.\n\n**Success** The target takes 2d12+3 piercing damage.\n\n**Failure** The target takes 5d12 piercing damage and is pinned in place, fastened to the underlying magical nature of Thousandbreaths by the barbs (even if not adjacent to a solid surface). It is [[Conditions/Immobilized|Immobilized]] until it Escapes. If the creature is under the effects of a spell that would prevent it from being immobilized, Thousandbreaths first attempts a Counteract check against the spell (+27).\n\n**Critical Failure** As failure, but the target takes 10d12 piercing damage and is [[Conditions/Slowed|Slowed 1]] until it escapes."

  - name: "Reel In"
    desc: "  **Requirements** The wyvern has a creature [[Conditions/Grabbed|Grabbed]] in its tongue.\n* * *\n\n**Effect** The wyvern moves the creature up to 20 feet closer to it."

  - name: "Ripping Grab"
    desc: "`pf2:1`  **Requirements** The wyvern's last action was a success with a barbed tongue Strike, or it has a creature [[Conditions/Grabbed|Grabbed]] using this action.\n* * *\n\n**Effect** If the target was [[Conditions/Immobilized|Immobilized]] by Pin to the Sky, the wyvern first painfully rips it free of the effect, dealing 4d12 piercing damage. Regardless of whether or not the target was previously immobilized, the wyvern Grabs the target until the end of the monster's next turn. The wyvern can't use its tongue to Strike creatures until the Grab ends. Using Ripping Grab extends the duration of the monster's Grab until the end of its next turn for all creatures grabbed by it. A grabbed creature can use the [[Actions/Escape|Escape]] action to get out of the grab, and the Grab ends for a grabbed creature if the barbtongued wyvern moves away from it."
 
```

```encounter-table
name: Barbtongued Wyvern
creatures:
  - 1: Barbtongued Wyvern
```


Variant wyvern

A wyvern is a venomous drake with a well-earned reputation for impatience and aggression. As much as 15 feet long and weighing up to 1,000 pounds, a wyvern's resilient body allows it to crash talons-first into large prey without serious risk to itself. A wyvern uses its momentum to stun its target before injecting it with searing venom or carrying it over the side of a nearby cliff. Because a wyvern lacks the strength to haul its prey all the way to its nest intact, it is far more likely to lift and drop its victim over a gully or canyon and let gravity do its work before it descends to pick apart the carcass.

Conversation is of little interest to a wyvern, as the creature typically speaks only to taunt its prey, issue territorial claims, or demand tribute. Even so, many wyverns enjoy grim humor and tales of violent acts, particularly if those acts were committed by the storyteller. A wyvern properly appeased with meat, entertainment, and treasure sometimes agrees to provide assistance ranging from giving directions to serving as a mount for a powerful humanoid. However, these arrangements rarely last more than a few weeks before the wyvern's pride, malice, or insolence inspires it to flee or even betray its allies. Only the truly cruel can cow a wyvern into servitude for an extended period, as most wyverns are so self-interested that they go out of their way to avoid helping others.

* * *

Ravenous, bestial, and driven by instinct-drakes are primitive draconic monsters who bear a fraction of the terrifying might of their larger cousins but little (if any) of the cunning. While they're weaker, slower, and less inclined toward reason than dragons, drakes are nonetheless a menace to creatures and settlements around them. Their propensity for forming raiding parties-small social groups fittingly called "rampages"-makes them all the more dangerous; a single rampage of river drakes can quickly lay waste to a waterside village, and roving rampages of desert drakes are a plague to caravan traders.

Drakes share a number of physical characteristics that unite them as one species despite their wide variety of habitats and abilities. For example, drakes lack forearms, leaving them only their formidable jaws and thick-scaled tails with which to attack if engaged at melee range. Most drakes would rather avoid close combat, however, preferring to use their breath weapons to wreak havoc in wide swaths from comfortable distances while flying overhead. Finally, all drakes have small reservoirs of their ancestral draconic power that they can tap into to perform incredible feats of speed.
