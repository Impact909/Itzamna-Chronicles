---
title: "Flytrap Leshy"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.YSMGjFWXIaKREdjs" 
tags:
  - pf2e/creature/type/leshy
  - pf2e/creature/type/plant
  - pf2eMonster
  - pf2e/creature/level/4
statblock: inline
name: "Flytrap Leshy"
level: 4
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Flytrap Leshy"
level: "Creature 4"

alignment: ""
size: "Small"
trait_01: [[leshy]]
trait_02: [[plant]]
modifier: 11
perception:
  - name: "Perception"
    desc: "+11; Darkvision"
languages: "Common, Fey, Wildsong; speak with plants (carnivorous plants only)"
skills:
  - name: "Skills"
    desc: "Athletics: +12, Nature: +10, Stealth: +12"
abilityMods: [4, 2, 1, 0, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__ +9, __Ref__ +12, __Will__ +13"
hp: 72
health:
  - name: ""
  - name: HP
    desc: "72; __Resistances__ acid 5"
abilities_top:
  - name: ""

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "Verdant Burst"
    desc: " (healing,plant) When a flytrap leshy dies, a burst of primal energy explodes from its body, restoring 3d6 healing Hit Points to each plant creature in a 30-foot emanation.\n\nThis area immediately fills with flytraps, becoming difficult terrain. If the terrain is not a viable environment for these flytraps, they wither after 24 hours."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Flytrap Mouth"
    desc: "+13 (versatile s)\n__Damage__  1d8 + 6 piercing plus flytrap-toxin 1d6 acid plus flytrap-toxin"

  - name: "**Melee** `pf2:1` Flytrap Hand"
    desc: "+13 (agile, versatile s)\n__Damage__  1d6 + 6 piercing plus flytrap-toxin 1d6 acid plus flytrap-toxin"

  - name: "**Ranged** `pf2:1` Spittle"
    desc: "+11 (acid, range increment 10 feet)\n__Damage__  1d6 + 6 acid plus flytrap-toxin"

  - name: "Primal Innate Spells"
    desc: "DC 21, attack +11; __4th __  _[[Spells/Speak with Plants|Speak with Plants]]_; __2nd __  _[[Spells/Vanishing Tracks|Pass Without Trace]]_"

  - name: "Amalgam"
    desc: "`pf2:1` (polymorph,primal) A flytrap leshy can combine itself with an adjacent and willing flytrap leshy that is not currently affected by Amalgam. The leshy using Amalgam physically merges with the target, restoring 3d8 healing Hit Points to the target.\n\nThe leshy can Sustain a Spell to continue Amalgam, but once they stop, the target leshy takes 3d8 damage. If the target leshy dies, Amalgam ends at once and the original leshy gains the [[Conditions/Dying|Dying]] condition or increases their dying condition value by 1 if they were already dying.\n\nAs long as Amalgam is sustained, the target leshy gains a +1 status bonus to attack rolls and saving throws, its AC increases to 21, and it gains an additional reaction at the start of each turn."

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph,primal) The flytrap leshy transforms into a Small flytrap. This ability otherwise uses the effects of [[Spells/One with Plants|One with Plants]].\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Flytrap Toxin"
    desc: " (poison) **Saving Throw** DC 19 Fortitude check\n\n**Maximum Duration** 6 rounds\n\n**Stage 1** [[Conditions/Sickened|Sickened 1]] (1 round),\n\n**Stage 2** [[Conditions/Sickened|Sickened 2]] (1 round)"
 
```

```encounter-table
name: Flytrap Leshy
creatures:
  - 1: Flytrap Leshy
```



While often seen as unfriendly by non-leshys, flytrap leshys get along well with other leshys. Nonetheless, they're among the most aggressive leshys, often guarding the most vulnerable places in the natural world with their flytrap mouths and hands.

When a large threat emerges, pairs of flytrap leshys band together to create amalgams capable of driving back powerful foes. This unusual form of communal defense suffuses flytrap leshy society, and they often form relationships between multiple individuals that would confuse or even scandalize more uptight humanoids-to a flytrap leshy, though, there's nothing strange about sharing your innermost secrets with people you literally merged together with to defend your home from an enemy.
