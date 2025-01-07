---
title: "Raja-Krodha"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.s85FhHFoiFtNQ9kY" 
tags:
  - pf2e/creature/type/rakshasa
  - pf2e/creature/type/spirit
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Raja-Krodha"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Raja-Krodha"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[rakshasa]]
trait_02: [[spirit]]
trait_03: [[unholy]]
modifier: 18
perception:
  - name: "Perception"
    desc: "+18; Darkvision"
languages: "Common, Diabolic, Sakvroth, Chthonian, Empyrean"
skills:
  - name: "Skills"
    desc: "Athletics: +19, Deception: +21, Diplomacy: +21, Intimidation: +21, Performance: +19, Religion: +18, Stealth: +23"
abilityMods: [6, 6, 4, 2, 2, 5]
speed: 35 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +18, __Ref__ +20, __Will__ +18; +2 status to all saves vs. magic"
hp: 180
health:
  - name: ""
  - name: HP
    desc: "180; __Immunities__  fear effects,  fortune effects,  misfortune effects; __Weaknesses__ holy 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Scimitar|Taravari]]"
abilities_mid:
  - name: ""
  - name: "Knowledge of Delusion"
    desc: "  A creature that fails a Recall Knowledge check or a Perception check to [[Actions/Sense Motive|Sense Motive]] on a raja-krodha is [[Conditions/Off-Guard|Off-Guard]] until the end of its next turn."

  - name: "Reassert Fate"
    desc: "`pf2:r` (divine) **Trigger** A creature within 30 feet uses a fortune or misfortune effect\n* * *\n\n**Effect** The raja-krodha reasserts the ebb and flow of fate, instilling a deep dread in those who would attempt to cheat their written role. They disrupt the triggering effect, and the triggering creature becomes [[Conditions/Frightened|Frightened 2]] and is [[Conditions/Off-Guard|Off-Guard]] to the raja-krodha until the end of its next turn."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Fangs"
    desc: "+20 (agile, magical, unholy)\n__Damage__  2d12 + 10 piercing"

  - name: "**Melee** `pf2:1` Claw"
    desc: "+22 (agile, finesse, magical, unholy)\n__Damage__  2d8 + 10 slashing"

  - name: "**Melee** `pf2:1` Taravari"
    desc: "+22 (forceful, magical, sweep)\n__Damage__  3d6 + 7 slashing"

  - name: "Divine Innate Spells"
    desc: "DC 29, attack +21; __5th __  _[[Spells/Crisis of Faith|Crisis of Faith]]_, _[[Spells/Hallucination|Hallucination]]_, _[[Spells/Invoke Spirits|Invoke Spirits]]_; __4th __  _[[Spells/Clairvoyance|Clairvoyance]]_, _[[Spells/Unfettered Movement|Unfettered Movement]]_, _[[Spells/Vampiric Feast|Vampiric Feast]]_; __3rd __  _[[Spells/Clairaudience|Clairaudience]]_, _[[Spells/Haste|Haste]]_; __2nd __  _[[Spells/Invisibility|Invisibility]]_\n__Cantrips__  __(5th)__ _[[Spells/Detect Magic|Detect Magic]]_, _[[Spells/Divine Lance|Divine Lance]]_"

  - name: "Cleric Domain Spells"
    desc: "2 Focus Points, DC 29, attack +21; __5th __  _[[Spells/Ignite Ambition|Ignite Ambition]]_, _[[Spells/Savor the Sting|Savor the Sting]]_"

  - name: "[[Bestiary Ability Glossary/Change Shape|Change Shape]]"
    desc: "`pf2:1` (concentrate,polymorph) The raja-krodha takes on the appearance of any Medium humanoid. This doesn't change the raja-krodha's Speed or their attack and damage modifiers with their Strikes but might change the damage type their Strikes deal (typically to bludgeoning). They lose their fangs Strike unless the humanoid form has fangs or a similar unarmed attack.\n* * *\n\nThe monster changes its shape indefinitely. It can use this action again to return to its natural shape or adopt a new shape. Unless otherwise noted, a monster cannot use Change Shape to appear as a specific individual. Using Change Shape counts as creating a disguise for the [[Actions/Impersonate|Impersonate]] use of Deception. The monster's transformation automatically defeats Perception DCs to determine whether the creature is a member of the ancestry or creature type into which it transformed, and it gains a +4 status bonus to its Deception DC to prevent others from seeing through its disguise. Change Shape abilities specify what shapes the monster can adopt. The monster doesn't gain any special abilities of the new shape, only its physical form. For example, in each shape, it replaces its normal Speeds and Strikes, and might potentially change its senses or size. Any changes are listed in its stat block."

  - name: "Cruel Majesty"
    desc: "`pf2:1` (emotion,mental,visual) **Requirements** The rakshasa is not in its true form\n* * *\n\n**Effect** The rakshasa Changes Shape into its true form in a display that is equal parts terrifying and majestic. Creatures within 30 feet of the rakshasa must succeed at a DC 29 Will check save or be [[Conditions/Off-Guard|Off-Guard]] to the rakshasa until the beginning of the rakshasa's next turn as they are awestruck."

  - name: "Sneak Attack"
    desc: "  The raja-krodha deals 2d6 extra precision damage to [[Conditions/Off-Guard|Off-Guard]] creatures."

  - name: "[[Bestiary Ability Glossary/Swallow Whole|Swallow Whole]]"
    desc: "`pf2:1` (attack) Medium, 2d12+6 bludgeoning, Rupture 15\n* * *\n\nThe monster attempts to swallow a creature of the listed size or smaller that it has grabbed or restrained in its jaws or mouth. If a swallowed creature is of the maximum size listed, the monster can't use Swallow Whole again. If the creature is smaller than the maximum, the monster can usually swallow more creatures; the GM determines the maximum. The monster attempts an Athletics check check opposed by the grabbed creature's Reflex DC. If it succeeds, it swallows the creature. The monster's mouth or jaws no longer grab a creature it has swallowed, so the monster is free to use them to Strike or Grab once again. The monster can't attack creatures it has swallowed.\n\nA swallowed creature is [[Conditions/Grabbed|Grabbed]], is [[Conditions/Slowed|Slowed 1]], and has to hold its breath or start suffocating. The swallowed creature takes the listed amount of damage when first swallowed and at the end of each of its turns while it's swallowed. If the victim [[Actions/Escape|Escapes]] this ability's grabbed condition, it exits through the monster's mouth. This frees any other creature grabbed in the monster's mouth or jaws. A swallowed creature can attack the monster that has swallowed it, but only with unarmed attacks or with weapons of light Bulk or less. The swallowing creature is [[Conditions/Off-Guard|Off-Guard]] against the attack. If the monster takes piercing or slashing damage equaling or exceeding the listed Rupture value from a single attack or spell, the swallowed creature cuts itself free. A creature that gets free by either Escaping or cutting itself free can immediately breathe and exits the swallowing monster's space.\n\nIf the monster dies, a swallowed creature can be freed by creatures adjacent to the corpse if they spend a combined total of 3 actions cutting the monster open with a weapon or unarmed attack that deals piercing or slashing damage."
 
