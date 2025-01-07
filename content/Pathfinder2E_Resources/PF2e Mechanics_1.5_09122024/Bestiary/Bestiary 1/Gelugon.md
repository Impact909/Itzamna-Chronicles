---
title: "Gelugon"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.5Mhcf0STiscNKBfu" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/evil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/lawful
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/13
statblock: inline
name: "Gelugon"
level: 13
license: OGL
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Bestiary"
name: "Gelugon"
level: "Creature 13"

alignment: ""
size: "Large"
trait_01: [[devil]]
trait_02: [[evil]]
trait_03: [[fiend]]
trait_04: [[lawful]]
trait_05: [[unholy]]
modifier: 26
perception:
  - name: "Perception"
    desc: "+26; Greater Darkvision"
languages: "Common, Diabolic, Draconic, Empyrean; telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +22, Athletics: +23, Deception: +25, Diplomacy: +25, Intimidation: +23, Religion: +26, Society: +25, Stealth: +22, Warfare Lore: +30"
abilityMods: [6, 5, 5, 8, 5, 4]
speed: 35 feet,  fly 35 feet
sourcebook: "_Pathfinder Bestiary_"
ac: 34
armorclass:
  - name: AC
    desc: "34; __Fort__ +24, __Ref__ +24, __Will__ +26; +1 status to all saves vs. magic"
hp: 215
health:
  - name: ""
  - name: HP
    desc: "215; __Immunities__  cold,  fire; __Weaknesses__ holy 10; __Resistances__ physical 10 (except silver), poison 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Longspear|+1 Striking Longspear]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Attack of Opportunity|Attack of Opportunity]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

  - name: "[[Bestiary Ability Glossary/Frightful Presence|Frightful Presence]]"
    desc: " (aura,divine,emotion,fear,mental) 10 feet. DC 31 Will check\n* * *\n\nA creature that first enters the area must attempt a Will save.\n\nRegardless of the result of the saving throw, the creature is temporarily immune to this monster's Frightful Presence for 1 minute.\n* * *\n\n**Critical Success** The creature is unaffected by the presence.\n\n**Success** The creature is [[Conditions/Frightened|Frightened 1]].\n\n**Failure** The creature is [[Conditions/Frightened|Frightened 2]].\n\n**Critical Failure** The creature is [[Conditions/Frightened|Frightened 4]]."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Frost Longspear"
    desc: "+28 (cold, magical, reach 15 feet, unholy)\n__Damage__  2d8 + 12 piercing plus slowing-frost 1d6 spirit plus slowing-frost"

  - name: "**Melee** `pf2:1` Tail"
    desc: "+25 (agile, cold, magical, reach 10 feet, unarmed, unholy)\n__Damage__  2d6 + 12 bludgeoning plus slowing-frost 2d6 cold plus slowing-frost 1d6 spirit plus slowing-frost"

  - name: "**Ranged** `pf2:1` Frost Longspear"
    desc: "+27 (cold, magical, thrown 20 ft., unholy)\n__Damage__  2d8 + 12 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 33, attack +25; __7th __  _[[Spells/Cone of Cold|Cone of Cold (x2)]]_; __6th __  _[[Spells/Illusory Scene|Illusory Scene]]_; __5th __  _[[Spells/Translocate|Dimension Door]]_, _[[Spells/Wall of Ice|Wall of Ice (x3)]]_; __4th __  _[[Spells/Translocate|Dimension Door (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Ray of Frost|Ray of Frost]]_\n__Constant__  __(4th)__ _[[Spells/Fly|Fly]]_"

  - name: "Rituals"
    desc: "_Infernal Pact_"

  - name: "Slowing Frost"
    desc: " (cold,divine) The ice devil channels the extreme cold of its body through its appendages and weapons. A creature hit by an ice devil's weapon or unarmed attack in melee must attempt a DC 32 Fortitude check save or be [[Conditions/Slowed|Slowed 1]] for 1d4 rounds. A weapon used by an ice devil gains the effects of a _[[Equipment/Frost|Frost]]_ rune while the gelugon holds it, and the ice devil can throw any such weapon with a 20-foot range increment, trailing motes of frost."

  - name: "Tactician of Cocytus"
    desc: "`pf2:1` (concentrate) An ice devil's logical mind devises genius tactics from its perfect memory. It can telepathically send a tactical repositioning to its allies, allowing all commanded or allied evil creatures in the range of its telepathy to immediately Stride (or Burrow, Climb, Fly, or Swim, if the creature has the corresponding Speed)."
 
```

```encounter-table
name: Gelugon
creatures:
  - 1: Gelugon
```



Insectile ice devils are strategists and masterminds in Hell's armies, using their superior intellect to strike against their enemies and spread Hell's influence throughout the planes. An ice devil rarely breaks their solitary contemplation of strategy save to pursue a plan they have devised. They can be enticed otherwise only by an exchange of services to be determined at a later time, adding to the pieces they can play on the board. Occasionally, a mortal strategist of outstanding skill might amuse an ice devil enough for the gelugon to agree to a contest of strategy, typically a strategic board game like chess, to decide a dispute. In the unlikely event the devil loses such a contest, they inevitably go to great lengths to later obtain that mortal's services for their own infernal ends.

* * *

Masters of corruption and architects of conquest, devils seek both to tempt mortal life to join in their pursuit of all things profane and to spread tyranny throughout all worlds. The temptations they offer mortals range from great powers granted by the signing of an infernal contract to twisted favors following a whispered pledge to a diabolic patron, or any number of even subtler exchanges. Those who succumb to these temptations find themselves consigned to an afterlife of endless torment in the pits of Hell, wherein the only hope of escape lies in the chance of being promoted to become a devil in the infernal ranks. Every devil has a specific role to play in the upkeep of the remorseless bureaucratic machine that is Hell, from soldiers and scholars to inquisitors, lawyers, judges, and executioners. Lowly lemures and imps perform subservient labor to more powerful and specialized devils, such as contract devils and erinyes, while the greatest pit fiends command entire infernal armies.
