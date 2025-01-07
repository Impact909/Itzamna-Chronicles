---
title: "Phistophilus"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.6SRp8pn978QjtjOV" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Phistophilus"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Phistophilus"
level: "Creature 10"

alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 21
perception:
  - name: "Perception"
    desc: "+21; Greater Darkvision"
languages: "Aklo, Chthonian, Common, Diabolic, Draconic, Empyrean, Sakvroth; Telepathy 100 feet, Truespeech"
skills:
  - name: "Skills"
    desc: "Arcana: +19, Deception: +23, Diplomacy: +21, Intimidation: +21, Religion: +19, Society: +19, Stealth: +18, Legal Lore: +25"
abilityMods: [3, 4, 4, 7, 5, 5]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__ +18, __Ref__ +18, __Will__ +23; +1 status to all saves vs. magic"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Immunities__  fire,  Ward Contract; __Weaknesses__ holy 10; __Resistances__ physical 10 (except silver), poison 10"
abilities_top:
  - name: ""

  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Ward Contract"
    desc: "  A signed contract carried by a living contract devil (including draped over its horns) is immune to damage from all creatures other than that contract devil. A contract devil is immune to mental effects that would make it destroy, nullify, or alter a contract."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Binding Contract"
    desc: "+23 (agile, disarm, magical, reach 10 feet, trip, unholy)\n__Damage__  3d6 + 11 slashing plus grab,infernal-wound"

  - name: "**Melee** `pf2:1` Horn"
    desc: "+21 (magical)\n__Damage__  3d10 + 11 piercing plus infernal-wound"

  - name: "Divine Innate Spells"
    desc: "DC 31, attack +23; __10th __  _[[Spells/Scrying|Scrying (At Will, See Infernal Investment)]]_; __7th __  _[[Spells/Interplanar Teleport|Interplanar Teleport]]_; __5th __  _[[Spells/Fireball|Fireball]]_, _[[Spells/Illusory Scene|Illusory Scene]]_, _[[Spells/Lightning Bolt|Lightning Bolt]]_, _[[Spells/Locate|Locate (At Will)]]_, _[[Spells/Mind Probe|Mind Probe]]_, _[[Spells/Sending|Sending (At Will)]]_, _[[Spells/Translocate|Translocate]]_; __4th __  _[[Spells/Peaceful Bubble|Peaceful Bubble]]_, _[[Spells/Silence|Silence]]_, _[[Spells/Translocate|Translocate (At Will)]]_; __3rd __  _[[Spells/Mind Reading|Mind Reading (At Will)]]_\n__Cantrips__  __(7th)__ _[[Spells/Detect Magic|Detect Magic]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Diabolic Pact_"

  - name: "Draft Contract"
    desc: "`pf2:3` (divine,manipulate) The contract devil produces an infernal contract for a single living mortal. This contract can grant a wide range of abilities and effects, akin to the power of a [[Spells/Wish|Wish]] ritual but fulfilled to the letter by the contract devil. To receive any of those benefits, the mortal must willingly sign its true name to the contract. At that point, the mortal's soul is bound to the contract devil and Hell.\n\nWhile the contract is in effect, the victim can't be restored to life except by _wish_ or similar magic. If the mortal is restored to life by those means, the contract devil knows which mortal came to life and can locate the creature or creatures who restored the mortal to life for 1 year, gaining the effects of a [[Spells/Locate|Locate]] spell with unlimited range. Avoiding the terms of an infernal contract is difficult and often dangerous."

  - name: "Infernal Investment"
    desc: "  A contract devil can cast a 10th-rank innate [[Spells/Scrying|Scrying]] spell at will, but only to target a creature with which they have a contract.\n\nThe target automatically critically fails its save."

  - name: "Infernal Wound"
    desc: " (divine) The wounds from a contract devil's Strikes resist healing.\n\nA spellcaster or item attempting to use healing magic on a creature suffering first attempts to counteract infernal wound (DC 29). If it is not counteracted, the healing has no effect."

  - name: "[[Bestiary Ability Glossary/Grab|Grab]]"
    desc: "`pf2:1`  **Requirements** The monster's last action was a successful Strike that lists Grab in its damage entry, or the monster has a creature [[Conditions/Grabbed|Grabbed]] or [[Conditions/Restrained|Restrained]]\n* * *\n\n**Effect** If used after a Strike, the monster attempts to [[/act grapple]] the creature using the body part it attacked with. This attempt neither applies nor counts toward the creature's multiple attack penalty.\n\nThe monster can instead use Grab and choose one creature it's grabbing or restraining with an appendage that has Grab to automatically extend that condition to the end of the monster's next turn."
 
```

```encounter-table
name: Phistophilus
creatures:
  - 1: Phistophilus
```



Contract devils are clerks, scribes, and bureaucrats of Hell rarely found outside the infernal courts, and then almost always to pursue potential contracts, tempting mortals to sell their souls in exchange for achieving their worldly desires. If a target is desirable enough, a phistophilus can offer contracts for prices seemingly lesser than their soul all at once, though in this case, the devil carefully manipulates the price to drive the signatory toward the forces of Hell anyway. Contract devils are tall creatures with skin tones that range from bronze to crimson and large curving horns extending from their bodies, over which they often drape favored or important contracts.

* * *

Masters of corruption and architects of conquest, devils seek both to tempt mortal life to join in their pursuit of all things profane and to spread tyranny throughout all worlds. The temptations they offer mortals range from great powers granted by the signing of an infernal contract to twisted favors following a whispered pledge to a diabolic patron, or any number of even subtler exchanges. Those who succumb to these temptations find themselves consigned to an afterlife of endless torment in the pits of Hell, wherein the only hope of escape lies in the chance of being promoted to become a devil in the infernal ranks.

Every devil has a specific role to play in the upkeep of the remorseless bureaucratic machine that is Hell, from soldiers and scholars to inquisitors, lawyers, judges, and executioners. Lowly orts perform subservient labor to more powerful and specialized devils, such as infantry and contract devils, while the greatest nessaris command entire infernal armies.

Asmodeus stands at the apex of the structure he created, but the layers below him are marked by a constant jockeying for position. Most diabolic plans ultimately serve to improve the schemer's place in the hierarchy.
