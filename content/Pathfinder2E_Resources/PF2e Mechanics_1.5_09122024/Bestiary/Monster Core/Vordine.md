---
title: "Vordine"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.42xyLrVRhK1Rc949" 
tags:
  - pf2e/creature/type/devil
  - pf2e/creature/type/fiend
  - pf2e/creature/type/unholy
  - pf2eMonster
  - pf2e/creature/level/5
  - remaster
statblock: inline
name: "Vordine"
level: 5
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Vordine"
level: "Creature 5"

alignment: ""
size: "Medium"
trait_01: [[devil]]
trait_02: [[fiend]]
trait_03: [[unholy]]
modifier: 12
perception:
  - name: "Perception"
    desc: "+12; Greater Darkvision"
languages: "Common, Diabolic; Telepathy 100 feet"
skills:
  - name: "Skills"
    desc: "Acrobatics: +13, Athletics: +15, Intimidation: +13, Religion: +12, Warfare Lore: +13"
abilityMods: [4, 4, 5, 2, 3, 2]
speed: 25 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__ +14, __Ref__ +13, __Will__ +10; +1 status to all saves vs. magic"
hp: 60
health:
  - name: ""
  - name: HP
    desc: "60; __Immunities__  fire; __Weaknesses__ holy 5; __Resistances__ physical 5 (except silver), poison 5"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Whip|Whip]], [[Equipment/Trident|Trident]], [[Equipment/Breastplate|Breastplate]]"
  - name: "[[Bestiary Ability Glossary/Greater Darkvision|Greater Darkvision]]"
    desc: "  A creature with greater darkvision can see perfectly well in areas of darkness and dim light, though such vision is in black and white only. A creature with greater darkvision can see through even forms of magical darkness."

  - name: "[[Bestiary Ability Glossary/Telepathy|Telepathy 100 feet]]"
    desc: " (aura,magical,mental) A monster with telepathy can communicate mentally with any creatures within the listed radius, as long as they share a language. This doesn't give any special access to their thoughts, and communicates no more information than normal speech would."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/Reactive Strike|Reactive Strike]]"
    desc: "`pf2:r`  **Trigger** A creature within the monster's reach uses a manipulate action or a move action, makes a ranged attack, or leaves a square during a move action it's using.\n* * *\n\n**Effect** The monster attempts a melee Strike against the triggering creature. If the attack is a critical hit and the trigger was a manipulate action, the monster disrupts that action. This Strike doesn't count toward the monster's multiple attack penalty, and its multiple attack penalty doesn't apply to this Strike."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Trident"
    desc: "+15 (magical, unholy)\n__Damage__  1d8 + 10 piercing"

  - name: "**Melee** `pf2:1` Whip"
    desc: "+15 (disarm, finesse, magical, nonlethal, reach 10 feet, trip, unholy)\n__Damage__  1d4 + 10 bludgeoning"

  - name: "**Melee** `pf2:1` Hoof"
    desc: "+15 (agile, magical, unholy)\n__Damage__  1d4 + 7 bludgeoning 1d4 fire"

  - name: "**Ranged** `pf2:1` Trident"
    desc: "+13 (magical, thrown 20 ft., unholy)\n__Damage__  1d8 + 10 piercing"

  - name: "Divine Innate Spells"
    desc: "DC 19, attack +11; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_"

  - name: "Rituals"
    desc: "_Diabolic Pact_"

  - name: "Burning Hoofprints"
    desc: "`pf2:2` (divine,fire,unholy) The vordine Strides, trailing hoofprints in each square they exit. The hoofprints burn for 1 minute. A creature on the ground that enters a square with burning hoofprints or begins its turn in one takes 1d4 fire damage."

  - name: "Trident of Dis"
    desc: "`pf2:1`  The vordine makes a trident Strike, increasing their reach to 10 feet for that Strike. If there is an unholy ally between the vordine and their target, that creature's energy causes the Strike to deal an additional 1d6 spirit damage."
 
```

```encounter-table
name: Vordine
creatures:
  - 1: Vordine
```



The vast city of Dis trains endless legions of vordines to guard the upper layers of Hell and march across the planes at the archdevils' orders. Although quick to bend their knees to higher-ranking devils and even mortals favored by Asmodeus, vordines are relentlessly cruel to orts and other devils they can call their subordinates.

Although higher ranks in the infernal military are held by more powerful devils, like the nessari who serve as generals, a labyrinthine structure gives each vordine a rank and certain responsibilities. Some vordines are responsible for the battlefield command of squads, while others relay orders from above or are set to handling specific administrative tasks for their unit. The greatest gift one can offer a vordine is an increased rank to lord over other vordines.

* * *

Masters of corruption and architects of conquest, devils seek both to tempt mortal life to join in their pursuit of all things profane and to spread tyranny throughout all worlds. The temptations they offer mortals range from great powers granted by the signing of an infernal contract to twisted favors following a whispered pledge to a diabolic patron, or any number of even subtler exchanges. Those who succumb to these temptations find themselves consigned to an afterlife of endless torment in the pits of Hell, wherein the only hope of escape lies in the chance of being promoted to become a devil in the infernal ranks.

Every devil has a specific role to play in the upkeep of the remorseless bureaucratic machine that is Hell, from soldiers and scholars to inquisitors, lawyers, judges, and executioners. Lowly orts perform subservient labor to more powerful and specialized devils, such as infantry and contract devils, while the greatest nessaris command entire infernal armies.

Asmodeus stands at the apex of the structure he created, but the layers below him are marked by a constant jockeying for position. Most diabolic plans ultimately serve to improve the schemer's place in the hierarchy.
