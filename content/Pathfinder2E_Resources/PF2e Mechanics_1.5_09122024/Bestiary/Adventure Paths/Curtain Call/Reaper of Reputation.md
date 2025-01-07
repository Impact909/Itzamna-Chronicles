---
title: "Reaper of Reputation"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.z5azn5KUKYonDABv" 
tags:
  - pf2e/creature/type/humanoid
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/20
  - remaster
statblock: inline
name: "Reaper of Reputation"
level: 20
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder #206: Bring the House Down"
name: "Reaper of Reputation"
level: "Creature 20"
rare_03: [[Unique]]
alignment: ""
size: "Medium"
trait_01: [[humanoid]]
trait_02: [[unholy]]
modifier: 37
perception:
  - name: "Perception"
    desc: "+37; Greater Darkvision, Scent (Imprecise) 30 Feet"
languages: "Common, Diabolic; Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +35, Athletics: +34, Deception: +40, Diplomacy: +38, Intimidation: +38, Occultism: +36, Religion: +36, Society: +36, Norgorber Lore: +38, Vyre Lore: +38"
abilityMods: [6, 7, 4, 8, 7, 10]
speed: 25 feet
sourcebook: "_Pathfinder #206: Bring the House Down_"
ac: 45
armorclass:
  - name: AC
    desc: "45; __Fort__ +30, __Ref__ +35, __Will__ +37; +1 status vs. magical effects"
hp: 375
health:
  - name: ""
  - name: HP
    desc: "375; __Immunities__  mental"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "+3 Greater Striking Greater Astral Keen Wounding Rapier, +2 Greater Resilient Antimagic Raiment Leather Armor, White Cleome's Eye, Ashes of the War God, 2x Healing Potion (Greater), 2x Panacea"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Corrupt Speech"
    desc: "`pf2:r` (auditory,illusion,linguistic,occult) **Trigger** The Reaper of Reputation hears a creature speak within 30 feet\n* * *\n\n**Effect** The Reaper of Reputation manipulates those words to damage the speaker's repute by putting treacherous words on another's lips. The Reaper whispers up to 12 words and attempts a Deception check check against the Perception DC of a creature other than the triggering creature within 30 feet.\n* * *\n\n**Critical Success** The target hears the Reaper's words as if they were spoken by the triggering creature. This can alter linguistic effects. The Reaper casts subconscious suggestion on the target as part of the reaction.\n\n**Success** As critical success, except the Reaper can't cast subconscious suggestion.\n\n**Failure** The target doesn't hear the Reaper's words, and they have no effect.\n\n**Critical Failure** The target hears the Reaper speak the words."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fist"
    desc: "+35 (agile, finesse, magical)\n__Damage__  4d4 + 16 bludgeoning plus grab"

  - name: "**Melee** `pf2:1` Antler"
    desc: "+35 (magical)\n__Damage__  4d8 + 16 piercing plus knockdown"

  - name: "**Melee** `pf2:1` Rapier"
    desc: "+37 (deadly d8, disarm, finesse, magical)\n__Damage__  3d6 + 16 piercing 1d6 spirit 1d6 bleed"

  - name: "Occult Innate Spells"
    desc: "DC 41, attack +33; __10th __  _[[Spells/Fabricated Truth|Fabricated Truth]]_; __9th __  _[[Spells/Duplicate Foe|Duplicate Foe]]_, _[[Spells/Spirit Blast|Spirit Blast]]_; __8th __  _[[Spells/Disappearance|Disappearance]]_; __5th __  _[[Spells/Subconscious Suggestion|Subconscious Suggestion (At Will)]]_\n__Constant__  __(10th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Collective Memories_, _Geas_, _Planar Servitor_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,occult,polymorph) The Reaper of Reputations can take on the appearance of any Small or Medium humanoid. This doesn't change his Speed or his attack and damage bonuses with his rapier or fist Strikes, but does prevent him from using his antlers Strike. The Reaper can Change Shape to Impersonate specific individuals.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Reap Reputation"
    desc: "`pf2:2` (auditory,emotion,linguistic,mental,occult) The Reaper of Reputation makes a compelling and devastating speech in a language of his choice. Any number creatures chosen by the Reaper who are within 30 feet who can understand this speech feel their own reputations twisting as a mix of fear and paranoia take hold. Each creature in the area must attempt a DC 42 Will check save. The Reaper of Reputation can't Reap Reputation again for 1d4 rounds.\n* * *\n\n**Critical Success** The creature is unaffected.\n\n**Success** The creature takes 10d6 mental damage.\n\n**Failure** The creature becomes [[Conditions/Confused|Confused]] for 1 minute. Once the confusion effect ends, the mental anguish and memories of what they did while they were confused cause them to take 10d6 mental damage.\n\n**Critical Failure** As failure, but 20d6 mental damage and 1d6 persistent mental damage."

  - name: "Sneak Attack"
    desc: "  The Reaper of Reputation deals 3d6 extra precision damage to creatures who are [[Conditions/Off-Guard|Off-Guard]]"

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."

  - name: "[[Bestiary Ability Glossary/Knockdown|Knockdown]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Knockdown in its damage entry\n* * *\n\n**Effect** The monster attempts to [[/act trip]] the creature. This attempt neither applies nor counts toward the monster's multiple attack penalty."
 
```

```encounter-table
name: Reaper of Reputation
creatures:
  - 1: Reaper of Reputation
```


Male variant palace skelm

Skelms crave power, and the palace skelms who stalk the halls where such power concentrates are among the most dangerous of their kind. They assume titles that allow them maximum freedom to punish or hurt others with minimal oversight: any vindictive guard captain, tyrannical viceroy, or needlessly cruel magistrate could be or become a palace skelm. They delight in the wealth and status of their positions, garbing themselves in ornate finery that reflects their station.

Palace skelms ingratiate themselves with powerful individuals and gather followers by stoking fears of losing long-held or hard-earned power-especially power gained through illicit means. They undermine their enemies by encouraging competition, jealousy, and outright paranoia by way of magic and false messages. These skelms possess an unnatural ability to twist spoken words and worm their manipulative magic into others' speech, sowing confusion and hatred that might explode into violence.

A political upheaval is a palace skelm's greatest fear and opportunity alike, upsetting the balance of power he has built but providing countless new opportunities to sow hatred and evil. This conflicting goal leads palace skelms to self-sabotage and undermine their own efforts more than any other skelm.

* * *

Rage-filled skelms are drawn to any settlement with more than a few hundred souls. Using magical disguises and leveraging societal norms to their benefit, these antlered monsters crave fearful respect and brutally punish any who dare disagree with their lofty opinions, even in the slightest degree. Although quite dangerous on their own, skelms are at their deadliest when leading an angry mob. Their cruel and exploitative nature has made their name synonymous with villainy.

An existing skelm can transform any evil humanoid who's overwhelmed with rage into one of their kind. Skelms heap enraging humiliation on potential new brothers as a form of indoctrination, convincing these recruits that some other person or group is responsible for their misery. This practice ensures skelms begin their new existence with sufficient vitriol to plot their revenge.

Many newly forged skelms carry on their lives in the roles they held as mortals; and in fact, these roles often shape the type of skelm they become. Skelms can arise among members of nearly any ancestry, though they're more common among cultures with deeply entrenched gender roles, unjust hierarchies, and those that don't offer healthy ways to experience and process anger.
