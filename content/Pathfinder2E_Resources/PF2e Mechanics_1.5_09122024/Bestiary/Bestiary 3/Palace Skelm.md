---
title: "Palace Skelm"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.nSDWvedTZUjSIjOp" 
tags:
  - pf2e/creature/type/evil
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/lawful
  - pf2e/creature/type/skelm
  - pf2eMonster
  - pf2e/creature/level/8
statblock: inline
name: "Palace Skelm"
level: 8
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary 3"
name: "Palace Skelm"
level: "Creature 8"

alignment: ""
size: "Medium"
trait_01: [[evil]]
trait_02: [[humanoid]]
trait_03: [[lawful]]
trait_04: [[skelm]]
modifier: 15
perception:
  - name: "Perception"
    desc: "+15; Scent (Imprecise) 30 Feet"
languages: "Aklo, Common; tongues"
skills:
  - name: "Skills"
    desc: "Athletics: +18, Deception: +21, Diplomacy: +17, Intimidation: +17, Occultism: +16, Society: +16, Stealth: +16, Thievery: +16"
abilityMods: [6, 4, 3, 4, 3, 5]
speed: 25 feet
sourcebook: "_Pathfinder Bestiary 3_"
ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__ +17, __Ref__ +16, __Will__ +15; -2 to all saves vs. emotion effects"
hp: 155
health:
  - name: ""
  - name: HP
    desc: "155; __Weaknesses__ cold iron 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "Signet Ring"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Corrupt Speech"
    desc: "`pf2:r` (auditory,illusion,linguistic,occult) **Trigger** The skelm hears a creature speak within 30 feet\n* * *\n\n**Effect** The skelm sows paranoia by putting treacherous words on another's lips. The skelm whispers up to 12 words and attempts a Deception check check against the Perception DC of a creature other than the triggering creature within 30 feet.\n* * *\n\n**Critical Success** The target hears the skelm's words as if they were spoken by the triggering creature. This can alter linguistic effects. The skelm also casts [[Spells/Paranoia|Paranoia]] or [[Spells/Suggestion|Suggestion]] on the target, if he likes.\n\n**Success** As critical success, except the skelm can't cast _paranoia_ or _suggestion_.\n\n**Failure** The target doesn't hear the skelm's words, and they have no effect.\n\n**Critical Failure** The target hears the skelm speak the words."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+20 (agile, magical)\n__Damage__  2d8 + 9 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Antler"
    desc: "+20 (magical)\n__Damage__  2d12 + 9 piercing plus knockdown"

  - name: "Occult Innate Spells"
    desc: "DC 26, attack +18; __4th __  _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Enthrall|Enthrall]]_, _[[Spells/Outcast's Curse|Outcast's Curse]]_, _[[Spells/Paranoia|Paranoia (At Will)]]_, _[[Spells/Peaceful Bubble|Private Sanctum]]_, _[[Spells/Suggestion|Suggestion]]_; __2nd __  _[[Spells/Invisibility|Invisibility (x3)]]_\n__Cantrips__  __(5th)__ _[[Spells/Daze|Daze]]_, _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Tongues]]_"

  - name: "Rituals"
    desc: "_Inveigle_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The palace skelm can take on the appearance of any Medium male humanoid. This doesn't change his Speed or his attack and damage bonuses with his Strikes but might change the damage type his Strikes deal.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Incite Violence"
    desc: "`pf2:2` (emotion,mental,occult) **Frequency** once per day\n* * *\n\n**Effect** The skelm gives an impassioned speech calling for his followers to act upon their convictions. Each creature within 30 feet must attempt a DC 24 Will check save.\n* * *\n\n**Critical Success** The creature can immediately Strike an adjacent creature of its choosing.\n\n**Success** The creature is unaffected.\n\n**Failure** The creature immediately Strikes an adjacent creature; if multiple creatures are adjacent, the skelm chooses the target. If no creatures are adjacent, the creature is [[Conditions/Off-Guard|Off-Guard]] and [[Conditions/Fascinated|Fascinated]] with the skelm until the start of its next turn."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Palace Skelm
creatures:
  - 1: Palace Skelm
```



Skelms crave power, and the palace skelms who stalk the halls where such power concentrates are among the most dangerous of their kind. They assume titles that allow them maximum freedom to punish or hurt others with minimal oversight: any vindictive guard captain, tyrannical viceroy, or needlessly cruel magistrate could be or become a palace skelm. They delight in the wealth and status of their positions, garbing themselves in ornate finery that reflects their station.

Palace skelms ingratiate themselves with powerful individuals and gather followers by stoking fears of losing long-held or hard-earned power-especially power gained through illicit means. They undermine their enemies by encouraging competition, jealousy, and outright paranoia by way of magic and false messages. These skelms possess an unnatural ability to twist spoken words and worm their manipulative magic into others' speech, sowing confusion and hatred that might explode into violence.

A political upheaval is a palace skelm's greatest fear and opportunity alike, upsetting the balance of power he has built but providing countless new opportunities to sow hatred and evil. This conflicting goal leads palace skelms to self-sabotage and undermine their own efforts more than any other skelm.

* * *

Rage-filled skelms are drawn to any settlement with more than a few hundred souls. Using magical disguises and leveraging societal norms to their benefit, these antlered monsters crave fearful respect and brutally punish any who dare disagree with their lofty opinions, even in the slightest degree. Although quite dangerous on their own, skelms are at their deadliest when leading an angry mob. Their cruel and exploitative nature has made their name synonymous with villainy.

An existing skelm can transform any evil humanoid who's overwhelmed with rage into one of their kind. Skelms heap enraging humiliation on potential new brothers as a form of indoctrination, convincing these recruits that some other person or group is responsible for their misery. This practice ensures skelms begin their new existence with sufficient vitriol to plot their revenge.

Many newly forged skelms carry on their lives in the roles they held as mortals; and in fact, these roles often shape the type of skelm they become. Skelms can arise among members of nearly any ancestry, though they're more common among cultures with deeply entrenched gender roles, unjust hierarchies, and those that don't offer healthy ways to experience and process anger.
