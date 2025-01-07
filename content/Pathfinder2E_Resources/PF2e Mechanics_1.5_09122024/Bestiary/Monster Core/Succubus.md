---
title: "Succubus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.hCrAdiiKw46D949e" 
tags:
  - pf2e/creature/type/demon
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Succubus"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Succubus"
level: "Creature 7"
rare_03: [[Uncommon]]
alignment: ""
size: "Medium"
trait_01: [[demon]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Darkvision"
languages: "Chthonian, Common, Draconic, Empyrean; three additional mortal languages, Telepathy 100 feet, Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +14, Deception: +18, Diplomacy: +20, Intimidation: +16, Religion: +13, Society: +15, Stealth: +14"
abilityMods: [2, 3, 4, 4, 2, 7]
speed: 25 feet,  fly 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__ +15, __Ref__ +14, __Will__ +17; +1 status to all saves vs. magic"
hp: 100
health:
  - name: ""
  - name: HP
    desc: "100; __Weaknesses__ cold iron 5, holy 5"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Rejection Vulnerability"
    desc: "  As succubi are beings of pure lust, creatures that reject their lust can metaphysically harm them. When a succubus fails a Diplomacy check to Embrace or Request, or when a creature succeeds at its save against a succubus's mental spell or ability, the succubus takes 2d6 mental damage.\n\nFor 1 hour after causing mental damage to a succubus in this way, a creature can deal 2d6 mental damage to the succubus with a successful [[Actions/Demoralize|Demoralize]] action incorporating its rejection."

  - name: "Seductive Presence"
    desc: " (aura,emotion,mental) 10 feet.\n\nAny creature in the aura that could be sexually attracted to a succubus takes a –2 circumstance penalty to checks and DCs to oppose the succubus's mental spells, Deception, and Diplomacy."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Claw"
    desc: "+16 (agile, finesse, magical, unholy)\n__Damage__  2d8 + 8 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 26, attack +18; __6th __  _[[Spells/Dominate|Dominate]]_; __5th __  _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Suggestion|Suggestion (At Will)]]_, _[[Spells/Translocate|Translocate (At Will)]]_; __3rd __  _[[Spells/Mind Reading|Mind Reading (At Will)]]_; __1st __  _[[Spells/Charm|Charm (At Will)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Demonic Pact_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,divine,polymorph) The succubus can take on the appearance of any Small or Medium humanoid. This doesn't change their Speed or their attack and damage modifiers with their Strikes, but it might change the damage type their Strikes deal (typically to bludgeoning).\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Embrace"
    desc: "`pf2:1` (attack) The succubus attempts to [[/act grapple skill=diplomacy]]{Grapple} a creature using their Diplomacy bonus instead of Athletics. If the creature is willing, the succubus automatically succeeds."

  - name: "Passionate Kiss"
    desc: "`pf2:1` (divine,emotion,mental,unholy,void) **Frequency** once per round\n* * *\n\n**Effect** The succubus engages a creature they have [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]] in an embrace or other act of passion to drain its vital essence.\n\nThe kiss makes the creature [[Conditions/Drained|Drained 1]] or increases its drained value by 1, to a maximum of 4. The creature takes 3d6 void damage and the succubus regains Hit Points equal to the damage dealt. The target must succeed at a DC 26 Will check save or be affected by a [[Spells/Suggestion|Suggestion]] to submit to more actions of passion rather than trying to [[Actions/Escape|Escape]]."

  - name: "Profane Gift"
    desc: "`pf2:3` (divine,mental) **Frequency** once per day\n* * *\n\n**Effect** The succubus gives a willing humanoid a profane gift. That creature gains a +1 status bonus to attack rolls, skill checks, and saving throws. As long as the gift persists, the succubus can communicate telepathically with the target at any distance, see through the creature's senses, and target the creature with suggestion through the telepathic link. In addition, the creature uses an outcome one degree of success worse than it rolls on saving throws against the succubus's [[Spells/Suggestion|Suggestion]] spells.\n\nA humanoid can't have more than one profane gift at a time, and a succubus can't grant more than one profane gift at a time. Removing the gift requires an atone ritual. The succubus can remove the gift as a free action to give the recipient a curse, making them [[Conditions/Stupefied|Stupefied 3]] with an unlimited duration.\n\nA summoned succubus can't grant a profane gift.\n\n[[Bestiary Effects/Effect_ Profane Gift|Effect: Profane Gift]]"
 
```

```encounter-table
name: Succubus
creatures:
  - 1: Succubus
```



Succubi are manifestations of the sin of destructive lust, and they are the most attractive of all demons—as befits their role in seducing mortals to fall to sin. The concept of gender is fluid to a succubus, as they can adopt countless humanoid forms of any gender to aid in their goals. Most succubi have a feminine true form (incubi, which usually have a masculine true form, are a different kind of demon), but regardless of gender, a lust demon is supernaturally beautiful or handsome, but with curving horns, bat wings, sharp claws, and a sinuous tail.

When disguised as a mortal humanoid in the Universe, a succubus whispers into the ears of mortals, urging them to pursue their darkest and most destructive desires and pushing them into depravity, using magic only if persuasion fails. While mortals often fixate on succubi's application of sexual lust, these demons are can easily exploit lust for power, knowledge, fame, or any other desire as easily as more carnal appetites. Their ability to infiltrate societies makes them excellent spies, assassins, and political saboteurs as well. Ultimately, the succubus enjoys all means of upending mortal culture.

* * *

When a sinful mortal soul is judged and sent on to the Outer Rifts, it can become a deadly fiend—a demon. Demons are living incarnations of sin—be they classic sins like wrath or gluttony, or more "specialized" depravities like an obsession with torture or the act of treason or treachery. Once formed, a demon's driving goals are twofold—the amassing of personal power, and the corruption of mortal souls to cause them to become tainted by sin. In this way demons ensure a never-ending supply of new demons to bolster their ever-growing ranks in the Outer Rifts.

Demons are selfish and self-absorbed creatures, and most firmly believe that mortals only play at being more virtuous than fiends. They enjoy tempting mortals into damnation to both indulge their egos and swell their armies. Like many other fiends, one of the great rewards of this manipulation is fulfilling their hunger for souls. In their eyes, the primary use for these souls is to spawn new demons, who can serve as soldiers, slaves, pawns, or even currency for their more powerful masters.
