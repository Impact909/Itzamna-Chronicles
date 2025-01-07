---
title: "Four-Tooth"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.p2f5XugUbiYLsGgV" 
tags:
  - pf2e/creature/type/dwarf
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2eMonster
  - pf2e/creature/level/7
statblock: inline
name: "Four-Tooth"
level: 7
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #194: Cult of the Cave Worm"
name: "Four-Tooth"
level: "Creature 7"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[dwarf]]
trait_02: [[evil]]
trait_03: [[humanoid]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Common, Dwarven, Sakvroth"
skills:
  - name: "Skills"
    desc: "Athletics: +14, Deception: +15, Intimidation: +17, Society: +12, Accounting Lore: +17"
abilityMods: [5, 1, 4, 1, 3, 4]
speed: 20 feet
sourcebook: "_Pathfinder #194: Cult of the Cave Worm_"
ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__ +18, __Ref__ +13, __Will__ +15"
hp: 120
health:
  - name: ""
  - name: HP
    desc: "120; __Resistances__ poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Spiked Chain|+1 Spiked Chain]], [[Equipment/Chain Shirt|Chain Shirt]], 44x [[Equipment/Gold Pieces|Gold Pieces]], 78x [[Equipment/Silver Pieces|Silver Pieces]], Bag"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Spiked Chain"
    desc: "+18 (disarm, finesse, trip)\n__Damage__  2d8 + 9 slashing"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+19 ()\n__Damage__  3d6 poison 1d8 + 5 piercing"

  - name: "Occult Innate Spells"
    desc: "DC 21, attack +0; __4th __  _[[Spells/Blood Vendetta|Blood Vendetta]]_; __2nd __  _[[Spells/Paranoia|Paranoia]]_\n__Cantrips__  __(4th)__ _[[Spells/Sigil|Sigil]]_"

  - name: "Jaws"
    desc: "`pf2:1`  **Requirements** Four-Tooth has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** Four-Tooth makes a jaws unarmed Strike against the grabbed or restrained target with an attack modifier of +19 that deals 1d8+5 piercing damage, deals 3d6 poison damage, and exposes the target to the sewer haze disease.\n\n## Sewer Haze\n\nMany healers and alchemists suspect that sewer haze has a supernatural origin, given its association with particularly strong otyughs.\n\n**Saving Throw** DC 23 Fortitude check\n\n**Onset** 2 days\n\n**Stage 1** [[Conditions/Stupefied|Stupefied 2]] (1 day)\n\n**Stage 2** [[Conditions/Drained|Drained 2]] and stupefied 2 (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 3]] and [[Conditions/Stupefied|Stupefied 3]] (1 day)"

  - name: "Slashing Snare"
    desc: "`pf2:2`  Four-Tooth can Step and then make a spiked chain Strike. If it hits and deals damage, he can attempt an Athletics check to [[Actions/Grapple|Grapple]] the target. Both attacks count toward his multiple attack penalty, but the penalty doesn't increase until after he's made both attacks."

  - name: "Snagging Chain"
    desc: "  Four-Tooth can use a spiked chain to [[Actions/Grapple|Grapple]] with the Athletics skill even if he doesn't have a free hand, and he adds the weapon's item bonus to attack rolls to the Athletics check."
 
```

```encounter-table
name: Four-Tooth
creatures:
  - 1: Four-Tooth
```




