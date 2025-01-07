---
title: "Coarti"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.Fj6Cw8pawkHGapIb" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/7
  - remaster
statblock: inline
name: "Coarti"
level: 7
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Coarti"
level: "Creature 7"

alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 17
perception:
  - name: "Perception"
    desc: "+17; Greater Darkvision"
languages: "Common, Diabolic, Draconic, Empyrean; Telepathy 100 feet, Truespeech"
skills:
  - name: "Skills"
    desc: "Acrobatics: +15, Athletics: +15, Deception: +17, Religion: +17, Legal Lore: +14"
abilityMods: [4, 6, 2, 3, 4, 4]
speed: 25 feet,  fly 40 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__ +13, __Ref__ +17, __Will__ +15; +1 status to all saves vs. magic"
hp: 110
health:
  - name: ""
  - name: HP
    desc: "110; __Immunities__  fire; __Weaknesses__ holy 5; __Resistances__ physical 5 (except silver), poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Morningstar|+1 Morningstar]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "Blood Contract"
    desc: "  When the coarti takes damage from their holy weakness, blood flows freely from their eyes and the contract carved into their skin. They take 1d6 persistent bleed damage and are [[Conditions/Dazzled|Dazzled]] as long as the persistent damage continues, but their Despairing Shriek recharges."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Morningstar"
    desc: "+18 (magical, unholy, versatile p)\n__Damage__  1d6 + 10 bludgeoning 1d6 spirit"

  - name: "**Melee** `pf2:1` Wing"
    desc: "+17 (agile, unholy, versatile p)\n__Damage__  1d6 fire 1d6 + 7 bludgeoning"

  - name: "Divine Innate Spells"
    desc: "DC 25, attack +17; __4th __  _[[Spells/Darkness|Darkness]]_, _[[Spells/Translocate|Translocate (At Will)]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "Rituals"
    desc: "_Diabolic Pact_"

  - name: "Despairing Shriek"
    desc: "`pf2:2` (divine,sonic,unholy) The coarti lets out a terrible cry, dealing 4d6 sonic damage to all creatures in a 30-foot emanation with a DC 25 Will check save. Holy creatures that fail this save are also [[Conditions/Frightened|Frightened 2]]; this added effect has the emotion, fear, and mental traits.\n\nThe coarti can't use Despairing Shriek again for 1d4 rounds."

  - name: "Wing Snap"
    desc: "`pf2:1`  **Frequency** once per turn\n* * *\n\n**Effect** The coarti makes two wing Strikes, then falls if it's flying. It can't Fly until the end of its turn."
 
```

```encounter-table
name: Coarti
creatures:
  - 1: Coarti
```



The burning-winged coartis are marked by the onerous contracts they agreed to and bound to Hell by the machinations of a legalistic devil, usually a phistophilus. Some coartis are truly a type of fallen celestial, those trapped in horrible agreements for the greater good or due to grievous errors in judgment, but most arise from mortal souls that were on the path to become celestials yet were contractually bound to Hell. Coartis serve in public roles as messengers and personal attendants to demonstrate the power of Hell and the legal acumen of their corruptors.

Celestials universally pity coartis and despise their creators, but their preferred methods of dealing with the corrupted beings differ. While angels argue against lost cases in Pharasma's courts, seeking loopholes in the voluminous contracts, azatas scheme daring heists against the contract storehouses. Archons are the most direct, working to end their blighted lives.

* * *

Masters of corruption and architects of conquest, devils seek both to tempt mortal life to join in their pursuit of all things profane and to spread tyranny throughout all worlds. The temptations they offer mortals range from great powers granted by the signing of an infernal contract to twisted favors following a whispered pledge to a diabolic patron, or any number of even subtler exchanges. Those who succumb to these temptations find themselves consigned to an afterlife of endless torment in the pits of Hell, wherein the only hope of escape lies in the chance of being promoted to become a devil in the infernal ranks.

Every devil has a specific role to play in the upkeep of the remorseless bureaucratic machine that is Hell, from soldiers and scholars to inquisitors, lawyers, judges, and executioners. Lowly orts perform subservient labor to more powerful and specialized devils, such as infantry and contract devils, while the greatest nessaris command entire infernal armies.

Asmodeus stands at the apex of the structure he created, but the layers below him are marked by a constant jockeying for position. Most diabolic plans ultimately serve to improve the schemer's place in the hierarchy.