```

```encounter-table
name: Raja-Krodha
creatures:
  - 1: Raja-Krodha
```



The most iconic rakshasas, raja-krodhas are tiger-headed hunters of mortalkind. They are incarnations of all the malice people try to deny within themselves and instead wrongly ascribe to deadly predators of the wild. Their power and skill inspire fear, but also awe, and it is not unknown for some peoples to treat such a rakshasa as a guardian, if one to be treated with extreme caution.

Despite their nature as brutal flesh-eaters, rajas are extremely eloquent and philosophical when they choose to be. This is simply another form of camouflage, one that allows them to blend into cities, much as their stripes allow them to fade into jungles, and it often lulls scholars and intellectuals into a false sense of security. While it is not in the nature of a raja-krodha to be a social schemer or a mastermind, it pleases them when others delude themselves into thinking they are.

* * *

Rakshasas are primordial, divine beings who serve as incarnations of all that is foul within creation, born the moment that the concepts of good and evil were first conceived. It is their divine purpose to exemplify the profane—by murdering their own kin, eating the flesh of sapient beings, and performing thousands of other atrocities, they define these acts as obscene and taboo, so that mortals know these acts to be crimes in the eyes of the holy. It is a role they must play, in the same way that a stage play must have an actor to serve as the villain, a role that damned all rakshasas from the moment of their genesis.

Most rakshasas enjoy their role, in the same way an actor enjoys delivering a masterful performance, yet there is an element of tragedy to their existence. They are fated to serve solely as foils to others, to corrupt the unworthy and fall to the heroic, never free to forge their own path. They are condemned to perform the most heinous of deeds, even if it rankles their sensibilities and conscience. To do otherwise is to defy their nature and their purpose: the greatest sin a rakshasa can perform.
