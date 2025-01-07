---
title: "Akizendri"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.wLHp3j0KkgpRmrlk" 
tags:
  - pf2e/creature/type/chaotic
  - pf2e/creature/type/monitor
  - pf2e/creature/type/protean
  - pf2eMonster
  - pf2e/creature/level/3
statblock: inline
name: "Akizendri"
level: 3
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 2"
name: "Akizendri"
level: "Creature 3"

alignment: ""
size: "Small"
trait_01: [[chaotic]]
trait_02: [[monitor]]
trait_03: [[protean]]
modifier: 8
perception:
  - name: "Perception"
    desc: "+8; Darkvision"
languages: "Chthonian, Empyrean, Protean; telepathy (touch)"
skills:
  - name: "Skills"
    desc: "Acrobatics: +9, Deception: +10, Occultism: +11, Society: +10, Stealth: +9, Thievery: +9"
abilityMods: [3, 4, 1, 4, 3, 1]
speed: 25 feet,  fly 25 feet,  swim 25 feet
sourcebook: "_Pathfinder Bestiary 2_"
ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__ +6, __Ref__ +11, __Will__ +10"
hp: 42
health:
  - name: ""
  - name: HP
    desc: "42, fast healing 1; __Resistances__ precision 3, protean anatomy 6"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy (Touch)]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "Entropy Sense (Imprecise) 30 feet"
    desc: " (divine,prediction) An akizendri can anticipate the most likely location of a creature through their supernatural insight into the forces of chaotic probabilities and chance. This grants the akizendri the ability to sense creatures within the listed range. A creature under the effects of [[Spells/Veil of Privacy|Veil of Privacy]] or that is otherwise shielded from divinations and predictions cannot be noticed via entropy sense."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Fast Healing|Fast Healing 1]]"
    desc: "  A monster with this ability regains the given number of Hit Points each round at the beginning of its turn."

  - name: "Protean Anatomy 6"
    desc: " (divine,polymorph) An akizendri's vital organs shift and change shape and position constantly. Immediately after the akizendri takes acid, electricity, or sonic damage, it gains the listed amount of resistance to that damage type. This lasts for 1 hour or until the next time the protean takes damage of one of the other types (in which case its resistance changes to match that type), whichever comes first.\n\nThe akizendri is immune to polymorph effects unless it is a willing target. If [[Conditions/Blinded|Blinded]] or [[Conditions/Deafened|Deafened]], the akizendri automatically recovers at the end of its next turn as new sensory organs grow to replace the compromised ones."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Jaws"
    desc: "+12 (finesse, magical)\n__Damage__  2d8 + 3 piercing plus garbled-thoughts 1d4 spirit plus garbled-thoughts"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+12 (finesse, magical)\n__Damage__  2d6 + 3 bludgeoning plus grab 1d4 spirit plus grab"

  - name: "Divine Innate Spells"
    desc: "DC 20, attack +12; __3rd __  _[[Spells/Rune Trap|Glyph of Warding]]_, _[[Spells/Secret Page|Secret Page]]_; __1st __  _[[Spells/Detect Alignment|Detect Alignment (At will) (Lawful only)]]_\n__Cantrips__  __(2nd)__ _[[Spells/Acid Splash|Acid Splash]]_, _[[Spells/Daze|Daze]]_, _[[Spells/Ghost Sound|Ghost Sound]]_, _[[Spells/Telekinetic Hand|Mage Hand]]_, _[[Spells/Sigil|Sigil]]_\n__Constant__  __(4th)__ _[[Spells/Unfettered Movement|Freedom of Movement]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The akizendri takes on the appearance of any Small or smaller creature. This doesn't change its Speed or its attack and damage bonuses with its Strikes, but might change the damage type its Strikes deal.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "[[Bestiary Ability Glossary/Constrict|Constrict]]"
    desc: "`pf2:1`  1d8+3 bludgeoning damage, DC 20 Fortitude check\n* * *\n\nThe monster deals the listed amount of damage to any number of creatures [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] by it. Each of those creatures can attempt a basic Fortitude save with the listed DC."

  - name: "Garbled Thoughts"
    desc: " (divine,emotion,mental) A creature hit by the akizendri's bite Strike must attempt a DC 20 Will check save.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature is [[Conditions/Stupefied|Stupefied 1]] for 1d4 rounds.\n\n**Critical Failure** As failure, but the creature is also [[Conditions/Confused|Confused]] for 1 round."

  - name: "Text Immersion"
    desc: " (divine) When the akizendri casts [[Spells/Secret Page|Secret Page]], it can physically immerse itself in the text, changing the message of the text in the process. It can exit the book at any point by Dismissing _secret page_, at which point it appears in a space adjacent to the text. If it does so to begin combat, it rolls a Deception check for initiative. As long as it remains immersed in the text, the akizendri has no body. It can communicate telepathically with a creature as long as the creature touches the book or scroll that contains the secret page. It can sense nearby creatures using its entropy sense, but not in any other way, nor can it use any attack, manipulate, or move actions or speak aloud. If the object it is immersed in is destroyed, the akizendri reappears in an adjacent square and is [[Conditions/Stunned|Stunned 1]]."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Akizendri
creatures:
  - 1: Akizendri
```



Akizendris gnaw at sources of knowledge and lore, gleefully corrupting and altering them to vex scholars and sages across the planes with contradictions and untruths. These proteans appear as cackling, serpentine creatures with elongated crocodilian faces, luminous eyes, and arms that vanish at the elbows into swirling clouds of runes before reforming into solid talons.

Akizendris amuse themselves by rearranging or deleting texts, placing insulting acrostics in poetic verses, and penning crude insults upon title pages. Libraries in such places as Heaven, Axis, and Hell are especially keen to avoid such contamination, knowing that their records are choice targets for every akizendri in existence.
