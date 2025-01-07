---
title: "Nuckelavee"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.4vdspKQjBCRpVuQK" 
tags:
  - pf2e/creature/type/amphibious
  - pf2e/creature/type/fey
  - pf2eMonster
  - pf2e/creature/level/9
  - remaster
statblock: inline
name: "Nuckelavee"
level: 9
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Nuckelavee"
level: "Creature 9"

alignment: ""
size: "Large"
trait_01: [[amphibious]]
trait_02: [[fey]]
modifier: 16
perception:
  - name: "Perception"
    desc: "+16; Low-Light Vision"
languages: "Aklo, Common, Fey"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Intimidation: +19, Nature: +16, Stealth: +18, Survival: +16"
abilityMods: [6, 3, 4, 1, 3, 4]
speed: 40 feet,  swim 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__ +19, __Ref__ +16, __Will__ +20"
hp: 190
health:
  - name: ""
  - name: HP
    desc: "190; __Immunities__  disease,  poison; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Bastard Sword|+1 Striking Bastard Sword]]"
abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,emotion,fear,mental) 30 feet DC 25 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

  - name: "Purity Vulnerability"
    desc: "  Unpolluted fresh water burns a nuckelavee like acid, dealing 1d6 acid damage to it and causing it to be [[Conditions/Sickened|Sickened 2]].\n\nA nuckelavee can't heal from damage when it's in an area that isn't polluted (subject to GM discretion)."

  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Bastard Sword"
    desc: "+21 (magical, reach 10 feet, two-hand d12)\n__Damage__  2d8 + 12 slashing plus mortasheen 1d6 poison plus mortasheen"

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+20 (agile)\n__Damage__  2d8 + 12 piercing plus mortasheen 1d6 poison plus mortasheen"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+20 ()\n__Damage__  2d6 + 12 bludgeoning plus mortasheen"

  - name: "Primal Innate Spells"
    desc: "DC 28, attack +20; __5th __  _[[Spells/Control Water|Control Water]]_; __3rd __  _[[Spells/Stinking Cloud|Stinking Cloud]]_"

  - name: "Rituals"
    desc: "_Blight_"

  - name: "Blight Breath"
    desc: "`pf2:2` (disease,poison,primal) The nuckelavee breathes a 30-foot cone of foulness, dealing 8d6 void damage to living creatures in the area with a DC 28 Fortitude check save. A creature that fails also takes 2d6 bleed damage.\n\nThe nuckelavee can't use Blight Breath again for 1d4 rounds."

  - name: "Mortasheen"
    desc: " (disease) The target can't recover from the fatigued condition caused by mortasheen until the disease is cured. Mortasheen gains the virulent trait against animals and plants\n\n**Saving Throw** DC 28 Fortitude check\n* * *\n\n**Stage 1** Carrier with no ill effect (1 day);\n\n**Stage 2** [[Conditions/Drained|Drained 1]] and [[Conditions/Fatigued|Fatigued]] (1 day)\n\n**Stage 3** [[Conditions/Drained|Drained 2]] and fatigued (1 day)\n\n**Stage 4** dead"

  - name: "[[Bestiary Ability Glossary/Trample|Trample]]"
    desc: "`pf2:3`  Medium or smaller, hoof, DC 28 Reflex check\n* * *\n\nThe monster Strides up to double its Speed and can move through the spaces of creatures of the listed size, Trampling each creature whose space it enters. The monster can attempt to Trample the same creature only once in a single use of Trample. The monster deals the damage of the listed Strike, but trampled creatures can attempt a basic Reflex save at the listed DC (no damage on a critical success, half damage on a success, double damage on a critical failure)."
 
```

```encounter-table
name: Nuckelavee
creatures:
  - 1: Nuckelavee
```



When pollution despoils a natural waterway, it draws the dreaded nuckelavee to it from the First World. This spirit of wrath is a grisly sight to behold: a horselike monstrosity with the gnarled upper body of a humanoid growing directly from its back. Further enhancing its awfulness, not a patch of skin exists on the misshapen hybrid form, as though it survived its own flaying.

When a nuckelavee rides forth from its domain, it wreaks a trail of destruction across the land surrounding its path. Nuckelavees are considered among the cruelest and most monstrous fey, seen by some as just desserts visited upon those who would befoul the waters of their homes. A nuckelavee, however, doesn't discriminate between those who pollute and those who merely have the misfortune to be in the wrong place at the wrong time.

Despite their vile reputation among humanoids, nuckelavees are generally respectful of their fey counterparts. Once pollution has been cleansed and water fey like naiads return to a body of water, nuckelavees will peacefully withdraw.
