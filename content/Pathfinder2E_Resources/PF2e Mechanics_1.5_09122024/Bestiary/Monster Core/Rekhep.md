---
title: "Rekhep"
obsidianUIMode: preview
noteType: pf2eMonster
cssClasses: pf2e
aliases: "Actor.bD7Mdk98tJtcOjVV" 
tags:
  - pf2e/creature/type/archon
  - pf2e/creature/type/celestial
  - pf2e/creature/type/holy
  - pf2eMonster
  - pf2e/creature/level/10
  - remaster
statblock: inline
name: "Rekhep"
level: 10
license: ORC
---

```statblock
columns: 2
forcecolumns: true
layout: Basic Pathfinder 2e Layout
source: "Pathfinder Monster Core"
name: "Rekhep"
level: "Creature 10"

alignment: ""
size: "Large"
trait_01: [[archon]]
trait_02: [[celestial]]
trait_03: [[holy]]
modifier: 19
perception:
  - name: "Perception"
    desc: "+19; Darkvision"
languages: "Diabolic, Draconic, Empyrean, Utopian; Truespeech"
skills:
  - name: "Skills"
    desc: "Athletics: +21, Diplomacy: +19, Intimidation: +19, Religion: +19, Survival: +17"
abilityMods: [5, 1, 7, 2, 3, 3]
speed: 30 feet,  fly 60 feet
sourcebook: "_Pathfinder Monster Core_"
ac: 31
armorclass:
  - name: AC
    desc: "31 all-around vision; __Fort__ +23, __Ref__ +15, __Will__ +19; +1 status to all saves vs. magic"
hp: 150
health:
  - name: ""
  - name: HP
    desc: "150; __Immunities__  fear effects; __Weaknesses__ unholy 10"
abilities_top:
  - name: ""
  - name: "Items"
    desc: "[[Equipment/Lance|+1 Striking Lance]]"
  - name: "[[Bestiary Ability Glossary/Constant Spells|Constant Spells]]"
    desc: "  A constant spell affects the monster without the monster needing to cast it, and its duration is unlimited. If a constant spell gets counteracted, the monster can reactivate it by spending the normal spellcasting actions the spell requires."

abilities_mid:
  - name: ""
  - name: "[[Bestiary Ability Glossary/All-Around Vision|All-Around Vision]]"
    desc: "  This monster can see in all directions simultaneously and therefore can't be flanked."

  - name: "Archon's Protection"
    desc: "`pf2:r`  **Trigger** An enemy damages the archon's ally and both are within 15 feet of the archon\n* * *\n\n**Effect** The ally gains resistance 15 to all damage against the triggering damage and the archon can make a Strike against the enemy."

attacks:
  - name: ""

  - name: "**Melee** `pf2:1` Holy Lance"
    desc: "+22 (deadly d8, divine, holy, jousting d6, reach 10 feet)\n__Damage__  2d8 + 11 piercing 1d4 spirit"

  - name: "Divine Innate Spells"
    desc: "DC 27, attack +19; __4th __  _[[Spells/Translocate|Translocate (At Will)]]_; __2nd __  _[[Spells/Share Life|Share Life (x3)]]_; __1st __  _[[Spells/Sure Strike|Sure Strike (x3)]]_\n__Cantrips__  __(5th)__ _[[Spells/Divine Lance|Divine Lance]]_, _[[Spells/Message|Message]]_\n__Constant__  __(5th)__ _[[Spells/Truespeech|Truespeech]]_"

  - name: "[[Actor.oTw6wAZmGiL3oGWR.Item.MwMQRd6zWTqreigg|Archon's Pursuit]]"
    desc: "`pf2:2`  **Frequency** once per day\n\n**Requirements** The rekhep saw another creature teleport within the last round and has at least one [[Spells/Translocate|Translocate]] spell remaining\n* * *\n\n**Effect** The rekhep casts one of their _translocate_ spells, which is heightened to 5th rank and causes the qarna to arrive in an unoccupied space it chooses within 30 feet of the creature it's pursuing. If the creature is too far away, the rekhep arrives as close as possible."

  - name: "Courageous Switch"
    desc: "  When a rekhep uses their [[Spells/Translocate|Translocate]] innate spell, they can choose to move into the space of a willing ally they can see within range. If they do, the ally switches places with the archon, appearing in the space the archon just vacated, as if it too had cast _translocate_."

  - name: "Holy Armament"
    desc: " (divine,holy) Any weapon gains the _[[Equipment/Holy|Holy]]_ rune while the rekhep wields it."

  - name: "Living Shield"
    desc: "`pf2:1`  The rekhep grants an adjacent ally a +2 circumstance bonus to AC until they're no longer adjacent or until the start of the archon's next turn, whichever comes first. When the rekhep uses Archon's Protection against an attack against the shielded ally, the rekhep gains the resistance and takes the damage rather than the ally.\n* * *\n\n[[Bestiary Effects/Effect_ Living Shield|Effect: Living Shield]]"

  - name: "Terrifying Smite"
    desc: "`pf2:2` (emotion,fear,mental) The rekhep makes a Strike against an enemy that has one of the rekhep's allies within its reach. On a hit, the target takes an additional 2d8 mental damage and is [[Conditions/Frightened|Frightened 2]]. The extra damage and frightened value are doubled on a critical hit."
 
```

```encounter-table
name: Rekhep
creatures:
  - 1: Rekhep
```



Rekheps are the living shields that defend Heaven against fiendish incursions. They tile together in massive formations capable of withstanding any onslaught. Given their tremendous strength and imposing stature, shield archons are ideal guardians of the meek and are sometimes summoned to the mortal Universe to ward off the attacks of great numbers of evildoers.

* * *

Archons are guardians of Heaven and enemies of corruption. Before gods and their servants set foot in the celestial planes, archons already resided in Heaven, the original inhabitants of the realm. Upon meeting, the archons and divine angels quickly discovered they were of a kind, holding justice and righteousness in their hearts. An alliance was formed, and archons now serve as stalwart allies to all celestials and mortals they find worthy.

While the first archons coalesced from the immense seven-tiered mountain of Heaven, they choose willing and worthy Heaven-bound souls to join their ranks. These mortals hear and answer the call of a mysterious voice, manifesting in the Garden at the mountain's peak. There they swear to forever serve the cause of justice and transform into their new archon forms.

Though deeply concerned with defending mortal life and willing to sacrifice themselves in battle against fiends, archons often feel rote and inscrutable to others, and their forms can border on frightening and bizarre. For this reason, they often have issues with interacting with mortals, or with the free spirited azatas. Despite this, archons draw great strength from others, especially those who exemplify virtue.

Beyond their celestial allies, archons also maintain ancient ties with aeons. The inscrutable factions can still be seen working together to defend longforgotten secrets and enforce rules that predate mortal life. Archons explain these missions as necessary without further elaboration, leaving even their angelic allies frustrated with archons' obstinance.
