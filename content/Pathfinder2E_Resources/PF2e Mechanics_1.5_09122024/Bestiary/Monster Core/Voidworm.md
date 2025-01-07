---
title: "Voidworm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.9JiFPF7erZqQnXdN" 
tags:
  - pf2e/creature/type/monitor
  - pf2e/creature/type/protean
  - pf2eMonster
  - pf2e/creature/level/1
  - remaster
statblock: inline
name: "Voidworm"
level: 1
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Voidworm"
level: "Creature 1"

alignment: ""
size: "tiny"
trait_01: [[monitor]]
trait_02: [[protean]]
modifier: 4
perception:
  - name: "Perception"
    desc: "+4; Darkvision"
languages: "Chthonian, Protean"
skills:
  - name: "Skills"
    desc: "Acrobatics: +7, Deception: +6, Religion: +4, Stealth: +7"
abilityMods: [-1, 4, 0, -1, -1, 1]
speed: 20 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__ +5, __Ref__ +9, __Will__ +6"
hp: 16
health:
  - name: ""
  - name: HP
    desc: "16, fast healing 1; __Resistances__ precision 3, protean anatomy 5"
abilities_top:
  - name: ""

  - name: "Entropy Sense (Imprecise) 30 feet"
    desc: " (divine,prediction) A voidworm can anticipate the most likely presence of a creature through a supernatural insight into chaotic probabilities and chance. This grants them the ability to sense creatures within the listed range. [[Spells/Veil of Privacy|Veil of Privacy]] prevents a creature from being detected via entropy sense automatically (without a counteract check)."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 1]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "[[Creature Family Ability Glossary/(Protean) Protean Anatomy|Protean Anatomy]]"
    desc: " (divine) A voidworm's vital organs shift and change shape and position constantly. Immediately after the voidworm takes acid, electricity, or sonic damage, they gains the listed amount of resistance to that damage type. This lasts for 1 hour or until the next time the voidworm takes damage of one of the other types (in which case its resistance changes to match that type), whichever comes first.\n\nThe voidworm is immune to polymorph effects unless it is a willing target. If [[Conditions/Blinded|Blinded]] or [[Conditions/Deafened|Deafened]], the voidworm automatically recovers at the end of its next turn as new sensory organs grow to replace the compromised ones.\n\n[[Bestiary Effects/Effect_ Protean Anatomy|Effect: Protean Anatomy]]"

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+9 (finesse, magical)\n__Damage__  1d8 + 1 piercing"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+9 (finesse, magical)\n__Damage__  1d4 + 1 slashing plus confounding-lash"

  - name: "Divine Innate Spells"
    desc: "DC 16, attack +8; __4th __  _[[Spells/Read Omens|Read Omens]]_; __2nd __  _[[Spells/Blur|Blur (Self only)]]_, _[[Spells/Mist|Mist]]_\n__Cantrips__  __(4th)__ _[[Spells/Figment|Figment]]_, _[[Spells/Light|Light]]_, _[[Spells/Prestidigitation|Prestidigitation]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Unfettered Movement]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The voidworm takes on the appearance of a Tiny animal. This doesn't change their Speed or their attack and damage bonuses with their Strikes but might change the damage type their Strikes deal.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Confounding Lash"
    desc: " (divine,emotion,mental) A creature hit by the voidworm's tail Strike is [[Conditions/Stupefied|Stupefied 1]] for 1 round ([[Conditions/Stupefied|Stupefied 2]] on a critical hit). A successful DC 16 Will check save negates this effect and grants temporary immunity to confounding lash for 1 minute."
 
```

```encounter-table
name: Voidworm
creatures:
  - 1: Voidworm
```



Other proteans don't consider the flying, iridescent beings known as voidworms to be part of a protean caste at all, but instead merely a shameful side effect of the Maelstrom's constantly churning energy. To call a voidworm a protean in the presence of a more powerful protean is a sure a way to instigate combat.

Voidworms themselves have little interest in whether anyone sees them as proteans. They maintain a thriving ecology in the Maelstrom, frolicking in schools of up to 20 and playing in the chaos of constantly shifting realities. Elsewhere (such as in the Universe), voidworms are mesmerized by the principle of object permanence; many latch onto specific features of a region (such as a hillside or pond) and flit through the air around it for months or even years as they wait for the object of their curiosity to change. Minor changes—such as a tree's change of color in the fall, a corpse's slow decay, or periodic venting of steam from a geyser—all fascinate voidworms. A voidworm is about 2 feet long and weighs 2 pounds.

* * *

Guardians of disorder and natives of the primal plane of chaos known as the Maelstrom, proteans consider it their calling to spread bedlam and hasten entropic ends. The most powerful proteans are demigods known collectively as the protean lords, although they are mysterious entities whose cults in the Universe tend to be obscure and secretive.

Proteans divide themselves into a loose caste system and possess a dizzying variety of powers. Most proteans have a serpentine body with the head of a primeval beast. Scholars have long been intrigued by this fact—that scions of dissolution and disorder would share so many features—pointing out that there is some semblance of order even in the purest chaos. Others note that the serpentine form is one of the most primeval shapes, perhaps suggesting that in a reality at the dawn of time, such shapes were all that could exist. The proteans themselves have little to say on the matter, which, perhaps ironically, only adds to the confusion and lack of consensus surrounding their kind. After all, if even chaos cannot be trusted to be chaotic, would that not be the purest form of entropy?
